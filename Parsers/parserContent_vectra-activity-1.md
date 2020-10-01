#### Parser Content
```Java
{
Name = vectra-activity-1
  Product = Vectra
  Vendor = Vectra
  Lms = Splunk
  DataType = "app-activity"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """vectra_timestamp""","""reason""","""action""","""src_name"""]
  Fields =[
    """({time}\d+-\d+-\d+T\d+:\d+:\d+)""",
    """({app}vectra)""",
    """"*dvchost"*:\s*"+({host}[^"]+)""",
    """"*src_name"*:\s*"+({src_host}[^"]+)""",
    """"*dest_name"*:\s*"+({dest_host}[^"]+)""",
    """"*src_ip"*:\s*"+({src_ip}[^"]+)""",
    """"*action"*:\s*"+({activity}[^"]+)""",
    """"*dest_ip"*:\s*"+({dest_ip}[^"]+)""",
    """"*reason"*:\s*"+({result}[^"]+)"""
  ]
 }

${SentinelOneParserTemplates.sentinelone-activity}{
  Name = sentinelone-web-activity
  DataType = "web-activity"
  Conditions = [ """CEF:""", """dproc=Deep Visibility Endpoint""", """destinationServiceName=SentinelOne""", """method:""", """http""" ]
  Fields = ${SentinelOneParserTemplates.sentinelone-activity.Fields} [
    """exabeam_host=([^=]+@\s*)?({host}\S+)""",
    """,({time}\d+-\d+-\d+T\d+:\d+:\d+.\d+Z)""",
    """method:\s*"+({method}[^"]+)""",
    """url:\s*"+({full_url}({protocol}[^:\\\/\s,"]+):\/*({web_domain}[^\\\/\s:,"]+)(:({dest_port}\d+))({uri_path}\/[^\s\?"]*)?({uri_query}\?[^"\s]*)?)""",
    """\shttp.+?({top_domain}[^\/\.\s]+(?i)(\.(com|net|info|edu|org|gov|co|jp|ru|de|ir|it|in|fr|info|pl|nl|es|gr|cz|eu|tv|me|jp|ca|cn|uk|my|cc|id|us|nz|biz|club|io|gg|fi|au|st|tw|asia|sg|ie|li|za))+)"""
  ]
}
```