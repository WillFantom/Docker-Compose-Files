# Nextcloud

A Dropbox like cloud storage solution that can be self hosted!

## Installation

Modify the .env file:

```
BASE_DIR  <-- Where all the dirs will be created storing content such as the configs

CLOUD_DATA <-- The dir where all your uploaded data will be stored. Can be on an encrypted disk for better security

DB_HOST <-- The host of the mysql (or maria) DB, for example: localhost:3306

DB_NAME <-- The name of the db for nextcloud to use

DB_USER <-- The DB User that has permissions on the DB name above

DB_PASSWD <-- The password for the given DB user

NC_AD_USER <-- The username of the nextcloud admin account

NC_AD_PASSWD <-- The password for the nexcloud admin user

```

Then just run the following from within a terminal:

``` docker-compose up -d ```

## Traefik

👌💯 Works well with traefik
