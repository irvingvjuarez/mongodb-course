# Connect to the currently service up
```sh
docker-compose exec [service_name] bash
```

# Connect with mongosh
```sh
mongosh [connection_string]

show dbs
show collections

use([database_name])
db.[collection_name].find()
```

