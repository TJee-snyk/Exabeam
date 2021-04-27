#### Parser Content
```Java
{
Name = q-kiteworks-file-upload
  Product = Kiteworks
  Conditions = [ """Uploaded file""", """Activity:""", """File: id=""" ]
  Fields = ${KiteWorksParserTemplates.q-kiteworks-file-activity.Fields}[
    """({accesses}Uploaded) file ({file_name}.+?(\.({file_ext}\w+))?)\.\s*File:""",
    """({accesses}Uploaded) file "+({file_name}[^"]+?(\.({file_ext}\w+))?)"""",
  ]
}
q-kiteworks-file-activity = {
    Vendor = Accellion
    Lms = QRadar
    DataType = "file-operations"
    IsHVF = true
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Fields = [
      """\w+\s+\d+ \d+:\d+:\d+\s+({host}[\w.\-]+)\s+""",
      """({host}[\w.\-]+)\s+rest_server.py:""",
      """exabeam_endTime=({time}\d+)""",
      """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
      """\ssize=({bytes}\d+)""",
      """({user_email}[^@\s]+@({email_domain}[^\s]+))\s+id=[^,]+,\s*({src_ip}[a-fA-F\d.:]+),\s*Activity:?""",
      """Activity:\s*({activity}.+?)\."*\s*$""",
      """Activity Type:\s+({activity}[^\s,]+)"""
    ]

```