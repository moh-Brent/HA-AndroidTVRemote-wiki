# HA-Firemote
![Fire TV 4 Series Remote](https://github.com/PRProd/HA-Firemote/blob/main/ExampleImages/fireTVRemote.png)
![Fire TV Stick 4K](https://github.com/PRProd/HA-Firemote/blob/main/ExampleImages/fireTVStick4K.png)

## Prerequisites
* A functioning version of Home Assistant
* HACS
* [Card-Mod](https://github.com/thomasloven/lovelace-card-mod) (available from HACS)
* A supported Amazon Fire Device

## How to use
1. [Turn on ADB Debugging](https://www.youtube.com/watch?v=40iVXrTWcPU) on your Amazon device
1. Set up the Android TV integration to connect it to your Amazon Device
1. Add a blank YAML card to your dashboard, and paste the contents of the *.Remote.yaml file into the card
1. Change line 3 "tv_entity:" to reflect the name of your Amazon "Android TV" device