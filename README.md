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
# "description": "Description's Nexus 5",
# "mdnsName": "Name's Nexus 5",
# "dhcpHostname": "NameNexus5",
# "usage": {"sent": 0000.0, "recv": 0000.0},
# "mac": "00:00:X0:YY:Z0:W0",
# "ip": "1.2.3.4",
# "id": "xx12yy",
# "switchport": null
# },
# ...
# ]
