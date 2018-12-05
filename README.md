# ddd: drupal on docker, for development

## Instructions

### 1. Create directories for local development

    mkdir shared
    mkdir shared/drupal-sites
    mkdir shared/drupal-modules
    mkdir shared/drupal-themes
    mkdir shared/drupal-profiles
    
### 2. Permissions

`sudo chown -R www-data:www-data shared`

### 2. Compose

`docker-compose stack.yml up`

### 3. Browse to localhost:8080

    Database type: PostgreSQL
    Database name: postgres
    Database username: postgres
    Database password: example
    Database host: postgres

source: [docker-compose file](https://hub.docker.com/r/_/drupal/)

e.g. stack.yml
