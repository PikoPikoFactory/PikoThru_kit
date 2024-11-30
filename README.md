# PikoThru_kit

![outlineiimage](/image/pikothru.png)

## About this page
- 1 in 8 turu 小型MIDIスルーボックス PikoThru 組み立てキットの情報ページです。

## Parts List

| リファレンス番号 | 個数 | 部品名 |
| ---------------- | ---- | -------|
|C1, C2|2|セラミックコンデンサ 0.1uF|
|CN1|1|DINコネクタ|
|D1, D2|2|ショットキーダイオード SBM245|
|D3|1|LED|
|D4|1|ダイオード 1N914|
|J1, J2, J3, J4, J5, J6, J7, J8, J11|9|3.5mmステレオジャック|
|J9|1|USB Type-C コネクタ|
|J10|1|JST XHコネクタ|
|R1, R2, R3, R4, R5, R6, R7, R8, R9, R10, R11, R12, R13, R14, R15, R16, R20|17|抵抗 220Ω|
|R17, R18|2|5.1kΩ|
|R19|1|1kΩ|
|R21|1|100kΩ|
|R22|1|3.3kΩ|
|SW1|1|スライドスイッチ|
|U1|1|CMOS IC 74HC245|
|U2|1|フォトカプラ 4N28|

## 回路図

[Schematics](/hardware/pikothru-schematic.pdf)

## 基板パターン図

[PCB Pattern](/hardware/pikothru-pattern.pdf)

## 部品配置図

![PartsPlacementChart](/image/pikothru-parts-place.png)

## 部品実装上の注意
### ダイオード
- ダイオードは極性があります。方向に注意してください。
- D1,D2,D4は線が付いている方向がカソード(K)です。

![PartsPlacementImage](/image/d1d2.jpg)
![PartsPlacementImage](/image/d4.jpg)

- LED(D3)はリード線の短い方がカソード(K)です。以下の図を参考にしてください。

![PartsPlacementImage](/image/diode.PNG)

### IC(U1,U2)
- 写真の作例ではソケットを使っていますが、付属しておりません。直接ハンダ付けに不安のある人は、別途入手して、使用してください。
- 取付方向が上下逆になりますので注意してください。

![PartsPlacementImage](/image/ic.jpg)
