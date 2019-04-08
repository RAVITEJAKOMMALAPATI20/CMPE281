### Lab8 commands
```
Docker command for multiple pull?

//docker exec -it <containerName> bash
docker exec -it lab8mongodb bash
mongo
show dbs
use cmpe281
db.dropDatabase()
 db.gumball.insert(
        { 
          Id: 1,
          CountGumballs: NumberInt(202),
          ModelNumber: 'M102988',
          SerialNumber: '1234998871109' 
        }
    ) ;
    db.gumball.find({Id:1});

```

### RabitMQ

```
8080:15671
https://github.com/daniftodi/rabbitmq-ssl-mng-docker

docker container run -d -p 8081:15671 --name lab8rabitmq  rabbitmq:3-management
```

### GoLang
```
https://sohlich.github.io/post/go_makefile/
```
