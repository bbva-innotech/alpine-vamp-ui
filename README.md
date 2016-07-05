alpine-vamp-ui
==============

This image is the alpine-vamp-ui base. It comes from [alpine-nginx][alpine-nginx].

## Build

```
docker build -t rawmind/alpine-vamp-ui:<version> .
```

## Versions

- `0.8.4-7` [(Dockerfile)](https://github.com/bbva-innotech/alpine-vamp-ui/blob/0.8.4-7/Dockerfile)

## Configuration

This image runs [vamp-ui][vamp-ui] with monit. It is started with vamp user/group and 10006 uid/gid.

The service is started with monit. It's listening at port 8080.

[alpine-nginx]: https://github.com/rawmind0/alpine-nginx/
[vamp-ui]: https://github.com/magneticio/vamp-ui/