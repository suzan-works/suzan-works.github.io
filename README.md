# suzan works プロジェクトポートフォリオ / Project Portfolio

## X(旧Twitter)アカウント
[@suzan_works](https://twitter.com/suzan_works)

## GitHubで公開中のプロジェクト

### ⚡[電圧表示付き USB PDトリガー](https://github.com/suzan-works/USBPDTrigger-VoltDisplay)  
![USBPDTrigger-VoltDisplay](https://github.com/suzan-works/USBPDTrigger-VoltDisplay/blob/main/%E4%BD%BF%E7%94%A8%E4%BE%8B.png?raw=true)  
**これは何？ / What's this?**  
WCH CH32X035マイコンを使ったUSB PDトリガーです。今どれくらいの電圧が来てるか、SSD1306 OLEDにリアルタイムで表示してくれる便利なやつ。  
It's a USB PD trigger using WCH CH32X035. Shows you the current voltage on an SSD1306 OLED display in real-time!

**できること / Features:**
- USB PD対応のシンク機能
- 128×64ピクセルのOLEDで設定電圧と実測電圧を可視化
- 5V～20Vまでお好みの電圧を選べる(USB PD固定電圧から選択)
- ブレッドボードで使いやすいコンパクトサイズ

### ⚡[USB PD対応小型マイコンボード XIAO_CH32X035](https://github.com/suzan-works/XIAO_CH32X035)  
![XIAO_CH32X035](https://github.com/suzan-works/XIAO_CH32X035/blob/main/images/1-2_mcu-board.jpg?raw=true)  

**これは何？ / What's this?**  
Arduino IDEでサクッとプログラムできる小さめマイコンボード。USB PDシンクもできちゃうので、IoTガジェットとか電源まわりの実験にぴったり。  
A small MCU board you can program right from Arduino IDE. Has USB PD sink built-in, perfect for IoT gadgets and power experiments.

**スペック / Specs:**
- MCU: WCH CH32X035C8T6 (RISC-V 48MHz LQFP48)
- USB Type-C付き（PD対応）
- 専用のSWDコネクター(1.27mm 2x5P)

### ⚡[#まいぎふ RP2040_マイコンボード](https://github.com/suzan-works/MAIGIFU_RP2040_Pico-Like_Board)  
![MAIGIFU_RP2040_Pico-Like_Board](https://github.com/suzan-works/MAIGIFU_RP2040_Pico-Like_Board/blob/main/image1.png?raw=true)  

**これは何？ / What's this?**  
Raspberry Pi Picoと同じRP2040を使った自作ボード。配布目的で作ったので安価なプリント基板製USB-Cコネクタを搭載。カラーシルク基板でピン配置が一目でわかるのがポイント。  
My own board design using the same RP2040 as Raspberry Pi Pico. Features a USB-C connector (made of PCB) and colorful silk printing so you can see pin functions at a glance.

**こだわりポイント / Special touches:**
- 安価なプリント基板製USB-Cコネクタ(下で設計データ公開してます)
- カラーシルクでピンの機能がすぐわかる
- RP2040マイコン搭載
- MicroPython/CircuitPythonも動く

### ⚡[プリント基板製USB-Cコネクタ](https://github.com/suzan-works/USB-C_PCB_Receptacle)  
![USB-C_PCB_Receptacle](https://github.com/suzan-works/USB-C_PCB_Receptacle/blob/main/images/usage-example-1.jpg?raw=true)  

**これは何？ / What's this?**  
基板に直接USB Type-Cコネクタを実装したい人向けの設計データ一式。小型デバイスや薄型製品に組み込みやすいように最適化してあります。  
Design files for mounting USB Type-C receptacles directly on PCBs. Optimized for easy integration into compact and slim devices.

**入ってるもの / What's included:**
- KiCAD用のライブラリファイル（シンボル・フットプリント）
- 使用例

### ⚡[カラーな評価ボード CH32V006K8U6](https://github.com/suzan-works/Colored-CH32V006K8U6-EVT)  
![Colored-CH32V006K8U6-EVT](https://github.com/suzan-works/Colored-CH32V006K8U6-EVT/blob/main/image2.jpg?raw=true)  

**これは何？ / What's this?**  
RISC-VなCH32V006K8U6マイコンの評価ボード。ピンの機能ごとに色分けしたカラーシルク基板で、どのピンが何なのかパッと見で分かりやすくて実験用に最適です。  
An eval board for the RISC-V based CH32V006K8U6. Color-coded silk printing makes it super easy to identify pin functions - great for learning too.

**特徴 / Highlights:**
- ブレッドボードにさせる配置
- LED・ボタン付き
- WCH-LinkE直結でSWDデバッグ可能
