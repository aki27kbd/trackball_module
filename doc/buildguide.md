# Build Guide

![trackball_module_main00](/images/main_00.jpg)

![trackball_module_main00](/images/main_03.jpg)

meishi trackball moduleのビルドガイドになります。
meishi trackball moduleは、名刺サイズ（55mm×91mm）の自作トラックボール検証基板です。そのまま組み立てることで、34mmトラックボールとスイッチ×2、ロータリーエンコーダ、OLEDを搭載したマウスやマクロパッドとして利用することが可能です。  
また、中央の2u×2u（38mm×38mm）のプレートは切り離すことで、そのままトラックボールモジュールとして他のキーボードに搭載可能です。詳細はこちらを参照ください。

## 部品
### キット付属品

#### ベースセット付属品

![meishi_bom_bottom](/images/meishi_bom_base.jpg)

#### アクリルボトムプレート付属品（オプション）

アクリルボトムプレートを自身で発注する際はこちらのデータを改編してお使いください。  
[アクリルボトムプレート](https://github.com/aki27kbd/trackball_module/blob/main/hardware/meishi_trackball_module_bottom.pdf)

![meishi_bom_bottom](/images/meishi_bom_bottom.jpg)

|名前|数|備考|
|---|---|---|
|実装済基板|1枚||
|ProMicro|1個||
|マウスセンサー（ADNS-5050）|1個||
|センサーレンズ|1個||
|3Dプリント製ボールケース|1個||
|M2ねじ 6mm|4本||
|M2ナット|4個||
|アクリルボトムプレート|1枚|オプション|
|M2ねじ 4mm|8本|オプション|
|M2スペーサー 6mm|4本|オプション|
|ゴム脚|4個|オプション|

### キット以外に必要なもの

下記パーツは[遊舎工房](https://shop.yushakobo.jp/)、[TALP KEYBOARD](https://talpkeyboard.net/)、[Daily Craft Keyboard](https://shop.dailycraft.jp/)などで揃えることが可能です。また、18mm径ノブは[へちょあまの工房＠たねやつ支店](https://taneyats.booth.pm/items/3512697)での品揃えが豊富です。

|名前|数|備考|
|---|---|---|
|MicroUSB or USB-TypeCケーブル|1本||
|ProMicro|1個||
|コンスル― or ピンヘッダ（2.5mm×12ピン）|2本||
|キースイッチ|2個|MX互換 or Choc v1|
|キーキャップ（1U）|2個|MX互換 or Choc v1|
|ロータリーエンコーダ（EC12互換）|1個|水平タイプも可|
|ロータリーエンコーダ用ノブ|1個|最大直径18mm以下|
|OLEDモジュール|1個||
|OLED用ピンソケット|1個||
|OLED用ピンヘッダ|1個||
|リセットスイッチ|1個||
|34mmボール|1個||


各ショップの在庫状況に応じて検討ください。


## 組み立て

### 1. センサー

  基板の裏面からセンサーを固定します。写真の赤枠のように、センサーの丸印と基板の丸印の位置が揃うように気を付けてください。マスキングテープなどで固定した後、表側から8本の脚をはんだ付けしてください。

  ![meishi_bg_01](/images/meishi_bg_01.jpg)

  ![meishi_bg_02](/images/meishi_bg_02.jpg)

  ![meishi_bg_03](/images/meishi_bg_03.jpg)

### 2. ロータリーエンコーダ

  続いてロータリーエンコーダのはんだ付けを行います。**必ずキースイッチの前にロータリーエンコーダのはんだ付けを行ってください。**  
  水平ロータリーエンコーダの場合は下記写真のように表側から基板に固定し、裏側6本の脚をはんだ付けしてください。

  ![meishi_bg_04](/images/meishi_bg_04.jpg)

  ![meishi_bg_05](/images/meishi_bg_05.jpg)

  通常のロータリーエンコーダの場合は下記写真のように表側から基板に固定し、裏側5本の脚をはんだ付けしてください。

  ![meishi_bg_06](/images/meishi_bg_06.jpg)

  ![meishi_bg_07](/images/meishi_bg_07.jpg)

### 3. キースイッチ

  キースイッチ2個を基板の表側から差し込み、裏側2本の脚×2個の計4か所のはんだ付けしてください。

  ![meishi_bg_08](/images/meishi_bg_08.jpg)

### 4. その他パーツ（オプション）

  OLED用ピンソケットを基板表側から差し込み、マスキングテープなどで固定した後、裏側から4本の脚をはんだ付けしてください。

  ![meishi_bg_09](/images/meishi_bg_09.jpg)

  ![meishi_bg_10](/images/meishi_bg_10.jpg)

  同様に、リセットスイッチも基板表側から差し込み、裏側から2本の脚をはんだ付けしてください。

  ![meishi_bg_11](/images/meishi_bg_11.jpg)

  ![meishi_bg_12](/images/meishi_bg_12.jpg)

  OLED用ピンヘッダをOLEDモジュールに差し込みます。ピンヘッダが斜めにならないよう気を付けながらはんだ付けをおこなってください。

  ![meishi_bg_13](/images/meishi_bg_13.jpg)

  はんだ付けの行程は以上になります。

  ![meishi_bg_14](/images/meishi_bg_14.jpg)

### 5. ボールケース

ボールケースにセラミックボールを固定します。（写真はcocot46plusのボールケースになりますが、手順は同様です。）キット内容物以外に必要な道具は下記写真の通り、エポキシ2液混合接着剤、接着剤を取り出す容器、爪楊枝になります。  
![cocot46plus_bg_ballcase_01](https://user-images.githubusercontent.com/88039287/226820854-839753fa-50cc-49b4-b183-860b4672632e.jpg)

接着剤の取り扱い説明に沿って接着液の準備を行います。  
![cocot46plus_bg_ballcase_02](https://user-images.githubusercontent.com/88039287/226820885-08b87789-22ed-47b8-828b-e8ba3df3491b.jpg)

爪楊枝の先端に接着剤を少量付け、ボールケース内側の穴に塗ります。塗りすぎるとボールを嵌めた際にあふれてしまうので、窪みの内側が接着剤で薄く覆われる程度を目安としてください。  
![cocot46plus_bg_ballcase_03](https://user-images.githubusercontent.com/88039287/226820905-af0f3451-a6f7-4ecd-a42f-e3e1407a0052.jpg)

![cocot46plus_bg_ballcase_04](https://user-images.githubusercontent.com/88039287/226820925-2cb8de68-cb62-473e-a874-141fe15a1e09.jpg)

接着剤が乾く前にボールをはめ込みます。接着剤がボールの周りにあふれてしまった場合は固まる前にきれいにふき取ってください。  
![cocot46plus_bg_ballcase_05](https://user-images.githubusercontent.com/88039287/226820957-14e5d2f1-9693-4ec7-9fb0-9a6081d463f8.jpg)

3箇所すべてボールを接着すればボールケースの準備完了です。  
![cocot46plus_bg_ballcase_06](https://user-images.githubusercontent.com/88039287/226821043-05606c8c-6c40-4bf9-b368-8b84e1a0726b.jpg)


### 6. 組み立て

  センサー用レンズをセンサーの上に被せます。レンズの向きに注意してください。

  ![meishi_bg_15](/images/meishi_bg_15.jpg)

  ボールケースをレンズ上から被せます。ボールケースの溝とレンズがぴったりはまるように向きに注意してください。

  ![meishi_bg_16](/images/meishi_bg_16.jpg)

  M2 6mmねじとナットでボールケースを基板に固定します。写真のように上からM2ねじを差し、裏側からナットで固定します。

  ![meishi_bg_17](/images/meishi_bg_17.jpg)

  オプションのアクリルボトムプレートを組み立てる場合、まずアクリルプレートにM2 6mmスペーサーをM2ねじ4mmで固定します。

  ![meishi_bg_18](/images/meishi_bg_18.jpg)

  スペーサーの上に基板を重ね、基板上からもM2 4mmねじで固定します。

  ![meishi_bg_19](/images/meishi_bg_19.jpg)

  裏面にゴム脚を貼ります。

  ![meishi_bg_20](/images/meishi_bg_20.jpg)

  34mmボール、キーキャップ、ノブを付けて完成です！

  ![meishi_bg_21](/images/meishi_bg_21.jpg)

## ファームウェア

  [REMAP](https://remap-keys.app/catalog/YTktEniNbS090Dnwr0mk/firmware)からファームウェアのダウンロードおよびProMicroへの書き込みを行うことができます。キーマップは[こちら](https://remap-keys.app/configure)から更新可能です。  
トラックボール、LED含めて上記.hexファイルで確認いただけます。

（.hexファイルをQMK ToolboxなどでProMicroに書き込む従来の方法でも問題ありません。）


![REMAP](/images/meishi_bg_remap.jpg)


組み立て段階で動作確認をする際も、REMAPのTest Matrix Modeを使うと便利です。ただし、Test Matrix Modeではロータリーエンコーダの回転は確認できないので、別途キー入力等で動作を試してください。


ソースコードは[こちら](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/aki27/trackball_module)を参照ください。  
また、VIA用のjsonファイルは[こちら](https://github.com/aki27kbd/trackball_module/blob/main/firmware/trackball_module_via.json)を参照ください。


## OLED

  OLEDにはトラックボールの情報を表示することが可能です。

  ![meishi_bg_oled_1](/images/meishi_bg_oled_1.jpg)

  OLED|Description
  ---------|-----------
  Layer|現在のレイヤーを示します。
  Mode|Cursor:カーソル/Scroll:スクロールモードを示します。
  CPI|カーソルモードのCPIを示します。
  ScDiv|スクロールモードにおけるセンサーの感度を示します。数値が大きいほどスクロール量が小さくなります。
  Angle|マウスセンサーのY軸の回転角を示します。

  手の大きさやトラックボールへの手の置き方によって、操作しやすいY軸の回転角が異なります。`ROT_R15`、`ROT_L15`キーで調整しながら自分に合った設定を探してみてください。

  ![meishi_bg_oled_2](/images/meishi_bg_oled_2.jpg)


## 終わりに
何かトラブルがあれば[Twitterアカウント](https://twitter.com/aki27kbd)までご連絡ください。

また、完成写真をSNSにアップいただけるととても励みになります。（アップするのがはばかられる方はDMで直接送りつけていただいても構いません。）

ハッシュタグは #trackball_module です。
