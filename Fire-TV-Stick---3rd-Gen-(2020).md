## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ |  ----  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Nov 20 2022 [V1.8.6](https://github.com/PRProd/HA-Firemote/tree/v1.8.6)        | @PRProd      |
| Author Verified    | Yes    | Nov 20 2022 [V1.8.6](https://github.com/PRProd/HA-Firemote/tree/v1.8.6)        | @PRProd      |
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
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstickgen3](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstickgen3)
 * **Build Model:** AFTSSS
 * **HDMI Inputs:** No

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event4
 * **Power:** media_player.turn_on or media_player.turn_off depending on power state

