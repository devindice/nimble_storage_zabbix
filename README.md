This is a basic template to monitor a nimble datastore with zabbix (in this cas the model is AF40). It was created using [SNMPWALK2ZABBIX](https://github.com/Sean-Bradley/SNMPWALK2ZABBIX) with some minor modifications.
From the original output there has been some improvements:
- Enable interesting metrics by default
- Adding interface number to the item name
- Converting units to proper values (I need only the lower order bytes in my case)
- Create graphs to show the used space over time