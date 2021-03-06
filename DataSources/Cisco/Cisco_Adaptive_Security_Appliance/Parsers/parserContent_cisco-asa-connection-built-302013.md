#### Parser Content
```Java
{
Name = cisco-asa-connection-built-302013
  Vendor = Cisco
  Product = Cisco Adaptive Security Appliance
  Lms = Direct
  DataType = "network-connection"
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Conditions = [ "%ASA-", "-302013", ": Built ", " connection "]
  Fields = [
    """({time}\w+ \d\d \d\d\d\d \d\d:\d\d:\d\d+)""",
    """(\w{3} (\d\d| \d) (\d\d\d\d )?(\d\d| \d):\d\d:\d\d)\s+({host}[\w.\-:]+?[^:])\s*:?\s*%ASA-""",
    """<\d+>({host}[\w.\-:]+?[^:])\s+%ASA-""",
    """%ASA-({priority}\d+)-({event_code}\d+)""",
    """({event_name}Built ({direction}inbound|outbound) ({protocol}TCP|UDP) connection)""",
    """\sconnection\s+({connection_id}\d+)\s+for""",
    """Built outbound.*?for\s+({dest_interface}.+?):(({dest_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({dest_host}[^\s]+?))((\/({dest_port}\d+)\s+)|\s+)\((({dest_translated_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({dest_translated_host}[^\s]+?))(\/({dest_translated_port}\d+))?\)(\(.+?\))?\s+to\s+({src_interface}.+?):(({src_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({src_host}[^\s]+?))((\/({src_port}\d+)\s+)|\s+)\((({src_translated_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({src_translated_host}[^\s]+?))(\/({src_translated_port}\d+))?\)(\s+\(({user}.+?)\))?""",
    """Built inbound.*?for\s+({src_interface}.+?):(({src_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({src_host}[^\s]+?))((\/({src_port}\d+)\s+)|\s+)\((({src_translated_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({src_translated_host}[^\s]+?))(\/({src_translated_port}\d+))?\)(\(.+?\))?\s+to\s+({dest_interface}.+?):(({dest_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({dest_host}[^\s]+?))((\/({dest_port}\d+)\s+)|\s+)\((({dest_translated_ip}(\d{1,3}\.){3}\d{1,3}|([A-Fa-f0-9%.]*:[A-Fa-f0-9%.:]+(th0)?))|({dest_translated_host}[^\s]+?))(\/({dest_translated_port}\d+))?\)(\s+\(({user}.+?)\))?"""
 ]
}
```