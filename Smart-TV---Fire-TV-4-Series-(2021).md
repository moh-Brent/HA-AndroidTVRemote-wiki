## Current Support Overview
| Check              | Status | Last Update                                                                    | Related Info |
| ------------------ |  ----  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Yes    | Sept 2022 [v1.1.2](https://github.com/PRProd/HA-Firemote/releases/tag/v1.1.2)  |              |
| Author Verified    | Yes    | Sept 2022                                                                      | @PRProd      |
| Community Verified | No     |                                                                                |              |

***

## Outstanding Issues
None

***


## Device Interrogation
| Name                       | Path              | Description                 |
| -------------------------- | ----------------- | --------------------------- |
| MStar Smart TV IR Receiver | /dev/input/event0 | Physical IR remote receiver |
| MTK TV KEYPAD              | /dev/input/event1 |                             |
| amazon_touch               | /dev/input/event2 |                             |
| kcmouse                    | /dev/input/event3 | a mouse                     |
| amznkeyboard               | /dev/input/event4 | an amazon keyboard          |
| Amazon Fire TV Remote      | /dev/input/event5 | A physical remote control that appears only when a remote is currently attached/associated with this device |

***

## Misc Device Details
![Fire Smart TV 4 Series 2021](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetv/fireTV_4series.png)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=4-series](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=4-series)
 * **Build Model:** AFTTI43
 * **HDMI Inputs:** Yes. (4)

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event0
 * **DPad Center Button:** sendevent /dev/input/event0 1 28 1 && /dev/input/event0 0 0 0 && /dev/input/event0 1 28 0 && /dev/input/event0 0 0 0
 * **Fast Forward Button:** sendevent /dev/input/event0 1 159 1 && sendevent /dev/input/event0 0 0 0 && sendevent /dev/input/event0 1 159 0 && sendevent /dev/input/event0 0 0 0'
