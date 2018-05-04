
#Cisco IOS EEM Scripts

```Cisco_IE_physical_contact_SNMP_TRAP.txt```

This EEM Script was used to work around a limitation of an SNMP server.  the
Server would not read SNMP trap messages because they ended with an incrementing
index number.  To work around this the same OUI numbers where used to indicate
the same information but in a format the server would read.

This specific instance is the wired pin inputs on an IE-2000 series industrial
ethernet switch.
