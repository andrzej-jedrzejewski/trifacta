## This doument contains information about different aspects of Trifacta configuration.

### 1. To create hive connection through CLI:
```bash
./trifacta_cli.py edit_connection --user_name admin@trifacta.local --password admin --conn_name aHiveConnection --conn_description "Global Hive connection." --conn_host LSGNPDHMN01.nonprod.local --conn_port 10000 --conn_credential_type trifacta_service --conn_params_location ./parameter.json --conn_is_global --cli_output_path ./conn_create.out
```