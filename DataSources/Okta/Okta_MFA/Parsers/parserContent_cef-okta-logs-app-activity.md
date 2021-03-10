#### Parser Content
```Java
{
Name = cef-okta-logs-app-activity
  Vendor = Okta
  Product = Okta MFA
  Lms = ArcSight
  DataType = "app-activity"
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSS"
  Conditions = [ """"actor":""", """"securityContext":""", """"target":""", """"client":""" ]
  Fields=[
    """exabeam_host=([^=]+@\s*)?({host}\S+)""",
    """"published"\s*:\s*"({time}\d\d\d\d\-\d\d\-\d\dT\d\d:\d\d:\d\d\.\d\d\d)""",
    """"displayMessage"\s*:\s*"({event_name}[^"]+)""",
    """"eventType"\s*:\s*"({activity}[^"]+)""",
    """request"+:.+?User.+?"+displayName"+:(null|"+(Okta System|(?:({user_firstname}[^,"]+),\s*({user_lastname}[^"]+)|({user_fullname}[^"]+)))")""",
    """"actor"+.+?"+type"+:"+User.+?displayName"+:(null|"+(Okta System|Okta Admin|(?:({user_lastname}[^,"]+),\s*({user_firstname}[^"]+)|({user_fullname}[^"]+))))""",
    """"client":[^\]]*?"browser"\s*:\s*"(?:UNKNOWN|({browser}[^"]+))""",
    """"client":[^\]]*?"os"\s*:\s*"(Unknown|({os}[^"]+))""",
    """"client":[^\]]*?"rawUserAgent"\s*:\s*"({user_agent}[^"]+)""",
    """"client":[^\]]*?"ipAddress"\s*:\s*"({src_ip}[^"]+)""",
    """"outcome":[^\]]*?"result"\s*:\s*"FAILURE","reason":"({failure_reason}[^"]+)""",
    """"outcome":[^\]]*?"result"\s*:\s*"({outcome}[^"]+)"""",
    """"target":.+?"displayName"\s*:\s*"({object}[^"]+[^\s])"""",
    """"target":.+?"type"\s*:\s*"({object_type}[^"]+)"""",
    """({app}OKTA)""",
    """({app}Okta)""",
    """"city":"({location_city}[^"]+)""",
    """"state":"({location_state}[^"]+)""",
    """"country":"({location_country}[^"]+)""",
    """request"+:.+?"+type"+:"+User"+,"+alternateId"+:(null|"+(system@okta\.com|(?:({user_email}[^"@]+@({domain}[^"]+))|({user}[^"]+))))""",
    """"actor"+:[^\]]*?"+type"+:"+User"+,"+alternateId"+\s*:\s*"+(system@okta\.com|(?:({user_email}[^"@]+@({domain}[^"]+))|({user}[^"]+)))"""",
    """"privilegeGranted"+\s*:\s*"+({additional_info}[^"]+)""",
  ]
  DupFields = ["domain->email_domain"]
}
```