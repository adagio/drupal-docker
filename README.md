# ddd: drupal on docker, for development

## Instructions

### 1. Directories for local development

    shared
    ├── drupal-sites
    ├── drupal-modules
    ├── drupal-themes
    └── drupal-profiles
    
### 2. Permissions

`sudo chown -R www-data:www-data shared`

### 2. Compose

`docker-compose -f stack.yml up`

### 3. Browse to localhost:8080

    http://localhost:8080

### 4. Drupal installation

Consider postgress credentials

    Database type: PostgreSQL
    Database name: postgres
    Database username: postgres
    Database password: example
    Database host: postgres

source: [docker-compose file](https://hub.docker.com/r/_/drupal/)

e.g. stack.yml
