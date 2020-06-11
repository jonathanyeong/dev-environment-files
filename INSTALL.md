# Install

For all the dependencies you need to install:

## Postgresql

```bash
# Install docker
$ docker pull postgres
$ docker run -d -p 5432:5432 --name local-postgres -e POSTGRES_PASSWORD=localhost postgres
```
