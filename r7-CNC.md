# r7-CNC

- 電源接続  
- 制御ボードとパソコンの接続  
- 切削原点の設定  
- エンドミルの交換  


r7 CNC の使い方等、書きます

---  

### 電源接続  

電源ユニットx2 をコンセントに繋ぐ  

![photo](photo/PowerUnit-01.jpg)

---  

### 制御ボードとパソコンの接続  

PC と USB A-B ケーブルで接続  

![photo](photo/Board-01.jpg)  

json-server を建てた後、Chilipeppr にアクセス（ [http://chilipeppr.com/tinyg](http://chilipeppr.com/tinyg)）  
右下の接続のパネルでチェックを入れて接続  

![photo](photo/Chilipeppr-Top.png)  

---  

### 切削原点の設定  

XY と Z（大事）  

Z は、紙を挟んで材料の高さと合わせる  

![photo](photo/Setting-Z-position.jpg)

---  

### エンドミルの交換  

13ミリのレンチ + 17ミリのレンチで緩めて、交換。  
交換した後はきつく締める。  

![photo](photo/ChangeMill.jpg)  
