#### Parser Content
```Java
{
Name = moveit-authentication-failed
  DataType = "authentication-failed"
  Conditions = [ """AgentBrand: MOVEit""", """authentication failed"""]
  Fields = ${MoveITParserTemplates.moveit-activity.Fields} [
     """\sMessage:\s*({failure_reason}[^,\."]+)""",
  ]
}
moveit-activity = {
  Vendor = Ipswitch
  Product = MoveIt DMZ
  Lms = Syslog
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d.\d\d\dZ)"""
    """\s\d\d:\d\d:\d\d\s({host}[^\s]+)""",
    """\sIPAddress:\s*({src_ip}\d{1,3}.\d{1,3}.\d{1,3}.\d{1,3})""",
    """User\s'(({user_email}[^@]+@[^']+)|Automation|({user_fullname}[^']+))?'\s\(({user}[^\)]+)?\)""",
    """\s:\s+({activity}[^,]+),\s+ID:""",
    """\sUsername:\s*(Automation|({user}[^,]+))"""
  ]

```