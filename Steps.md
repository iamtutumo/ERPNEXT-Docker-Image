git clone https://github.com/frappe/frappe_docker
docker-compose -p pwd -f pwd.yml up -d


docker ps

docker logs pwd_create-site_1 -f