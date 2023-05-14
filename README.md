# docker-compose-pawtucket2
CollectiveAccess - providence + pawtucket2 docker compose ready

## About

- Contains both Providence and Pawtucket2
- Pawtucket is accessed by `http://localhost:8080/`
- Providence is accessed by `http://localhost:8080/providence`

## Image build

`docker build --tag collective-pp2:latest .`

## Usage with Docker Compose

`docker-compose up -d`

## Providence (first run)
http://localhost:8080/providence/install/

Select: ISAD(G) - General International Standard Archival Desciption

### Save pass!

In the post instalation message:

`
Installation was successful!
You can now login with username administrator and password xxxxxxx.
`