# WFEGO_000001 介紹

## The Pinout of the WFEGO_000001-01

![pinout](./Board/WFEGO_000001_600DPI.png)

### LED 資訊
* SystemLED : P0.06，對應GPIO Number為 **6**.
* RLED : P0.08，對應GPIO Number為 **8**.
* GLED : P1.09，對應GPIO Number為 **41**.
* BLED : P0.12，對應GPIO Number為 **12**.
* **LED PIN LOW = Enable (LED On)**

### 按鈕 資訊
* RST : 用以重置系統/進入Bootloader Mode.
  * Double Reset : Reset twice within 500 ms will enter DFU with UF2 and CDC support.
* SW : P1.06，對應GPIO Number為 **38**.

  

## 開發方式
* 支援`Arduino IDE`開發.
* 支援`Nordic SDK`開發.
  * nRF5 SDK(原廠不再更新).
  * nRF Connect SDK.

## 相容
* 與 ESP32 (NodeMCU 32S) 安信可版本 幾乎相容.
  * 需將`P0.05設為Output並輸出Low準位`.
* 與 nRF52840 Dongle 幾乎相容.
  * `CONFIG_BOARD_ENABLE_DCDC_HV=n`
* 支援nRF Connect for Desktop
  * Bluetooth Low Energy
  * Programmer
  * RSSI Viewer
  * BLE Sniffer
  * Zigbee Sniffer

## [nRF52840 原廠資料](https://infocenter.nordicsemi.com/index.jsp?topic=/struct_nrf52/struct/nrf52.html)

## [模組資料](https://www.raytac.com/product/ins.php?index_id=24)

## [教學](./Tutorial/Tutorial.md)

## [外殼模型下載](https://makerworld.com/zh/models/2144796-compact-nrf52840-case-for-ble-zigbee-experiments#profileId-2323360)

## [Buy From](https://shopee.tw/nRF52840-%E9%96%8B%E7%99%BC%E6%9D%BF-i.26640381.23644275212?sp_atk=af0a1c73-030b-4a82-b1d5-a3a14a383f4f&xptdk=af0a1c73-030b-4a82-b1d5-a3a14a383f4f)
