# local-social-deploy

# Repository to for Deployment files for the localSocial app
# NOTE: to fetch images a ~/data/images folder needs to be created

# Before running create a volume
$ docker volume create mongodbdata

# To deploy run
$ docker stack deploy --compose-file docker-compose.yml localSocial

# local-social-ui can be accessed at http://localhost:3001

# local-social-api can be accessed at http://localhost:3002

# images can be fetched from urls starting with http://localhost:8080/images/
# example http://localhost:8080/images/album/picture.JPG

