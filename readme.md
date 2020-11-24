# Getting Started

First create a password in `factorio/config/rconpw`

Add any aditional mods into the mods directory

put your save into `factorio/saves/_autosave1.zip`

make everything the correct user/group 

```
sudo chown -R 845:845 factorio data/prometheus
sudo chown -R 472:472 data/grafana
```

run everything `docker-compose up`