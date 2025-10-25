# qbittorrent-docker

[qBittorent](https://qbittorent.org) docker compose with gluetun VPN.

## .env example

```bash
GLUETUN_VERSION='3.40.0'
QBITTORRENT_VERSION='5.1.2'
SERVER_COUNTRIES='Denmark,Germany'
TZ='Europe/Copenhagen'
VPN_PORT_FORWARDING='on'
VPN_SERVICE_PROVIDER='protonvpn'
VPN_TYPE='wireguard'
WIREGUARD_PRIVATE_KEY='key
```
