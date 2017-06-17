## This doument contains information about different aspects of Trifacta configuration.

### 1. To create hive connection through CLI:
```bash
./trifacta_cli.py edit_connection --user_name admin@trifacta.local --password adminPassword --conn_name aHiveConnection --conn_description "Global Hive connection." --conn_host hostFQDN --conn_port 10000 --conn_credential_type trifacta_service --conn_params_location ./parameter.json --conn_is_global --cli_output_path ./conn_create.out
```

### 2. TO edit hive connection through CLI:
```
./trifacta_cli.py create_connection --user_name serviceAccount@DOMAIN --password securePassword --conn_name aHiveConnection --conn_description "Global Hive connection." --conn_host hostFQDN --conn_port 10000 --conn_credential_type trifacta_service --conn_params_location ./parameter.json --conn_is_global --cli_output_path ./conn_create.out