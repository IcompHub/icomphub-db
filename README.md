# icomphub-db

This project goal is to easily update server db docker container by github actions, and also to start a local db for local api tests

## How to run

Run `docker compose up -d` on the terminal, it will start a new container with this configs:

- USER: `icomphub`
- PASSWORD: `development0nly`
- POST: `5416`
- VOLUME: `./psql`

You can also start pgadmin, junt uncomment the service at `./compose.yaml`
