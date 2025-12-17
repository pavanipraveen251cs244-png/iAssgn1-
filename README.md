# iAssgn1-
 cd assignment2

  docker network create webnet
  docker run -d --name web -p 8080:80 --network webnet nginx
  #creating nginx container
   docker run -d --name api --network webnet hashicorp/http-echo -text="Hello from API"
   mkdir files
    cd files
    code nginx.conf
    code index.html
  #making and coding nginx config and front end so that changes can be made in nginx conf
   http://api:5678
   
