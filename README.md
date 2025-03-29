# Meshtastic

Фърмуер на Мештастик за лабърските модули - ttgo lora32 v1


1. Ползвайте скрипта за флашване. Той ползва esptool, така че ще трябва и него да имате.

```
./device-install.sh -p /dev/cu.usbserial-0001 -f firmware-tlora-v1-2.5.4.8d288d5.bin
```

След инсталиране, може да се види дебъг съобщенията в uart-а на скорост 115200


2. Инсталирайте Meштастик приложението на телефона си за [Android](https://meshtastic.org/docs/software/android/installation/), [iPhone](https://meshtastic.org/docs/software/apple/installation/) или през [браузъра](https://client.meshtastic.org)
