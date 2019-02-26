# Support an Orphan (SAO)

## Introduction

The system is build using [Wordpress](https://wordpress.com/) CMS.

### Development

#### Setup in Docker

[Docker](https://www.docker.com/) Docker is a platform for developers and sysadmins to develop, deploy, and run applications with containers. The use of Linux containers to deploy applications is called containerization.

##### Install docker

Go here [link](https://docs.docker.com/install/).

Download and install docker communitiy version for your OS (Windows/MAC/Linux)


##### Run Docker

Run following command in command line in the root folder of the project where the "docker-compose.yml" file is located.
```sh
docker-compose up -d
```

Run following docker command to see the running containers.

```sh
docker ps
```

#### Browse localhost
If all goes well, open the [http://localhost:8000](http://localhost:8000)

That's it. So quick and easy.

#### Changing source code.

All source code are available under **src** folder