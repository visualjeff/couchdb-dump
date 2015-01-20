Couchdb-dump (& restore) for haraka-couchdb
===================================================

##Quickstart (& quickend)
```bash
./export.sh <TARGET_HOST> <COUCHDB_PORT>

./import.sh <TARGET_HOST> <COUCHDB_PORT>
```

Data is exported to json in a ./data directory.

NOTE: Tested with couchdb 1.6.1


addDesignDocument.sh is a script for add the mailBoxes.json design document to each database.
./addDesignDocument.sh http://haraka-couchdb.cloudapp.net 5984
