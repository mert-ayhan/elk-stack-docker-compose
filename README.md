# elk

## Build
To build & start system, run this command.
```
docker-compose up --build -d
```

## Delete
This command is to simple clear everything do:
```
docker system prune --all
```

## Logs
To see logs, use this command.
```
docker logs --tail [line_length] [container_name]
```

## Check ElasticSearch is Running
Run this command to check elasticsearch is running
```
curl -X GET localhost:9200
```
