## Quick NodeJS API with built-in mysql image

![NodeJS](https://img.shields.io/badge/NodeJS-100%25-5FA04E?logo=nodedotjs)
![Sequelize](https://img.shields.io/badge/Sequelize-MySQL-blue?logo=sequelize)
![MySQL](https://img.shields.io/badge/MySQL-MariaDB-lightblue?logo=mysql)

***

### easy to install restful api with members and users.

You can create an .env file if you prefer then run (leave empty for testing) :

```
docker-compose up -e MARIADB_ALLOW_EMPTY_ROOT_PASSWORD=1 -e MARIADB_DATABASE=default_db -d
```

### Possible Env variables :


> Default credentials are root | null | default_db | 127.0.0.1

MARIADB_USER | MARIADB_ROOT_PASSWORD | MARIADB_DATABASE | MARIADB_HOST
:---------------:|:---------------:|:---------------:|:---------------:|


