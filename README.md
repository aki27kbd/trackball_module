# trackball_module

![trackball_module_main00](/images/main_00.jpg)

This is a module part for 34mm trackball with ADNS-5050 sensor. Module size is within 2u x 2u (38mm x 38mm) so that it can be easily implemented with existing DIY keyboards. Connection with other boards is via 2.54mm-pitched 5 pins or 1.0mm-pitched SH connector. The module is embedded with a Meishi (name card) sized PCB which can also work as a stand-alone mini trackball with two keys, a rotary encoder and an OLED display.

- Keyboard Maintainer: [aki27kbd](https://github.com/aki27kbd) [@aki27kbd](https://twitter.com/aki27kbd)
- Hardware Supported: meishi trackball module PCB, ProMicro
- Hardware Availability: [BOOTH](https://aki27.booth.pm)
  Go on sale in October 2022.

Build Guide [JP](doc/buildguide.md) / [EN](doc/buildguide_en.md)

## 1. Stand-alone Mini Trackball
Meishi trackball module can be used as a mini trackball running on QMK. Keycodes and rotary encoder settings are easily customized via [Remap](https://remap-keys.app/).

### BOM
|名前|数|備考|
|---|---|---|
|MicroUSB or USB-TypeCケーブル|1本||
|ProMicro|1個||
|コンスル― or ピンヘッダ（12ピン）|2本||
|キースイッチ|2個|MX互換 or Choc v1|
|キーキャップ（1U）|2個|MX互換 or Choc v1|
|ロータリーエンコーダ（EC12互換）|1個|水平タイプも可|
|ロータリーエンコーダ用ノブ|1個|最大直径16mm以下|
|OLEDモジュール|1個||
|OLED用ピンソケット|1個||
|OLED用ピンヘッダ|1個||
|リセットスイッチ|1個||
|34mmボール|1個||
|M2ねじ 6mm|4本||
|M2ナット|4個||
|アクリルボトムプレート|1枚|オプション|
|M2ねじ 4mm|8本||
|M2スペーサー 6mm|4本||

![trackball_module_main01](/images/main_01.jpg)

![trackball_module_main02](/images/main_02.jpg)

## 2. Trackball Module

![trackball_module_main03](/images/main_03.jpg)

Square part located at the center of Meishi PCB can be cut off and used as a trackball module. There are several ways to connect this module with main boards.

1. Pin Headers & Pin Sockets  
  5 pins need to be connected. Straight and L-angle types are available.

2. Cables
  Cabling/wiring between pins of the module and the main board.

3. SH Connectors
  SH horizontal connectors are also supported for the connection with external boards.
