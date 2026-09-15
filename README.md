# Sensor Glitch Android

Android app for local, on-device broken-camera sensor style processing. No server and no WebView are required for image processing.

This repository includes the Android/Chaquopy project and a GitHub Actions workflow which builds an installable APK and publishes it as the `latest` GitHub Release asset `SensorGlitch.apk`.

## Download

After the workflow succeeds, download the APK from the repository Releases page (`latest`) or use the direct link:

https://github.com/wowowo-wo/sensor-glitch-android/releases/download/latest/SensorGlitch.apk

## Local processing

The app embeds the Python image-processing core with Chaquopy. Images are processed on the Android device using NumPy/Pillow, including selective color survival, white/highlight protection, hue preservation, manual masking, scan damage, column faults, bloom and other controls.

Build trigger initialized.
