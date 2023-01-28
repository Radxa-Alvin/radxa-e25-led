# radxa-e25-led


### Run mode：
* colorful
* rgb_breathe
* blink

### How to change the mode


modify radxa-e25-led.sh:

`rock@radxa-e25:~$ sudo vim /usr/local/bin/radxa-e25-led.sh`

`rgb_mode=colorful`

modify rgb_mode: 
> colorful  &ensp; rgb_breath &ensp; blink


### How to use

`sudo systemctl stop radxa-e25-led.service`

`sudo systemctl start radxa-e25-led.service`

`sudo systemctl status radxa-e25-led.service`
