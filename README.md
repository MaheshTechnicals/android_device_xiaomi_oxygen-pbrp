# Device Tree for Xiaomi MAX 2 (Oxygen)

## Spec Sheet

| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Octa-core 2.0 GHz Cortex-A53      |
| Chipset                 | Qualcomm MSM8953 Snapdragon 625   |
| GPU                     | Adreno 506                        |
| Memory                  | 4 GB                              |
| Shipped Android Version | 7.1.1                             |
| Storage                 | 64/128 GB                         |
| MicroSD                 | Up to 256 GB                      |
| Battery                 | 5300 mAh (non-removable)          |
| Dimensions              | 88.7 x 174.1 x 7.6 mm             |
| Display                 | 1920x1080 pixels, 6.44 (~342 PPI) |
| Rear Camera             | 13 MP, Dual LED flash             |
| Front Camera            | 5 MP                              |
| Release Date            | May 2017                          |

## Device picture
![Mi MAX 2](http://i01.appmifile.com/webfile/globalimg/29/B8388A52-854A-94A5-D386-7F675F467FE1.jpg "Mi MAX 2")

This branch is for building OrangeFox.

### To build: 
```
repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

repo sync

. build/envsetup.sh

lunch omni_oxygen-userdebug

make clean && make recoveryimage
```
