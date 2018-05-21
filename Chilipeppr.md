# 後でちゃんと書きます  
---  

---  


# Chilipeppr  

Chilipeppr とは、 r7 CNC を制御するためのオンラインツール  
これに、Fusion360 の CAM から書き出した g code を読み込む  


---  

### how to use  

ブラウザからアクセスする  
※ ブラウザは Firefox が良さそう、Microsoft Edge だとダメかも  

[http://chilipeppr.com/tinyg](http://chilipeppr.com/tinyg)  

![photo](photo/Chilipeppr-Top.png)  

g code をドラッグ&ドロップ  


---  

### エラーでの一時停止  

本体が停止して CNC 側に乗っている制御ボードの赤色 LED が点滅しているときはエラー。  


---  

### エラーで停止した時にの時に g code で復旧させる方法  

左側の g code の欄で、確実に終わっている行で確実に終わってる行を探す。  

![photo](photo/Chilipeppr-gcode-01.png)  




velocity