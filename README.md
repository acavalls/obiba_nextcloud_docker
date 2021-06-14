# oBiBa-Nextcloud docker

### Introduction

This docker-compose recipe starts Agate, Mica, Opal services that form part of the [oBiBa's software stack] (https://www.obiba.org). Also, a data storage service based on [Nextcloud] (https://nextcloud.com) is deployed. MongoDB (oBiBa) and MariaDB (Nextcloud) + configuration files are persisted by the use of docker volumes.

### Dependencies
- Docker and docker-compose

### Services
- Agate
- Mica
- Opal
- Nextcloud
- MongoDB
- MariaDB

### Usage
```
docker-compose up
```
