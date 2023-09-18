# Connect to container
```sh
docker-compose exec mongodb bash
```

# Connect wuth mongosh
```sh
mongosh "mongodb://epdev:EPmongodb47@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

# Some commands
```sh
use("platzi_store")
show dbs
show collections
use("db_name")
db.collection_name.find()
```

