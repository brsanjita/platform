##Requirements 
- Golang >= 1.12
- MongoDB >= 4.0 as data store.
- redis as a cache store.
- Vue.js (for front-end development)

## Source code
- Fork and Clone the source code from the respective repo from ( https://github.com/tribehq)

### Cloning 
- clone it from the forked repo by doing the following  :
- copy the SSH key or URL from the forked repo.
- in cmd -> git clone <the copied 
ssh key or url>
- Source code has been cloned successfully.

### IDE process
- edit the run/Debug configuration dialog to 
-- Run GQLgen (to run the GraphQL schema) 

similarly 
-- Run Graphserver (to run the Graph Server) 

- In the terminal - redis-server (to run the cache server)

### Tribe graphQL Playground : https://dev.graph.tribe.cab
- use the URL- localhost:8080 to access it.

### Setup .env 
- set the parameters like MONGODB_URL, MONGODB_DATABASE, hostname etc using .env.example file in platorm repo. 

### MongoDB
- In MongoDB compass set the respective fields like hostname , port (default: 27017) according to the .env file.

 


