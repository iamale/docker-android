Android in Docker
==================

First, place `data` and `system` directories from the Android-x86 installation into the `android-base` folder, then:

```
docker build -t iamale/android-base ./android-base
docker build -t iamale/android ./android
docker run -it iamale/android
```
