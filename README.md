# nas-docker-compose

## usage

```bash
sudo apt-get update && sudo apt-get install docker-compose -y
docker-compose -f grafana-compose.yml -f heimdall-compose.yml -f nginx-compose.yml -f qbittorrent-compose.yml -f transmission-compose.yml up -d
```

## default auth

|item|user|password|
|---|---|---|
|qbittorrent|admin|adminadmin|
|transmission|d525|123456|
|grafana|admin|admin|

## port

|item|port|
|---|---|
|heimdall|9090|
|grafana|9091|
|nginx|9092|
|qbittorrent|9093|
|transmission|9094|