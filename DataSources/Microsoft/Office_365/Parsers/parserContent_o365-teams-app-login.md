#### Parser Content
```Java
{
Name = o365-teams-app-login
  Vendor = Microsoft
  Product = Office 365
  Lms = Direct
  DataType = "app-login"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """"Workload""", """"Operation":"TeamsSessionStarted"""" ]
  Fields = [
    """exabeam_host=({host}[\w.\-]+)""",
    """"CreationTime":"({time}\d+\-\d+\-\d+T\d+:\d+:\d+)"""",
    """"Workload":"({app}[^"]+)"""",
    """"UserId":"({user_email}[^"]+)"""",
    """\Wsuser=({user_email}[^@]+@[^\s+?])\s+(\w+=|$)""",
    """"ObjectId":"(Unknown|({os}[^"\(\)]+[^\s\(\)]))"""
  ]
}
```