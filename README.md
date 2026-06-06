## moto_camera

add to device.mk
```
# Moto Camera 2
TARGET_MOTCAMERA2 := whitney
TARGET_USES_MOTCAMERA2 := true

$(call inherit-product, vendor/motorola/MotCamera2/motcamera2.mk)
```
