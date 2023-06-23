# Expresslrs_3.2_HT-CT62_sx1262

Using Elrs configurator choose local folder with downloaded erls and choose DIY 900 MHz device group and device  DIY 900 RX PWMP
change needed parameters - freq, pass, wifi and etc..

![image](https://github.com/Sekilsgs2/Expresslrs_3.2_HT-CT62_sx1262/assets/5908468/1479f8b6-9ce8-4ae0-a430-eb34c6f3d2af)

Next build and flash firmware.

HT-CT62 connection diagramm for first flashing (use usb to uart converter 3.3v) - 

![image](https://github.com/Sekilsgs2/Expresslrs_3.2_HT-CT62_sx1262/assets/5908468/32e7d3f5-d1f1-4a7b-8f6b-0575835a1c9f)

After flashing - disconnect gnd from gpio 9 - and can using module as erls rx. 200ghz and 100hz 8ch - not working with sx127x modules because not compatible at SF6.
Working 100hz, 50hz, 25hz hybrid switches...

After first flashing - can using wifi for next flashing methods..


