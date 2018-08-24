# twitter-client-confserver

### Build docker
- mvn install
- docker build -t twcli-confserver-docker .
- docker run -d -p 8050:8050 {tag}
