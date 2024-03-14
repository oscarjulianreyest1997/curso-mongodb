# Connect to container
```sh
docker-compose exec mongodb bash
```

# Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://oscaradmin:0000@mongodb1997.wuvmlqz.mongodb.net/"
```

# instructions
```sh
show dbs
show collections
```

```sh
use("store")
db.products.find()
```