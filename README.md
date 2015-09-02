# Eazeup Infrastructure
### Contains
- Loadbalancing
- Rabbitmq + clustering

### Requirements
- [docker](https://docs.docker.com/installation/)
- [docker-compose](https://docs.docker.com/compose/)
- [docker toolbox](https://www.docker.com/toolbox) (Highly recommended for debugging)

### Use

- `docker-compose up -d` -  builds and runs all containers in background
  - cluster listens to port ***5671***
  - admin panel listens to port ***15672***
- `docker-compose stop` - stops containers

