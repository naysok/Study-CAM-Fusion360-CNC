# STL-CAM  

メッシュ (STL) から切削パスを生成 → とりあえずできた  

色々試しているけど、メッシュの扱いはあまり賢くない...  



---  

メッシュの切削は、材料の塊から掘り残すみたいな感じ  


### 脚を追加  



![photo](photo/STL-add-Model-01.png)  

![photo](photo/STL-add-Model-02.png)  


### セットアップ  

セットアップ > モデル のところでメッシュを選択  
ストック > サイドを追加  

![photo](photo/STL-Stock-02.png)  

### 3D 負荷制御  





### シミュレーション

ここの情報のタブでかかる時間も見れる   

![photo](photo/STL-Sim-01.png)  

動画リンク ↓  

[![](http://img.youtube.com/vi/dgeH3hgkJ3Q/0.jpg)](http://www.youtube.com/watch?v=dgeH3hgkJ3Q)  


### ポスト処理  

書き出しの設定で g code の方言の指定  

![photo](photo/PostProcess-Export.png)  


---  

---  


## ※こここから下は失敗してた時のものです。  



### セットアップ  

エンドミル交換等に使えるように、切削エリアとは別の所に、原点。メッシュ + Brep でストックとしてくくる。  

![photo](photo/STL-Stock-01.jpg)  


### 3D ポケット  

選び方によって、ストック全体からの削り出しになった。これはアホ。  

![photo](photo/STL-3D-Pocket-02.jpg)  

選び方を何か変えたら、表面だけできた。  
これと仕上げ（+ 輪郭）を組み合わせてやればいけるはず。  

![photo](photo/STL-3D-Pocket-01.jpg)  



### 2D 輪郭  

メッシュのエッジは使えずに、ストックの全体の輪郭しか使えない。  
ストックと切削モデルを同じ形にするか、加工パス出し用の捨てデータかスケッチかなんらかが必要。

![photo](photo/STL-2D-Contour-01.jpg)  


### その他  

STL 部分で加工範囲を作ってその加工範囲を指定で加工、エンドミル交換用の位置合わせ点は、machine zeroの x に +10mm地点でばみるとか...。  

そもそも、これは、直方体のデータで、ストックとほぼ同じ形の場合なので、他の場合はまた違うかな。  


