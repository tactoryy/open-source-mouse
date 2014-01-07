# NIGI-Mouse
## sfc2013-design-strategy
This document is made by [gitfab](http://gitfab.org)
---
#にぎにぎマウス
マウスにふれると、手をにぎってくれるマウス

【コンセプト】
2013年6月に4年と2ヶ月つきあってた彼女が家からでていってしまったぼくが、クリスマス寂しく仕事してすごさなくていいような、手をぎゅっとしてくれるマウス。

【仕様】
マウスに触れるとイルミネーションモード
マウスを右クリックすると、手をギュッと。
専用のマウスパッドをつくって、好きなキャラを着せ替え可能。


---
#用意するもの
•Arduino Uno
•USB A-Bケーブル
•6V1A DCアダプター
•サーボモータ
•2.1mmDCジャック
•感圧センサ
•1wフルカラーLED
•可変抵抗(10kΩ)
•ブレッドボードorユニバーサル基板
•ジャンプワイヤ(線材)
•手袋
•綿
•ドライバー
•グルーガン
•グルースティック
•はんだ
•はんだごて
•ガラス板
•両面テープ
•傘の骨のさきっぽ
•マウス
•好きなキャラのクリアファイルとか写真とか
•はさみ
•寂しい心
•遊び心
---
# 完成予想図

スケッチ
![写真 2014-01-07 15 01 45.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/写真-2014-01-07-15-01-45.jpg)
---
#作り方(手編)

手袋のなかに、綿をいれて、弾力をつける。
手袋の手首の部分を内側におりこんで、両面テープで固定し落ちないようにする。
サーボモータに付属の歯車とサーボモータの間に手袋をうめて、ドライバーでねじを固定。


![手袋サーボモータ.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/手袋サーボモータ.jpg)

![prt_te.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/prt_te.jpg)
---
#作り方(マウス編)

マウスに綿を、お好みで、布用ボンドで固定していく。
さらにお好みで、上からキラキラするのをまぶして装飾。

---
#作り方(ハード編)

Arduinoとタッチセンサ、LED、サーボモータを配線する タッチセンサを、マウスのどこか、触れるとこに貼付ける LEDはテスト用の、おまけだから適当なとこでいい (あとで回路図添付します)
---
#作り方(サーボモータとマウスつなぐ編)

サーボモータに、ホットボンドで棒を2本固定する マウスにその棒がはまる穴をあけ、棒をいれ、ホットボンドで固定する
---
#作り方(ソフトウェア編)

arduinoで、感圧センサが感知したら、 サーボを90度うごかし、感知していないときは、0度にもどるような仕様。
---
#完成

写真あとで、のせます
---
#感想•今後広げられること

あったかくて、感触もきもちい 手の指の間接も曲げれたらいいなあ。 ArduinoをMEGAにして、さらにLED24個分くらいマウスに穴あけて、 マウスにしこんで、触ってるときに、ピカピカ光ってたらもっとかわいい
---
