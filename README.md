# twitter-client-confserver

### Build docker
- mvn install

- docker network create --subnet=172.18.0.0/16 mynet123
- docker run --net mynet123 --ip 172.18.0.20  -d -P -p 8090:8090  61f1fed290c0
- docker build -t twcli-configserver .
- docker run -p 8050:8050 {tag}
