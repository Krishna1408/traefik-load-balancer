# Flaconi DevOPS Challange
A demo showing traefik as load-balancer for a multi tier application

1. To run the stack run:

`docker-compose up --scale fe=2 --scale be=3`

2. To get the info from application run:

`curl -H Host:front-end.com localhost`

## Possible other solutions

Ha-proxy or nginx can also be used as loadbalancer/reverse proxy instead of traefik.  
