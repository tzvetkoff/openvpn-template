# OpenVPN config

OpenVPN configs, scripts, keys, etc.

## Layout

Certificates, keys, and other PKI related stuff reside inside `./easy-rsa/pki`.

Server configs are placed inside `./server`.

Client configs are generated in `./client`.

## Initial setup

``` sh
./script/init ServerName ConfigPath
```

## Adding a new client

``` sh
./script/mkclient ClientName
```

## Revoking a rogue client

``` sh
./script/rmclient ClientName
```
