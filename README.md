# V0Build

<pre>
This is a place holder Repo for my Voron 0.2 Build.

Tools Used:
Fabreeko Hex Screw set: https://www.fabreeko.com/products/fabreeko-precision-screw-driver-set-of-5?variant=38183379828934
Wera Hex Ballhead Screw: https://www.amazon.com/dp/B000WL8UV8?ref=ppx_yo2ov_dt_b_product_details&th=1
Allen Key : https://www.amazon.com/dp/B009ODV0OE?ref=ppx_yo2ov_dt_b_product_details&th=1
TS101: https://www.amazon.com/dp/B0BL2LN7K2?ref=ppx_yo2ov_dt_b_product_details&th=1
ES15: https://www.amazon.com/dp/B09MVM9PTW?psc=1&ref=ppx_yo2ov_dt_b_product_details
Label Maker PTE500 with Heat shrink tape : https://www.amazon.com/dp/B00KHVE28S?psc=1&ref=ppx_yo2ov_dt_b_product_details & https://www.amazon.com/dp/B08XW7JHW9?ref=ppx_yo2ov_dt_b_product_details&th=1


Organizer: 
https://www.printables.com/model/171383-less-thin-hexagon-parts-tray/files

Mods:
https://github.com/MotorDynamicsLab/LDOVoron0
https://github.com/christophmuellerorg/voron_0_kirigami_bed
https://github.com/VoronDesign/Voron-Hardware/tree/master/V0-Umbilical
https://github.com/chirpy2605/voron/tree/main/V0/XCarriage_v0_2
https://github.com/zruncho3d/zerofilter
https://www.printables.com/model/496209-manta-5p-mount-for-voron0x

Day 1: Page 0-66 Build Time : 4hours

Board Prep:
  Shorting Pin for UART
  Shorting pin for Sensorless Homing XandY
  Shorting pin for fans to use 24v
  https://bigtreetech.github.io/docs/M5P.html#hardware-installation
  https://bigtreetech.github.io/docs/Software%20Installation.html
  CB1 Source: https://github.com/bigtreetech/CB1

  after RPi Imager:
  edit system.cfg with updated wifi password

  CB1 Troubleshooting
  https://bigtreetech.github.io/docs/Software%20Configuration.html?h=dfu#update-using-dfu
  
  check if CB1 MCU is detected
  ls /dev/serial/by-id/
  
  manual update
    cd /klipper
    make clean
    make menuconfig
    make
    output will be in /home/biqu/klipper/out/klipper.bin
    copy file to pc. and rename to firmware.bin put in SD CARD slot on back

  Sensorless homing: 
  https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html
  
</pre>
