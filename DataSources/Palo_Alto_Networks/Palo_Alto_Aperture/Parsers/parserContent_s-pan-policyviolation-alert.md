#### Parser Content
```Java
{
Name = s-pan-policyviolation-alert
    Vendor = Palo Alto Networks
    Product = Palo Alto Aperture
    Lms = Splunk
    DataType = "dlp-alert"
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
    Conditions = [ """"policy_violation"""", "cloud_app_instance" ]
    Fields = [
      """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)Z""",
      """exabeam_host=({host}[^\s]+)""",
      """\Wpolicy_rule_name\s*=\s*"({alert_name}[^"]+)"""",
      """\Witem_type\s*=\s*"({item_type}[^"]+)"""",
      """\Witem_type\s*=\s*"user"(\s*\w+\s*=\s*"[^"]*")*\s*item_name\s*=\s*"({user_email}[^"]+)"""",
      """\Witem_name\s*=\s*"({user_email}[^"]+)"(\s*\w+\s*=\s*"[^"]*")*\s*item_type\s*=\s*"user"""",
      """\Wcloud_app_instance\s*=\s*"({alert_type}[^"]+)"""",
      """\Waction_taken\s*=\s*"({additional_info}[^"]+)"""",
    ]
    DupFields = [ "user_email->user" ]
    SOAR {
    IncidentType = "dlp"
    DupFields = ["time->startedDate", "vendor->source", "rawLog->sourceInfo", "user->dlpUser", "alert_name->dlpPolicy", "alert_type->description", "host->dlpDeviceName"]
    NameTemplate = """Palo Alto DLP Alert ${alert_name} found"""
    ProjectName = "SOC"
    EntityFields = [
      {EntityType="user", Name="windows_id", Fields=["user->windows_id"]}
```