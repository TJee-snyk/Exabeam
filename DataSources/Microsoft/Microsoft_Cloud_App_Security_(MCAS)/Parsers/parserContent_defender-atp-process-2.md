#### Parser Content
```Java
{
Name = defender-atp-process-2
  DataType = "process-created"
  Conditions = [  """"Type":"AdvancedHuntingDeviceProcessEvents_CL""", """TimeGenerated""", """TenantId""" ]
  Fields = ${MicrosoftParserTemplates.defender-atp-events.Fields}[
]
}
defender-atp-events = {
    Vendor = Microsoft
    Product = Microsoft Defender ATP
    Lms = Splunk
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSSSSSZ"
    Fields = [
      """"time":"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d\.\d{1,100}Z)""",
      """"DeviceName":"({host}[^"]+)""""
      """"LogonType":"({logon_type}[^"]+)"""",
      """"AccountName":"({user}[^"]+)"""",
      """"AccountDomain":"({domain}[^"]+)"""",
      """"InitiatingProcessFileName":"({process_name}[^"]+)"""",
      """"category":"({event_name}[^"]+)"""",
      """"ActionType":"({outcome}[^"]+)"""",
      """"RemoteIP":"({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})"""",
      """"Protocol":"({protocol}[^"]+)""""
    ]

```