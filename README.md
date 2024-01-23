# Squid
https://hub.docker.com/r/ubuntu/squid

# Docker run

docker run -d --name squid-container -e TZ=Europe/Amsterdam -p 3128:3128 ubuntu/squid:latest

# Deploy 

helm upgrade --install squid-chart ./squid-chart
