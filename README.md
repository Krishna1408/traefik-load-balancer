# traefik-load-balancer

## Docker Challange
A demo showing traefik as load-balancer for a multi tier application

1. To run the stack run:

`docker-compose up --scale fe=2 --scale be=3`

2. To get the info from application run:

`curl -H Host:front-end.com localhost`

#### Possible other solutions

Ha-proxy or nginx can also be used as loadbalancer/reverse proxy instead of traefik.  

## Cloudformation Challange to Create VPC:

As per my last interview, I understand that terraform is also used in your team. Please check below for creation VPC using terraform:


Main repo: https://github.com/Krishna1408/apache-tomcat-automation

Code to Create VPC: https://github.com/Krishna1408/apache-tomcat-automation/blob/master/1-%20Create%20VPC/create_vpc.tf
