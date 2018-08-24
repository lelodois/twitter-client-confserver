# twitter-client-confserver

### Build docker
- mvn install

- docker network create --subnet=172.18.0.0/16 twclinet123
- docker build -t twcli-confserver-docker .
- docker run --net mynet123 --ip 172.18.0.20  -d -p 8090:8090  {tag}
