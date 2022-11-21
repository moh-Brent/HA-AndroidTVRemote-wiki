## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ | ------ | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Nov 16 2022 [v1.8.0](https://github.com/PRProd/HA-Firemote/tree/v1.8.0)        |              |
| Author Verified    | No     |                                                                                |              |
| Community Verified | Yes    | [https://community.home-assistant.io/t/lovelace-firemote-card-remote-controls-for-amazon-fire-android-devices/471038/4](https://community.home-assistant.io/t/lovelace-firemote-card-remote-controls-for-amazon-fire-android-devices/471038/4)                                                                                                     | [@ShooterQ](https://community.home-assistant.io/u/ShooterQ) |

***

## Outstanding Issues
None

***

## Device Interrogation
Not Preformed / Unavailable.

Do you own this device? We'd love your help filling this information gap!  [Click here to contribute.](https://github.com/PRProd/HA-Firemote/wiki/How-Can-I-Help%3F#device-interrogation)

***

## Misc Device Details
![Smart TV - Toshiba V35 Series 2021](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetv/ftvedition_toshibav35.jpg)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=ftvedition_toshibav35](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=ftvedition_toshibav35)
 * **Build Model:** AFTHA002
 * **HDMI Inputs:** No

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event0
 * **Other Working Event Settings:** Strong, event4 [@ShooterQ - Community Post Oct 2022](https://community.home-assistant.io/t/lovelace-firemote-card-remote-controls-for-amazon-fire-android-devices/471038/4)
 * **DPad Center Button:** sendevent /dev/input/event0 1 28 1 && /dev/input/event0 0 0 0 && /dev/input/event0 1 28 0 && /dev/input/event0 0 0 0
 * **Fast Forward Button:** sendevent /dev/input/event0 1 159 1 && sendevent /dev/input/event0 0 0 0 && sendevent /dev/input/event0 1 159 0 && sendevent /dev/input/event0 0 0 0
