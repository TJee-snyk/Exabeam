#### Parser Content
```Java
{
Name = win-powershell-command
  Vendor = Microsoft
  Product = Microsoft Windows
  Lms = Direct
  DataType = "process-created"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSSSZ"
  Conditions = [ """>4103</EventID>""", """CommandInvocation""", """Script Name =""" ]
  Fields = [
    """exabeam_host=({host}[\w\-.]+)""",
    """<TimeCreated SystemTime=\'({time}\d{4}-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{9}Z)\'\/>"""
    """>({event_code}4103)<\/EventID>"""
    """<Computer>({dest_host}.*?)<\/Computer>"""
    """<Security UserID='({user_sid}[\w-]+)'"""
    """Script Name =\s+({process}({directory}([\w:]+\\)?([^\\]+?\\)*?)({process_name}[^\\]*?))\s+Command Path ="""
    """User = (({domain}[^\\]+?)\\)?({user}[^\s]+)\s+Connected User ="""
  ]

}
```