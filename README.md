# proprietary_vendor_xiaomi_camera

Prebuilt stock MIUI Camera to include in custom ROM builds.

Extracted from lisa MIUI package (refer proprietary-files.txt for version).

### Supported devices
* POCO X5 Pro / Redmi Note 12 Pro Speed (redwood)

### How to use?

1. Clone this repo to `vendor/xiaomi/redwood-miuicamera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/redwood-miuicamera/device.mk)
```
