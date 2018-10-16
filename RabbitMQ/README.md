# RabbitMQ with management plugin enabled initially

under the directory where Dockerfile locates, build image by running
```
docker build -t {image name} . --no-cache
```

run following command to start container
```
docker run -d --hostname {host name} --name {container name} -p 4369:4369 -p 5671:5671 -p 5672:5672 -p 15672:15672 {image name}
```
