## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ |  ----  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Sept 2022 [v1.1.2](https://github.com/PRProd/HA-Firemote/releases/tag/v1.1.2)  | @PRProd      |
| Author Verified    | Yes    | Nov 2022 [v1.8.7](https://github.com/PRProd/HA-Firemote/releases/tag/v1.8.7)   | @PRProd      |
| Community Verified | N/A    |                                                                                |              |

***

## Device Interrogation
| Name                       | Path              | Description                 |
| -------------------------- | ----------------- | --------------------------- |
| amazon_touch               | /dev/input/event0 | Touchscreen Controller      |
| amazon-cec                 | /dev/input/event1 | CEC Control                 |
| kcmouse                    | /dev/input/event2 | mouse                       |
| Amazon Fire TV Remote      | /dev/input/event3 | A physical remote control   |

***

## Misc Device Details
![Fire TV Stick 1st Gen](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetv/firetvstick-single._TTH_.png)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstickgen1](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstickgen1)
 * **Build Model:** AFTM
 * **HDMI Inputs:** No

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event1
