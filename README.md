# nmra-pfsense-snmp
Networkables Monitoring remote agent for snmp based monitoring of pfSense

Example Run:
```
docker run \
  -d --rm \
  --name nmra-pfsense-snmp \
  -e PG_ORG_NAME="YOUR_CUSTOMER_ID" \
  -e PG_ORG_TOKEN="YOUR_SECRET_TOKEN" \
  -e PG_SITE_NAME="YOUR_SITE_NAME" \
  -e PG_PFSENSE_ADDR="YOUR_PFSENSE_ADDR" \
  ghcr.io/networkables/nmra-pfsense-snmp:1.0.0
```
