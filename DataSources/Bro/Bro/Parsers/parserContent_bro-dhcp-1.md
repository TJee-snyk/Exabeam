#### Parser Content
```Java
{
Name = bro-dhcp-1
  DataType = "dhcp"
  Conditions = [ """"id.orig_h""", """"id.resp_h""", """"assigned_ip""", """"lease_time""" ]
  Fields = ${BroParserTemplates.json-bro-activity.Fields}[
    """"assigned_ip":\s*"({assigned_ip}[a-fA-F\d.:]+)""",
    """"lease_time":\s*({lease_time}[\d\.]+)""",
    """"trans_id":\s*({trans_id}\d+)""",
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