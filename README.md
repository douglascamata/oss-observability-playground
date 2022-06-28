# Thanos Docker env

## How to run it?

### With HA Prometheus and Thanos sidecars

```sh
docker compose --profile sidecar up -d
```
### With single Thanos Receive and remote write

```sh
docker compose --profile remote-write up -d
```
