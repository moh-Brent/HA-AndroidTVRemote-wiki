## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ |  ----  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Oct 8 2022 [V1.5.1](https://github.com/PRProd/HA-Firemote/tree/v1.5.1)         | @PRProd      |
| Author Verified    | Yes    | Oct 2 2022 [V1.4.0](https://github.com/PRProd/HA-Firemote/tree/v1.4.0)         | @PRProd      |
| Community Verified | Yes    | Oct 9 2022 [Discussion #5](https://github.com/PRProd/HA-Firemote/discussions/5#discussioncomment-3835973) | @toddsay     |

***

## Device Interrogation
| Name                       | Path              | Description                 |
| -------------------------- | ----------------- | --------------------------- |
| hdmipower                  | /dev/input/event0 |                             |
| WOBLE_INPUT_DEVICE         | /dev/input/event1 | Game Controller             |
| amazon_touch               | /dev/input/event2 | Touchscreen Controller      |
| WOW_INPUT_DEVICE           | /dev/input/event3 |                             |
| kcmouse                    | /dev/input/event4 | mouse                       |
| Amazon Fire TV Remote      | /dev/input/event5 | A physical remote control   |

***

## Misc Device Details
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstick4kmax](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-streaming-media-player.html?v=ftvstick4kmax)
 * **Build Model:** AFTKA
 * **HDMI Inputs:** No

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event5
