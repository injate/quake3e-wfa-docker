Stolen from https://github.com/ra3se/q3ra3-server/tree/master

Requires docker, I recommend using the [Docker engine official install](https://docs.docker.com/engine/install/), not whatever comes from your OS packages.

2) Upload `wfa/*` folder and `pak0.pk3` to the root folder next to `compose.yaml`
3) `docker compose up -d --build --force-recreate`
4) If you change configs and files `docker compose restart`
