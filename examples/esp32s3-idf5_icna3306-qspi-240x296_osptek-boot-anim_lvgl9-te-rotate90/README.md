# 固件并包bin文件

```
/home/jin/.espressif/tools/python/v6.1/venv/bin/python -m esptool --chip esp32p4 merge-bin \
  --output esp32s3-idf5_icna3306-qspi-240x296_osptek-boot-anim_lvgl9-te-rotate90_0x0.bin \
  --flash-mode dio \
  --flash-freq 80m \
  --flash-size 16MB \
  0x0 bootloader/bootloader.bin \
  0x8000 partition_table/partition-table.bin \
  0x10000 esp32s3-idf5_icna3306-qspi-240x296_osptek-boot-anim_lvgl9-te-rotate90.bin \
  0x610000 mmap_build/assets/efc/efc.bin
```
