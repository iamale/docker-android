FROM iamale/android-base

ENTRYPOINT ["/system/bin/sh"]

# These are taken from Android-x86 running
ENV ANDROID_DATA=/data \
    LOOP_MOUNTPOINT=/mnt/obb \
    EGL_LOG_LEVEL=info \
    ANDROID_ASSETS=/system/app \
    TERM=screen \
    MKSH=/system/bin/sh \
    SYSTEMSERVERCLASSPATH=/system/framework/services.jar:/system/framework/ethernet-service.jar:/system/framework/wifi-service.jar \
    ANDROID_SOCKET_zygote=9 \
    ASEC_MOUNTPOINT=/mnt/asec \
    BOOTCLASSPATH=/system/framework/core-libart.jar:/system/framework/conscrypt.jar:/system/framework/okhttp.jar:/system/framework/core-junit.jar:/system/framework/bouncycastle.jar:/system/framework/ext.jar:/system/framework/framework.jar:/system/framework/telephony-common.jar:/system/framework/voip-common.jar:/system/framework/ims-common.jar:/system/framework/mms-common.jar:/system/framework/android.policy.jar:/system/framework/apache-xml.jar \
    SHELL=/system/bin/sh \
    ANDROID_BOOTLOGO=1 \
    USER=root \
    PATH=/system/bin:/system/xbin \
    HOSTNAME=docker \
    ANDROID_PROPERTY_WORKSPACE=8,0 \
    ANDROID_ROOT=/system \
    ANDROID_STORAGE=/storage \
    SECONDARY_STORAGE=/storage/sdcard \
    EMULATED_STORAGE_SOURCE=/mnt/shell/emulated \
    EMULATED_STORAGE_TARGET=/storage/sdcard \
    EXTERNAL_STORAGE=/storage/sdcard \
    HOME=/storage/sdcard \
    force_s3tc_enable=true
