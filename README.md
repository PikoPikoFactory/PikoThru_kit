# PikoThru_kit

![outlineiimage](/image/pikothru.png)

## About this page
- 
- 

## Parts List

| リファレンス番号 | 個数 | 部品名 |
| ---------------- | ---- | -------|
|C1, C2|2|セラミックコンデンサ 0.1uF|
|CN1|1|DINコネクタ|
|D1, D2|2|ショットキーダイオード SBM245|
|D3|1|LED|
|D4|1|ダイオード 1N914|
|J1, J2, J3, J4, J5, J6, J7, J8, J11, 	9	3.5mmステレオジャック |
|J9|1|USB Type-C コネクタ|
|J10|1|JST XHコネクタ|
|R1, R2, R3, R4, R5, R6, R7, R8, R9, R10, R11, R12, R13, R14, R15, R16, R20, 	17	抵抗 220Ω
|R17, R18|2|5.1kΩ|
|R19|1|1kΩ|
|R21|1|100kΩ|
|R22|1|3.3kΩ|
|SW1|1|スライドスイッチ|
|U1|1|CMOS IC 74HC245|
|U2|1|フォトカプラ 4N28|

## 回路図

[Schematics](/Hardware/pikothru_schematic.pdf)

## 基板パターン図

[PCB Pattern](/Hardware/pikoturu_pattern.pdf)

## 部品配置図

![PartsPlacementChart](/image/Pikothru_parts_place.png)

## 部品実装上の注意
### ダイオード
- ダイオードは極性があります。方向に注意してください。
- D5は線が付いている方向がカソード(K)です。

![PartsPlacementImage](/image/IMG_5644.JPG)


- LED(D1～D4)はリード線の短い方がカソード(K)です。以下の図を参考にしてください。

![PartsPlacementImage](/image/diode.PNG)

### U1 Arduino Nano Every

- U1 Arduino Nano Every はUSBコネクタが外側になるように取り付けてください。部品配置図を参考にしてください。

### U2 5V出力昇圧DC/DCコンバーターキット

- U2 5V出力昇圧DC/DCコンバーターキットは以下の写真の方向で取り付けてください。

![PartsPlacementImage](/image/IMG_5643.JPG)





## ソフトウェア
- Arduino IDEベースです。
- MIDIライブラリが必要です。MIDIライブラリは多種リリースされていますが、https://github.com/FortySevenEffects/arduino_midi_library を使用しています。

### サンプルコード
- Arduino Nano Every用です。
- ファンクションキーと鍵盤キーの同時押しで、MIDI CH変更や、Program Change等の送信が可能です。下図を参照ください。
- 2023/10/28 Note NoのBug Fixしました
 

[PikoKey_V1_1.ino](/Software/PikoKey_V1_1.ino)

![FunctionImage](/image/function.png)
