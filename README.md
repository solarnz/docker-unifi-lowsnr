unifi-lowsnr
------------

To use, clone the repository, build and run.

```bash
docker build -t unifi-lowsnr
docker run \
    -e UNIFI_CONTROLLER=localhost \
    -e UNIFI_USERNAME=admin \
    -e UNIFI_PASSWORD=admin \
    -e UNIFI_VERSION=v3 \
    -e UNIFI_SITE=default \
    -e UNIFI_MIN_SNR=28 \
    unifi-lowsnr
```
