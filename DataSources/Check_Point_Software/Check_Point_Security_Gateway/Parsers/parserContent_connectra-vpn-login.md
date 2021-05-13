#### Parser Content
```Java
{
Name = connectra-vpn-login
  Vendor = Check Point Software
  Product = Check Point Security Gateway
  Lms = Direct
  DataType = "vpn-start"
  TimeFormat = "ddMMMyyyy HH:mm:ss"
  Conditions = [ """|product=Connectra|""", """|event_type=Login|""", """|status=Success|""" ]
  Fields = [
    """\|(U|u)ser=({user_firstname}[^,@\|]+),\s{0,100}({user_lastname}[^@\|]+)@({domain}[^\s\|]+)\s{0,100}\(({user}[^\)\|]+)\)\s{0,100}(\||$)""",
    """\|user_dn=({user_ou}[^\|]+)\|""",
    """\|user_group=({realm}[^\|]+)""",
    """\|time=({time}\d{1,100}\w+\d\d\d\d \d{1,100}:\d{1,100}:\d{1,100})""",
    """\|src=(?:({src_ip}[a-fA-F\d.:]+)|({src_host}[\w.\-]+))\|""",
    """\|office_mode_ip=({host}[a-fA-F\d.:]+)""",
    """\|Hostname=({host}[^\|]+)\|""",
    """\|User=({user}[^,]+)""", 
  ]
  DupFields = ["user->account"]
}
```