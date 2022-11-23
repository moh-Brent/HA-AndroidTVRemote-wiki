## Current Support Overview
| Check              | Status        | Last Update                                                                    | Related Info |
| ------------------ |  -----------  | -----------------------------------------------------------------------------  | ------------ |
| Firemote Support   | Pending       | In progress Nov 23rd 2022                                                      |              |
| Author Verified    | No            |                                                                                |              |
| Community Verified | No            |                                                                                |              |

***

## Outstanding Issues
-none-


## Device Interrogation
| Name                       | Path               | Description                 |
| -------------------------- | ------------------ | --------------------------- |
| cec_input                  | /dev/input/event0  |                             |
| input_hdmirx               | /dev/input/event1  |                             |
| ir_keypad                  | /dev/input/event2  | IR Send                     |
| ir_keypad1                 | /dev/input/event3  | IR Receive                  |
| vad_keypad                 | /dev/input/event4  |                             |
| gpio-privacy-state         | /dev/input/event5  |                             |
| gpio-keys                  | /dev/input/event6  |                             |
| gpio-keys                  | /dev/input/event7  |                             |
| bd718xx-pwrkey             | /dev/input/event8  |                             |
| WOBLE_INPUT_DEVICE         | /dev/input/event9  |                             |
| amazon_touch               | /dev/input/event10 | Amazon Touch Device         |
| kcmouse                    | /dev/input/event11 | mouse                       |
| WOW_INPUT_DEVICE           | /dev/input/event12 |                             |
| Amazon Fire TV Remote      | /dev/input/event13 | A physical remote control that appears only when a remote is currently attached/associated with this device|

***

## Misc Device Details
![Fire TV Cube 3rd Gen 2022](https://m.media-amazon.com/images/G/01/mobile-apps/dex/firetv/cube3.png)
 * **Product Page:** [https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-cube.html?v=ftvcubegen3](https://developer.amazon.com/docs/fire-tv/device-specifications-fire-tv-cube.html?v=ftvcubegen3)
 * **Build Model:** AFTGAZL
 * **HDMI Inputs:** 1

***

## Firemote device specific settings and button overrides
 * **Default Event Setting:** event3
 * **Settings Button:** SETTINGS
 * **TV Button:** adb shell input keyevent 297
 * **App Switch Button:** adb shell input keyevent 304
 * **Power Button:** sendevent /dev/input/{event setting} 1 116 1 && sendevent /dev/input/{event setting} 0 0 0 && sendevent /dev/input/{event setting} 1 116 0 && sendevent /dev/input/{event setting} 0 0 0 && sendevent /dev/input/event2 1 9 1 && sendevent /dev/input/event2 0 0 0 && sendevent /dev/input/event2 1 9 0 && sendevent /dev/input/event2 0 0 0
   * event2 is hard coded into this custom power command since the cube has an IR blaster that also sends a power command to configured devices
 * **Switch to HDMI:** adb shell am start -n com.amazon.tv.inputpreference.service/com.amazon.tv.inputpreference.player.InputChooserActivity