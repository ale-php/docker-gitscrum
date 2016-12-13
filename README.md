# Docker-GitScrum
Docker containers for Laravel GitScrum

# How to install Docker Compose
curl -L https://github.com/docker/compose/releases/download/1.9.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose

# Build Containers
You can run the command on your bash to build the containers

```
cd docker-gitscrum
cd gitscrum
git clone https://github.com/renatomarinho/laravel-gitscrum.git
cp -R laravel-gitscrum/* webapp/
rm -rf laravel-gitscrum
docker-compose up --build
```

