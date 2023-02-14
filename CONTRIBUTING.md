# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:omec-5g-nrf_1.0.1_amd64.rock docker-daemon:omec-5g-nrf:1.0.1
docker run omec-5g-nrf:1.0.1
```
