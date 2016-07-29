# IronFunctions using BoltDB

BoltDB is the default database, you just need to run the API.

## Persistent

To keep it persistent you add a volume flag to the command:

```
docker run --rm -it -v $PWD/bold.db:/app/bolt.db -p 8080:8080 iron/functions
```