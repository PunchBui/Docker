# A minimal configuration to set up a docker with Ubuntu 16.04 + SSH access + LAMP
### How to Use:
1. Modify `Dockerfile` to set up password for SSH
2. Execute: `docker-compose up -d` (remove `-d` for foreground mode, If you want to build --build)
3. URL : http://DOCKER_IP:2080
4. Log into server: `ssh root@localhost -p 2022`  (Default Password is : 1234)
5. Set up root password for mysql: `mysqladmin -u root password '<NEW_PASSWORD>'`
