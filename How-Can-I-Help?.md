## Device Interrogation
In order to discover the best and fastest way for Home Assistant to communicate with an android device, we can send a simple adb command to the device and examine the output.

ADB command: `adb shell dumpsys input`

It is possible to execute this command through the Home Assistant UI in just a few steps:
1. Open Developer Tools
1. Click the Services Tab
1. Select "Android TV: ADB Command" service
1. Choose your device by clicking on the entity button
1. Enter `adb shell dumpsys input` into the command field
1. Click the CALL SERVICE button
1. Click over to the developer tools States tab
1. Choose your entity (the one you sent the command to)
1. Review the data to see what and how your device is listening for external input