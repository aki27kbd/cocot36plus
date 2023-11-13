# Build Guide

![cocot36plus_main00](/images/main_00.jpg)

cocot36plusのビルドガイドになります。

cocot36plusは中央に34mmトラックボールとスクロールリングを搭載したカラムスタッガード30%キーボードです。コンパクトながら豊富な機能を搭載しています。
- 中央にトラックボールとスクロールリングを配置
- フルキーバックライト & アンダーグロウLED & RGBマトリクス対応
- MCUはオンボードRP2040

また、ボールカバーを兼ねたスクロールリングは逆さにしてもボールが落ちず、かつ片手でボールの着脱が可能な設えとなっています。容易なボールのメンテナンスが可能となりました。


## 部品
### キット付属品

|名前|数|備考|
|---|---|---|
|実装済基板|1枚||
|スイッチプレート|1枚||
|ボトムプレート|1枚||
|マウスセンサー（PMW3360）|1個||
|センサーレンズ|1個||
|リングエンコーダ|1個||
|OLEDモジュール+付属ピンヘッダ|1個||
|M2ねじ 4mm|16本|
|M2ねじ 8mm|2本|
|M2ナット|2個||
|M2スペーサー 9mm|8本||
|ゴム脚|6個||
|ボールホルダー|1個||
|ボールカバー|1個||


### キット以外に必要なもの

下記パーツは[遊舎工房](https://shop.yushakobo.jp/)、[TALP KEYBOARD](https://talpkeyboard.net/)、[Daily Craft Keyboard](https://shop.dailycraft.jp/)などで揃えることが可能です。

|名前|数|備考|
|---|---|---|
|USB-TypeCケーブル|1本||
|キースイッチ|36個|MX互換|
|キーキャップ|36個|MX互換|
|34mmボール|1個||

各ショップの在庫状況に応じて検討ください。


## 組み立て
### 0. 部品確認

  まずはキット付属品に記載されたパーツが揃っているか確認ください。  
  その他上述の「キット以外に必要なもの」および「オプション部品」を揃えた上で組み立てに取り掛かってください。

  - タブ付きPCBの場合にはタブを割って切り離し、切断面を軽くヤスリがけしてください。
  - PCB、スイッチプレートの側面を油性マジックなどで黒く塗ると見栄えが良くなります。ぜひ試してみてください。

  上:未塗装 / 下:塗装済  
  ![cocot36plus_bg_00](/images/bg_00.jpg)


### 1. マウスセンサー

  マウスセンサー（PMW3360）を基板裏面から写真の向きに設置し、表面からはんだ付けを行います。シルクの●印と基板の●　印の位置が合うように注意してください。  
  ![cocot36plus_bg_01_1](/images/bg_01_1.jpg)

  センサーの脚がしっかり奥まで入った状態で、浮かないようにマスキングテープなどで固定します。  
  ![cocot36plus_bg_01_2](/images/bg_01_2.jpg)

  表面から16本の脚をはんだ付けします。  
  ![cocot36plus_bg_01_3](/images/bg_01_3.jpg)

  センサーに貼られているテープを剥がし、表面からレンズを付けます。
  ![cocot36plus_bg_01_4](/images/bg_01_4.jpg)


### 2. OLED

  OLEDピンヘッダを表側から挿し、マスキングテープなどで固定します。  
  ![cocot36plus_bg_02_1](/images/bg_02_1.jpg)

  基板裏側からピンヘッダの脚4本のはんだ付けを行ってください。  
  ![cocot36plus_bg_02_2](/images/bg_02_2.jpg)

  ペンチなどでピンヘッダのプラスチック部分を取り外します。ゆっくり真っすぐ上に少しずつずらしていくイメージです。  
  ![cocot36plus_bg_02_3](/images/bg_02_3.jpg)

  OLEDモジュールの裏側にマスキングテープやカプトンテープを貼り絶縁します。  
  ![cocot36plus_bg_02_4](/images/bg_02_4.jpg)

  OLEDモジュールをピンヘッダに通し、はんだ付けを行った後飛び出しているピンをカットします。OLEDモジュールが浮いていると後工程でスイッチプレートが浮いてしまうので、できるだけOLEDはPCBに近い位置で固定されるようにはんだ付けを行ってください。  
  ![cocot36plus_bg_02_5](/images/bg_02_5.jpg)


### 3. スクロールリング

  スクロールリングをPCB表面から差し込み、裏面の3か所はんだ付けを行います。  
  ![cocot36plus_bg_03_1](/images/bg_03_1.jpg)

  ![cocot36plus_bg_03_2](/images/bg_03_2.jpg)

### 4. 組み立て

  ボトムプレートに4mmネジで9mmスペーサーを固定します。  
  ![cocot36plus_bg_04_1](/images/bg_04_1.jpg)

  PCBとレンズの上にボールホルダーを載せ、8mmネジを裏面からナットで固定します。  
  ![cocot36plus_bg_04_2](/images/bg_04_2.jpg)

  ![cocot36plus_bg_04_3](/images/bg_04_3.jpg)

  スイッチプレートと基板を重ね、隅から順番にキースイッチをはめていきます。スイッチの向きに気を付けて、またスイッチの脚が曲がらないように真っすぐに差し込むようにしてください。  
  ![cocot36plus_bg_04_4](/images/bg_04_4.jpg)

  スイッチを差し込んだスイッチプレート&基板を、ボトムプレートの上に重ねます。スイッチプレート表面から4mmネジで8か所固定します。  
  ![cocot36plus_bg_04_5](/images/bg_04_5.jpg)

  ボールカバーをスクロールリングに装着します。緩い場合はマスキングテープや両面テープで接着面を増やすようにしてください。  
  ![cocot36plus_bg_04_6](/images/bg_04_6.jpg)

  ![cocot36plus_bg_04_7](/images/bg_04_7.jpg)

  ボール、キーキャップをはめて完成です。  
  ![cocot36plus_bg_04_8](/images/bg_04_8.jpg)

  ![cocot36plus_bg_04_9](/images/bg_04_9.jpg)  


## ファームウェア

デフォルトのファームが書き込まれた状態でお届けしています。ご自分でファームを書き込む場合、下記手順の通り実行してください。

  - 裏面のBOOTボタンを押しながらRESETボタンを押し、ブートローダーモードに入ります。
  - その状態でRPI-RP2というドライブに[.uf2](https://github.com/aki27kbd/cocot36plus/blob/main/firmware/aki27_cocot36plus_auto_mouse.uf2)ファイルをドラッグ&ドロップすることでファームが書き込まれます。

キーマップは[こちら](https://remap-keys.app/configure)から更新可能です。  
トラックボール、LED含めて上記.uf2ファイルで確認いただけます。


![REMAP](/images/Remap.jpg)

組み立て段階で動作確認をする際も、REMAPのTest Matrix Modeを使うと便利です。ただし、Test Matrix Modeではスクロールリングの回転は確認できないので、別途キー入力等で動作を試してください。

標準ファームウェアでは、トラックボールの動きを検知すると自動的にレイヤー4に移動します。レイヤー4にマウスキーなどを設定すると使いやすいです。

ソースコードは[こちら](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/aki27/cocot36plus)を参照ください。  
また、VIA用のjsonファイルは[こちら](https://github.com/aki27kbd/cocot36plus/blob/main/firmware/cocot36plus_via.json)を参照ください。


## カスタムキーコード

  トラックボールの操作に関していくつかカスタムキーコードを設定することが可能です。スクロール関係のキーコードに関しては、デフォルトのファームでは無効になっています。（SCRL_MOはレイヤー4でのみ有効）

  Value    | Keycode   |Description
  ---------|-----------|-----------
  `0x5DA7` | `CPI_SW`  |トラックボールのCPIを変更します。デフォルトのファームウェアでは、押すたびに200→400→800→1600→3200→200…という順番でCPIが変わります。
  `0x5DA8` | `SCRL_SW` |スクロールモードにおけるセンサーの感度を変更します。数値が大きいほどスクロール量が小さくなります。
  `0x5DA9` | `ROT_R15` |マウスセンサーのＹ軸を時計回りに15度回転させます。
  `0x5DAA` | `ROT_L15` |マウスセンサーのＹ軸を反時計回りに15度回転させます。
  `0x5DAB` | `SCRL_MO` |押されている間スクロールモードになります。（デフォルトファームではレイヤー4でのみ有効）
  `0x5DAC` | `SCRL_TO` |押すたびにスクロールモードとマウスモードを切り替えます。（デフォルトファームでは無効）
  `0x5DAD` | `SCRL_IN` |スクロール方向を反転させます。（デフォルトファームでは無効）

  REMAPでカスタムキーコードを設定する場合はFunctionタブ下のカスタムキーコードを用いて設定することが可能です。  
  ![CustomKeycode_rev](/images/CustomKeycode.jpg)


## OLED

  OLEDにはトラックボールの情報を表示することが可能です。  
  ![cocot46plus_bg_oled_1](https://user-images.githubusercontent.com/88039287/170496379-0b8dcec6-afac-48e9-b727-ad647c4a09c9.jpg)

  OLED|Description
  ---------|-----------
  Current Layer|現在のレイヤーを示します。
  Scroll Status|C:カーソル/S:スクロールモードを示します。
  CPI|カーソルモードのCPIを示します。
  Scroll Divider|スクロールモードにおけるセンサーの感度を示します。数値が大きいほどスクロール量が小さくなります。
  Rotation Angle|マウスセンサーのY軸の回転角を示します。

  手の大きさやトラックボールへの手の置き方によって、操作しやすいY軸の回転角が異なります。`ROT_R15`、`ROT_L15`キーで調整しながら自分に合った設定を探してみてください。  
  ![cocot46plus_bg_oled_2_2](https://user-images.githubusercontent.com/88039287/170499867-b430839b-f2f0-4163-afa2-c227184bd697.jpg)

  ![cocot46plus_bg_oled_3_4_5](https://user-images.githubusercontent.com/88039287/171883896-1a3b91cb-84b8-425c-b490-9affa5f42095.jpg)


## Links

  [【大注目！】トラックボール付き自作キーボード cocot36plus/coron47plus レビュー | Trackball Mechanical Keyboard Review](https://www.youtube.com/watch?v=GIpaJPnjrzo) (by Daihukuさん)  
  トラックボールの使い心地、内部構造、スクロールリングなど紹介いただいています。

  [Gallery on Twitter](https://twitter.com/search?q=%23cocot36plus&src=typed_query&f=image)



## 終わりに
何かトラブルがあれば[Twitterアカウント](https://twitter.com/aki27kbd)までご連絡ください。

また、完成写真をSNSにアップいただけるととても励みになります。（アップするのがはばかられる方はDMで直接送りつけていただいても構いません。）

ハッシュタグは #cocot36plus です。
