# docker-donuts
## Build
`docker build -t kristinnb17/donuts-web .`
`docker run -d -p 9000:5000 kristinnb17/donuts-web`
### To seed the database
run `docker exec -it <docker instance name> /bin/bash`
and run command `node data/seed.js`