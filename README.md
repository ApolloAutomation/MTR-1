# Apollo Multi-target Motion Multisensor (MTR-1)



This sensor offers a wide range of functionality for Home Assistant in a very tiny package.

YAML Files:
- MTR-1.yaml: This file is a minimal config. It doesn't have the bluetooth or OTA components. Use this if you are looking to add BLE proxy or BLE tracking.
- MTR-1_BLE.yaml: This file contains BLE proxy code. We use it as an automated test during our build process. But can be an example for adding BLE proxy to your device.
- MTR-1_Factory.yaml: This is the firmware flashed by us on new devices. It contains the components for ESP improve, allowing easy adoption in Home Assistant. When you load the device in ESPHome addon, it will grab the firmware from MTR-1.yaml which no longer has the improve.


Links: \
Discord (Support/feedback/discussion/future products): [https://discord.gg/8PpS4yUaUh](https://discord.gg/mMNgQPyF94) \
Shop: [https://apolloautomation.com](https://apolloautomation.com) \
Wiki: [https://wiki.apolloautomation.com](https://wiki.apolloautomation.com/) \
3D Files: [https://www.printables.com/model/932043-apollo-automation-mtr-1-multi-target-radar-multise](https://www.printables.com/model/932043-apollo-automation-mtr-1-multi-target-radar-multise)
