# What is this?

A collection of Docker Compose files that help me test/debug some scenarios.

## What and where?

### prometheus_snapshot_reader

Small Prometheus & Grafana setup for reading TSDB snapshots.

Supports Grafana dashboard & datasource provisioning.

### thanos

Small Thanos setup with two flavors: sidecar and receive. Pick between by
layering config files (passing many instances of `-f config.yaml` to `docker compose`)