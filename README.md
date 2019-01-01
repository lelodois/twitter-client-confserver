# twitter-client-confserver

### Build docker
- mvn install

- docker network create --subnet=172.18.0.0/16 twclientnet
- docker build -t twcli-config-server .
- docker run --net twclientnet --ip 172.18.0.20  -d -p 8090:8090  {tag}
