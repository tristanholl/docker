# Redis
This redis instance is configured to use 500mb of ram with 200 connections.

## Usage

```shell
docker run --name <app or env name>-redis -d -p 6379:6379 \
           -v /your/host/volume/path:/data {docker-image}
```
