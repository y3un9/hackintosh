# Hackintosh

https://dortania.github.io/OpenCore-Install-Guide/


- [PC](./pc/EFI/)

AMD -> Mac Pro 2019

Type:         MacPro7,1
Serial:       F5KF6DYMP7QM
Board Serial: F5K105301QXK3F71H
SmUUID:       0522BA6F-D2B4-45AD-9E78-456B910606A6
Apple ROM:    B8098A511166

|     Specs      |                          Value                          |
|:--------------:|:-------------------------------------------------------:|
|      CPU       |                    AMD Ryzen 5 3600                     |
|      iGPU      |                            -                            |
|      eGPU      | 肥猫家 AMD RX580 8GB 2048sp <br> (sockpuppet for RX570) |
|  Motherboard   |                  MSI B450M Mortax Max                   |
| WiFi&Bluetooth |                [Fenvi T919 (BCM94360CD)]                |


- [Laptop HP](./laptop/EFI/)

HP 15-r239TX -> MacBook Pro 2015

Type:         MacBookPro11,4
Serial:       C02QFMY3G8WN
Board Serial: C025385014NGDQP1H
SmUUID:       2FCA580A-9518-467F-9EDB-0CE83B8DD99B
Apple ROM:    0010FACA2E5C

|   Specs   |             Value             |
|:---------:|:-----------------------------:|
|    CPU    |  Intel i5-5200u (Broadwell)   |
|   iGPU    |    Intel HD Graphics 5500     |
|   eGPU    | NVIDIA GeForce 820M (blinded) |
|   WiFi    |         [WiFi dongle]         |
| Bluetooth |      [Bluetooth dongle]       |
| Trackpad  |           Synaptics           |


- [Laptop Lenovo](./laptop_lenovo/EFI)

Lenovo V15 G2 -> MacBook Pro 13 2020 (MacBookPro16,2)

Type:         MacBookPro16,2
Serial:       C02D70DRML7H
Board Serial: C02033600GUP8PG8C
SmUUID:       66A7E2BE-0620-4A8E-86EA-FC55D4214E31
Apple ROM:    00F4B924DEA3

Type:         MacBookPro14,2
Serial:       C02WDZZPHV2N
Board Serial: C02810405CDHRPC1F
SmUUID:       012A6E73-82EF-469C-B6A5-513CE090F352
Apple ROM:    34A39520113A

Type:         MacBookPro16,3
Serial:       C02CWFYSP3XY
Board Serial: C02025207GU00001H
SmUUID:       FF8725B3-D643-48EF-81BD-0DCEB0D3965F
Apple ROM:    0C1539D0B758

|    Specs    |                             Value                             |
|:-----------:|:-------------------------------------------------------------:|
|     CPU     |                   AMD Ryzen 5 5500U (ZEN 2)                   |
|    iGPU     |                 AMD Radeon RX Vega 7 (7 CUs)                  |
|    eGPU     |                               -                               |
| Motherboard |       Lenovo V15 G2 ALC (AMD K17.6 FCH, AMD K17.6 IMC)        |
|    WiFi     |                         [WiFi dongle]                         |
|  Bluetooth  |                      [Bluetooth dongle]                       |
|  Trackpad   |                            I2C HID                            |
|    Audio    |                        Realtek ALC257                         |
|   Network   |      Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter      |
|   Network   | Realtek TRL8822CE Wireless LAN 802.11ac PCI-E Network Adapter |
|   Storage   |              SAMSUNG MZALQ512HBLU-00BL2 (PM991A)              |

SAMSUNG PM991A will cause kernel panic!


[Fenvi T919 (BCM94360CD)]: https://detail.tmall.com/item.htm?_u=ejhgkq506cf&id=621616976467&spm=a1z09.2.0.0.3c0a2e8d9EhXcu
[WiFi dongle]: https://detail.tmall.com/item.htm?_u=ejhgkq51157&id=591582535513&spm=a1z09.2.0.0.3c0a2e8d9EhXcu&skuId=4059416376519
[Bluetooth dongle]: https://item.jd.com/11078472771.html
[HDAUDIO\FUNC_01&VEN_10EC&DEV_0257]: HDAUDIO\FUNC_01&VEN_10EC&DEV_0257&SUBSYS_17AA38BF&REV_1000\5&2c0da5d1&0&0001
