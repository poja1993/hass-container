# hass-container
Repo containing setup files for Home Assistant running as container on a Raspberry Pi.  
See [here](https://www.home-assistant.io/installation/raspberrypi#docker-compose) for more info  

## Installation:
* Clone Repo
* cd < repo >
* docker-compose up -d

## Upgrade Home Assistant
[Here](https://github.com/poja1993/scripts/blob/master/update_hass-docker.sh) there is a script that is taking care of:  
- Backup of the container
- Backup of the config files
- Upgrade Home Assistant
- Restart Home Assistant
