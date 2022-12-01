# robosys2022
本リポジトリは、2022年度のロボットシステム学で扱ったソースコードをまとめています。  
  * ```plus```  : 標準入力から読み込んだ数字を足す
---
[![test](https://github.com/ando72000/robosys2022/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/ando72000/robosys2022/actions/workflows/test.yml)  
↑ テストの結果が表示されるページに飛びます。

## ・インストール方法
こちらのコマンドをコピーして入力するとインストールできます。  
```
git clone https://github.com/ando72000/robosys2022.git
```
```  
cd robosys2022
```  

GitHubのアカウントを持っている方は下記の方法でも可能です。
```
git clone git@github.com:ando72000/robosys2022.git
```
```
cd robosys2022
```

## 【 plusコマンド 】
標準入力から読み込んだ数字を足し、標準出力するコマンドです。

### ・使用例
  * 実行
```
seq 5 | ./plus
```
1～5までの数字を標準入力し、```plus```に読み込ませる。

  * 結果
```
15
```


### ・必要なソフトウェア
Phython  (ver 3.7～3.10までテスト済)

### ・動作環境
Ubuntu22.04


## ・ライセンス
  * このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
  * このパッケージのコードは、下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを、本人の許可を得て自身の著作としたものです。
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)


© 2022 Natsu Ando
