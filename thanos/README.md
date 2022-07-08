# How to use?

## Running with Thanos Sidecars

1. Configure the different Prometheus instances `prometheus0.yaml` and
   `prometheus1.yaml` in the `prometheus` folder if need/want to.
2. Run `docker compose up -f compose.yaml -f sidecar.yaml -d`

## Setup with Thanos Receive

1. Configure the Prometheus instance `prometheus_remote_write.yaml` and in the
   `prometheus` folder if need/want to.
2. Run `docker compose up -f compose.yaml -f receive.yaml -d`