# HL_LABS
High Load System Labs
## Team Members
- Єфанов Ілля
- Різун Володимир
- Швець Віталій

## Lab 1 (Docker)
### Task 1
- `docker pull hello-world`
- create docker-compose.yaml
- `docker compose up`

### Task 2
- `docker pull node`
- create docker-compose.yaml
- create index.html
- create start.sh to run node server
- `docker compose up`

### Task 3
- `docker pull node`
- create docker-compose.yaml
- create db.json
- create start.sh to run json-server
- `docker compose up`

### Task 4
- `docker pull nginx`
- create docker-compose.yaml
- create folders: json_server, lite_server, nginx
- create json_server/db.json, json_server/start.sh
- create lite_server/index.html, lite_server/start.sh
- create nginx/nginx.conf
- `docker-compose up --scale lite-server=3 --scale json-server=3`

### Task 5
- create postman collection
- test collection
- save collection as json
- save results as json