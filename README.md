- HERE IS MY RECENT PROJECT

## DOCKERISING A WORDPRESS APP
- Two containers are needed here
   - mysql container
   - wordpress host
- BOTH CONTAINERS ARE STARTED USING DOCKER COMPOSE

 ### DOCKER-COMPOSE.YAML FILE
  - mysql was used for the database
      - mysql image pulled from dockerhub
        

- wordpress host running on docker
   - wordpress:latest pulled from docker hub
   - connected to the db
     
 
- docker volume for data persistency in any case the containers are restarted
  

- both containers are started by running the docker-compose.yaml file
   - docker-compose -f docker-compose.yaml up
 
   - check localhost:8000 on local
      - To sign in and configure Wordpress.
    
   ![wordpress](https://github.com/user-attachments/assets/e5769a7b-0b65-4cfe-b4f3-6e84fdd28bd9)


