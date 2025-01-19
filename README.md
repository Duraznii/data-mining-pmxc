# data-mining-pmxc
Data mining from a cloud management dashboard platform of internet wireless access point devices, and its processing for the development of a Key Performance Indicator (KPI) dashboard

# Requests from Meraki's cloud:

# curl -L -H 'X-Cisco-Meraki-API-Key: <key>' -X GET -H 'Content-Type: application/json'
# 'https://api.meraki.com/api/v0/devices/[serial]/clients?timespan=86400'


# GET “http request”:

# GET /devices/[serial]/clients


# Headers:

# X-Cisco-Meraki-API-Key {{X-Cisco-Meraki-API-Key}}


# Answer example:

# Successful HTTP Status: 200
# [
# {
# "description": "Hayg's Nexus 5",
# "mdnsName": "Hayg's Nexus 5",
# "dhcpHostname": "HaygNexus5",
# "usage": {"sent": 1337.0, "recv": 7331.0},
# "mac": "00:18:D3:AD:B3:3F",
# "ip": "1.2.3.4",
# "id": "lk12uq",
# "switchport": null
# },
# ...
# ]
