#### Parser Content
```Java
{
Name = bro-ftp-1
  DataType = "app-activity"
  Conditions = [ """"id.orig_h""", """"id.resp_h""", """"command":""", """"user""", """"reply_code""" ]
  Fields = ${BroParserTemplates.json-bro-activity.Fields}[
    """"user":\s*"({user}[^"]+)""",
    """"password":\s*"({password}[^"]+)""",
    """"command":\s*"({activity}[^"]+)""",
    """"reply_code":\s*({trans_id}\d+)""",
    """"reply_msg":\s*"({additional_info}[^"]+)""",
    """"data_channel\.resp_p":\s*({dest_port}\d+)""",
  ]
}
json-bro-activity = {
  Vendor = Bro
  Lms = Direct
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSS"
  Fields = [
    """exabeam_host=([^@=]+@\s*)?({host}\S+)""",
    """"ts\\?"+:\\?"+({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{3})""",
    """"uid\\?"+:\\?"+({conn_id}[^"]+)""",
    """"id\.orig_h\\?"+:\\?"+({src_ip}[a-fA-F\d.:]+)""",
    """"id\.orig_p\\?"+:({src_port}\d+)""",
    """"id\.resp_h\\?"+:\\?"+({dest_ip}[a-fA-F\d.:]+)""",
    """"id\.resp_p\\?"+:({dest_port}\d+)""",
    """"proto\\?"+:\\?"+({protocol}[^"]+)""",
  ]

```