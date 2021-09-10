# Zabbix Template Palo Alto BGP

Zabbix template for discover of the BGP peers using Palo Alto API, XML and Javascript

## Features

- Using Javascript in Discovery for parsing the Peers Name
- Using XMLPath for Raw data extration
- Tested on Zabbix 5.0

  
## Optimizations

The template uses the BGP peers discovered in the LLD step and makes an API call to the Firewall, then uses dependent items and XMLPath preprocessing to extract the desired fields.
  
## Environment Variables

To run this project, you will need to add the session API Key from the Firewall.

`{$APIKEY}`


  
