# WFEGO_000001 Arduino開發環境架設

## Arduino IDE 編輯工具安裝
* IDE工具下載： 請至[https://www.arduino.cc/en/Main/Software](https://www.arduino.cc/en/Main/Software) 網站下載.

* 依據所使用作業系統，選擇對應的檔案下載
![](./image/1.png)

* 此處點選`JUST DOWNLOAD`，另外一個選項則是捐獻Arduino基金會.
![](./image/2.png)

### macOS 作業系統

* 依照作業系統，點選`macOS Intel` or `macOS Apple Silicon`.
![](./image/10.png)

* 下載完成後，找到下載的檔案，點擊該檔案.
![](./image/11.png)

* 雙擊`Arduino IDE.app` 或將`Arduino IDE.app` 拖曳至 `Application`中.
![](./image/12.png)

* 等待安裝結束.

### 安裝核心程式

* 由於WFEGO_000001(nRF52840)是Arduino相容並非Arduino原廠產品，因此必須在Arduino IDE中安裝WFEGO_000001(nRF52840)核心程式，這樣才可使用Arduino IDE寫WFEGO_000001((nRF52840))。

* 點擊`Arduino IDE.app`
![](./image/20.png)

* 點選`Arduino IDE` -> `Preferences...`
![](./image/21.png)

* 找到`Additional boards manager URLs`，並將[https://adafruit.github.io/arduino-board-index/package_adafruit_index.json](https://adafruit.github.io/arduino-board-index/package_adafruit_index.json) 新增，然後點擊`OK`.
![](./image/22.png)

* 點擊`Tools` -> `Board` -> `Boards Manager`
![](./image/23.png)

* 在`BOARDS MANAGER`打上`Adafruit`，然後選擇`Adafruit nRF52`，點擊`INSTALL`
![](./image/24.png)

* 完成以上步驟，再次點選`Tools`->`Board`->`Adafruit nRF52`->`Nordic nRF52840 DK`
![](./image/25.png)

* 選擇正確的版本後會出現以下畫面
![](./image/26.png)

## 程式上傳測試 Blink

* 完成環境設定後，就可以來寫程式測試看看.這裡就先用Blink先做個簡單的練習.

* 點選`File`->`Examples`->`01.Basics`->`Blink`
![](./image/30.png)

* 完成畫面如下
![](./image/31.png)





