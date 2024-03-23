# home_server
Configuration of home-server

# BitWarden unlock

```
bw login --apikey
```

```
bw unlock
```

```
export BW_SESSION=XXXXX
```

# Base Config

```
ansible-playbook -i base_config_inventory.yml base_config.yml 
```

# Software deployment

```
ansible-playbook -i software_config_invetory.yml software_config.yml
```
