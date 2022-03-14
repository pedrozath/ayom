# AYOM Infrastructure

This is the infrastructure of AYOM: The free podcast platform.

As of now we are hosted in AWS ECS. This is done via Docker Compose through the
ECS context:

```
docker context create ecs ayom
docker context use ayom
docker compose up
```

## See also

* [AYOM API](github.com/pedrozath/ayom-api) — The back-end API of AYOM
* [AYOM UI](github.com/pedrozath/ayom-ui) — The web front-end interface of AYOM
