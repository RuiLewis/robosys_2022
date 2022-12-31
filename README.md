# robosys_2022
ロボットシステム学2022　第一回提出課題

## 本プログラムの目的・概要
本プログラムは任意の数字を入力すると，その足し合わせ計算を実施し，本日から計算結果分の日付が経過した日付を算出し出力するプログラムである．

# plus command
![test](https://github.com/RuiLewis/robosys_2022/actions/workflows/test.yml/badge.svg)
## 使用にあたり

### インストール
* 下記の手順に従いインストールする．

	* $ git clone https://github.com/RuiLewis/robosys_2022.git
	* $ cd robosys_2022
	* $ make
	* $ sudo make install

### クイックトライアル
* 本テストは2022年11月30日に実施された．

	* :~$ cd ~/robosys_2022
	* :~/robosys_2022$ seq 10 | ./plus
	* 2023-01-24

### 推奨環境
* Python 3.7 ~ 3.10

### テスト実行環境
* ubuntu18.04 LTS

### shebang
* #!/usr/bin/python3

# ライセンス
BSD三条項ライセンス適用．詳細はLICENSE参照．

# 権利関係・謝辞
* 本プログラム内にて使用されるplusコマンドとそのテストは，千葉工業大学準教授，上田隆一先生がはじめて著作，使用された.そのソースコードは以下の講義用動画において用いられたものを参考とした．
(https://ryuichiueda.github.io/my_slides/robosys_2022/lesson4.html)
(https://ryuichiueda.github.io/my_slides/robosys_2022/lesson5.html)
(https://ryuichiueda.github.io/my_slides/robosys_2022/lesson6.html)
(https://www.youtube.com/watch?v=E5nSiTIKGd8&list=PLbUh9y6MXvjeM-lT7UoHix3zxxa6M5Jui&index=5)
(https://www.youtube.com/watch?v=ZP0vm03QJSw&list=PLbUh9y6MXvjeM-lT7UoHix3zxxa6M5Jui&index=6)
(https://www.youtube.com/watch?v=9HPLMhKvecY&list=PLbUh9y6MXvjeM-lT7UoHix3zxxa6M5Jui&index=7)
(https://www.youtube.com/watch?v=9HPLMhKvecY&list=PLbUh9y6MXvjeM-lT7UoHix3zxxa6M5Jui&index=8)
* datetime関数を用いる上で，以下のウェブサイトとプログラムを参考とした．
(https://note.nkmk.me/python-datetime-now-today)
(https://www.choge-blog.com/programming/pythondatetimegetyearmonthday)
* このREADME.mdは以下のリポジトリを参考にマークダウン方式で記述された． 
(https://github.com/ryuichiueda/GlueLang) 
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージは，3条項BSDライセンスの下，ryuichiueda/emcl由来のコード（© 2022 Ryuichi Ueda）を利用しています．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Rui Suzuki




