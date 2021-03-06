#### Parser Content
```Java
{
Name = s-common-ftp-download
  Vendor = FTP
  Lms = Splunk
  DataType = "file-operations"
  IsHVF = true
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """]sent /""", """ - 200 """ ]
  Fields = [
    """exabeam_host=([^=]+?@\s*)?({host}[^\s]+)""",
    """(exabeam_\w+=|^)({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d) """,
    """({host}[\w\.-]+)\s+(\S+\s+){2}\[\d+\]""",
    """({src_ip}\S+)\s+(\S+\s+){2}\[\d+\]""",
    """(-|(({domain}\S+)[\/\\])?({user}\S+))\s+\[\d+\]""",
    """\]sent\s+(-|({file_name}\S+))\s""",
    """\]sent\s+(-|({file_path}({file_parent}\/(\S+\/)?)({file_name}\S+)))\s""",
    """\]sent\s+\/\S+\.({file_ext}[^\/\.\s]+)\s""",
    """\]sent\s+(\S+\s+){2}({outcome}\d+)""",
    """\]sent\s+(\S+\s+){3}({bytes}\d+)""",
  ]
  DupFields = [ "host->dest_host", "file_ext->host_file_ext" ]
}
```