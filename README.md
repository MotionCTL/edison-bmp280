# edison-bmp280
弊社Henryボード用のリポジトリです。  
Intel様のupmからBMP280関係だけ抜き出しました。  
Henryボードは拡張スルーホールのi2cのバス接続は6へ接続しているのでサンプルやヘッダファイルの調整もしてあります。  
残念ながらupmの方でコンパイル時にSwigのエラーが発生しているのでC++の部分しか動作しませんでしたので他の部分は外しています。  
手順は下記の通りです。  
`git clone https://github.com/MotionCTL/edison-bmp280.git`  
`cd edison-bmp280`  
`cmake .`  
`make`  
`make install`  