# nas-docker-compose

## usage

```bash
sudo apt-get update && sudo apt-get install docker-compose -y
docker-compose -f grafana-compose.yml -f heimdall-compose.yml -f nginx-compose.yml -f qbittorrent-compose.yml -f transmission-compose.yml up -d
```

### grafana config
    grafana datasource: http://prometheus:9090
    dashboard id: 1860 13978
### qbittorrent config
    old config path: 
        ~/.config
        ~/.local/share

## default auth

|item|user|password|
|---|---|---|
|qbittorrent|admin|adminadmin|
|transmission|admin|123456|
|grafana|admin|admin|

## ports

|item|port|
|---|---|
|heimdall|11100|
|grafana|11101|
|nginx|11102|
|qbittorrent|11103|
|transmission|11104|