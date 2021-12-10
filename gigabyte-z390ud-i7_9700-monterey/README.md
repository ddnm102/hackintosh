# Monterey Hackintosh Gigabyte Z390UD I7 9700

EFI for Hackintosh with Gigabyte Z390 UD, Intel I7 9700

Opencore version: 0.7.4

<strong>
[Update 02/12/2021]<br/>
  After using some months, my wifi card BCM4331 does not work properly, it off and can't enable after sleep, event after restart computer. <br/>
  Turn off computer for some hours, it work again, and then repeat error. Finding information and found: https://github.com/khronokernel/IO80211-Patches<br/>
  After add id/vender to DeviceProperties and the wifi card work again! Thanks so much to khronokernel!!
</strong>


<hr/>
Remember generate new MLB, SystemSerialNumber, SystemUUID

# Images:
![Screen Shot 1](https://user-images.githubusercontent.com/65882641/139067411-c7304df5-9dc8-4ee7-a39b-dd9d48f183a1.png)
![Screen Shot 2](https://user-images.githubusercontent.com/65882641/139067440-0e80542b-a8bc-4f8c-a91f-728f078de536.png)

# Hardwares:
  - Main: Gigabyte Z390 UD
  - Chip: Intel I7 9700
  - Ram: 16x2 GB Corsair
  - GPU: Radeon RX 570 4GB
  - SSD: 500GB Samsung 970 Evo Plus NVME
# Bios settings:
  - Firmware Version F10K
  - Load all setting to default.
  - Disabled: Vt-d, CMS, CFG Lock, PPT, Trusted computer, Network stack, Serial port, 
  - My Settings Images:
      ![bios_info](https://user-images.githubusercontent.com/65882641/139070218-24ff63e2-434c-4c50-bbed-d548816a8782.JPG)
      ![ram status](https://user-images.githubusercontent.com/65882641/139070242-903b2512-f586-4f54-bfe7-5c7d8fc94803.JPG)
      ![power_info](https://user-images.githubusercontent.com/65882641/139070289-fe40bd60-32da-4468-a1e7-e767d7d4d260.JPG)
      ![vt-d](https://user-images.githubusercontent.com/65882641/139070302-0d236063-a1a6-41a7-a94d-e9d3e8080279.JPG)
      ![basic_settings](https://user-images.githubusercontent.com/65882641/139070314-61068195-b87f-43c9-b530-9d961685df48.JPG)
      ![serial_info](https://user-images.githubusercontent.com/65882641/139070329-95bf5fc7-f480-4d5d-ae63-32f4f8581f50.JPG)
      ![usb_info](https://user-images.githubusercontent.com/65882641/139070365-19f3acdd-2602-4638-8b56-747022374945.JPG)
      ![network_info](https://user-images.githubusercontent.com/65882641/139070391-9ec1e0e0-7262-4e7c-a120-ddf06eea3d33.JPG)
      ![sata_info](https://user-images.githubusercontent.com/65882641/139070399-9a20dc79-2c76-41c7-9c25-af0c31552ecd.JPG)
      ![B3E50D3B-CEFA-4611-B994-9D56A0DE1303](https://user-images.githubusercontent.com/65882641/139070431-9e36dc63-28df-4dd8-9d91-cf7da3197f00.JPG)
      ![trust_computer](https://user-images.githubusercontent.com/65882641/139070439-d4538c05-dbc2-49f0-a2f4-d950d3e063da.JPG)
      ![boot_info](https://user-images.githubusercontent.com/65882641/139070456-434a0f24-d3d1-460b-9a9c-5e1eb30c4f48.JPG)

# Working: all ok
  - wifi, bluetooth, airdrop
  - shutdown, restart, sleep
# Not working:
  - not found yet
# All other task pls refer to Opencore Guidle, Here, i just update the EFI folder, everyone can use it with your own risk  
  [opencore link](https://dortania.github.io/OpenCore-Install-Guide/extras/monterey.html)
