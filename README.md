# robosys_kadai1

## 内容
上田隆一教授によるデバイスドライバを改変し、作成した。

## 準備するもの
・rasberry Pi4　×1　


・ブレッドボード(SAD-101)　×1 


・LED ×2


・抵抗 (100Ω) ×2 


・ジャンパーワイヤ　オス-オス ×2 


・ジャンパーワイヤ　オス-メス ×3

## 機能
1.1つのLEDが交互に点滅　：　echo t > /dev/myled0


2.1つのLEDは点いたままもう片方のLEDは点滅　：　echo l > /dev/myled0


3.2と反対のことが起こる（1つのLEDは点いたままもう片方のLEDは点滅）　：　echo r > /dev/myled0


## 動作方法
make


sudo insmod myled.ko 


sudo chmod 666 /dev/myled0 ・・・


## Youtube
https://youtu.be/OwW6O0iICZw

## 協力者
小村岳都
西廣巧
嶋田雅
