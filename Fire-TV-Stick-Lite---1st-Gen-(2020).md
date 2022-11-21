## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ |  ----  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Sep 3 2022 [V1.2.0](https://github.com/PRProd/HA-Firemote/tree/v1.2.0)         | @PRProd      |
| Author Verified    | Yes    | Sep 3 2022 [V1.2.0](https://github.com/PRProd/HA-Firemote/tree/v1.2.0)         | @PRProd      |
| Community Verified | N/A    |                                                                                |              |

***

## Device Interrogation
| Name                       | Path              | Description                 |
| -------------------------- | ----------------- | --------------------------- |
| hdmipower                  | /dev/input/event0 |                             |
| WOBLE_INPUT_DEVICE         | /dev/input/event1 | Game Controller             |
| amazon_touch               | /dev/input/event2 | Touchscreen Controller      |
| kcmouse                    | /dev/input/event3 | mouse                       |
| Amazon Fire TV Remote      | /dev/input/event4 | A physical remote control   |

***

## Misc Device Details
![Fire TV Stick Lite 1st Gen 2020](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetvsticklitethumb.jpg)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvsticklite](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvsticklite)
 * **Build Model:** AFTSS
 * **HDMI Inputs:** No

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event4
