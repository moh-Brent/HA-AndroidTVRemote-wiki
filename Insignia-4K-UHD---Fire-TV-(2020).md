## Current Support Overview
| Check              | Status  | Last Update                                                                    | Related Info |
| ------------------ |  ----   | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Pending |                                                                                |              |
| Author Verified    |         |                                                                                |              |
| Community Verified |         |                                                                                |              |

***

## Outstanding Issues
None

***


## Device Interrogation
Not yet completed.

***

## Misc Device Details
![Insignia 4K UHD - Fire TV (2020)](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetv/ftveditioninsignia4k_2020_thumb.jpg)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=ftveditioninsignia4k_2020](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-edition-smart-tv.html?v=ftveditioninsignia4k_2020)
 * **Build Model:** AFTDCT31
 * **HDMI Inputs:** Yes. (3)

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event0
 * **DPad Center Button:** sendevent /dev/input/event0 1 28 1 && /dev/input/event0 0 0 0 && /dev/input/event0 1 28 0 && /dev/input/event0 0 0 0
 * **Fast Forward Button:** sendevent /dev/input/event0 1 159 1 && sendevent /dev/input/event0 0 0 0 && sendevent /dev/input/event0 1 159 0 && sendevent /dev/input/event0 0 0 0'
