# Project Setup
  - git clone https://github.com/Av3001/Redis-client-Nodejs
  - cd src
  - tsc -b
### Spinup docker daemon & run the following commands)
  - docker pull redis
  - docker run -p 6379:6379 redis
### Copy container_id 
  - docker ps
  - docker exec -it container_id /bin/bash
  - then write *redis-cli* 
### To check docker redis container or not 
  - Set user_data avneet
  - Get user_data
### Now run the following command
 - npm run start

### check the endpoints via postman




