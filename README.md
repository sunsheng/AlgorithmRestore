# AlgorithmRestore

## [逆向分析某App其Frida、Xposed、Root检测及protobuf数据解析](https://blog.csdn.net/zwxlyg/article/details/122045045)

## [Android Atlas](https://cloud-atlas.readthedocs.io/zh_CN/latest/android/index.html)


Android O, failed to mount /system, /dev/block/dm-0 is read only

```
adb root
adb disable-verity
adb reboot

adb root
adb remount
adb shell

# mount -o rw,remount /system
```

open adb tcp
```
adb root
adb shell
echo "service.adb.tcp.port=5555" >> /system/build.prop
reboot
```


## [从原理到实战，全面总结 Android HTTPS 抓包](https://cloud.tencent.com/developer/article/2123803)
