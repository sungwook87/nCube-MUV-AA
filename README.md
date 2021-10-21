# nCube-MUV
Start Guide

* Install dependencies
```
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -

$ sudo apt-get install -y nodejs

$ node -v

$ sudo npm install -g pm2

$ git clone https://github.com/IoTKETI/nCube-MUV-AA

$ cd ~/nCube-MUV-AA

$ npm install
```

* MQTT-broker
```
$ sudo apt-get update
$ sudo apt-get install -y mosquitto
```
* How to run?
```
$ cd ~/nCube-MUV-AA
$ node thyme_tas_mav.js

# nCube-MUV-AA
