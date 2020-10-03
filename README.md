# postgres_tutorial
Postgres Tutorial

## Commands:
- `docker-compose up`
- `docker cp dvdrental.tar <container id>:/dvdrental.tar`
- `docker exec -it <container id> /bin/bash`
- `pg_restore -U postgres -d dvdrental dvdrental.tar`
- `psql -U postgres`
- `\c dvdrental`
