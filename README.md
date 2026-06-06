## moto_camera

MotoCamera clone:
```
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotCamera2.git -b android-15 vendor/motorola/MotCamera2
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotCamera-common.git -b android-15 vendor/motorola/MotCamera-common
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_ARselfie.git -b android-15 vendor/motorola/ARselfie
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotoPhotoEditor.git -b android-15 vendor/motorola/MotoPhotoEditor
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotCamera2AI.git -b android-15 vendor/motorola/MotCamera2AI
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotCameraAI-common.git -b android-15 vendor/motorola/MotCameraAI-common
git clone https://gitlab.com/Deivid21/proprietary_vendor_motorola_MotoSignatureApp.git -b android-15 vendor/motorola/MotoSignatureApp
```

add to device.mk
```
# Moto Camera 2
TARGET_MOTCAMERA2 := whitney
TARGET_USES_MOTCAMERA2 := true

$(call inherit-product, vendor/motorola/MotCamera2/motcamera2.mk)
```
