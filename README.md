# SportsClassify
画像からスポーツの種類を分類するためのプログラムです

モデル作成にはalpacaさんのlabellioを利用させてもらっています。


また、環境構築はこちらを参考にしました。
http://blog-jp.alpaca.ai/entry/2015/06/30/135214

分類にはCaffe  
Webへの公開にはFlask  
を利用しています。 （一般公開時にはNginx+uWSGIを使った方がいいらしいですが、現状はFlask単体で動かしています。）
