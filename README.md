# 2017年度LOCAL学生部総大会
## ファイル名
* それぞれファイル名はTwitterのID名+.tex
  * keisuke495500.tex
  * chikuwa_IT.tex
  * materialofmouse.tex
  * lrf141.tex
  * takuzoo3868.tex
  * Jumpaku.tex
  * aruneko99.tex
## コンパイル
texlive2017をインストールしてる人は
``` bash
$ latexmk -pvc main.tex
```
それ以外の人は
``` bash
$ docker-compose up
```
3GBくらいのdocker imageをダウンロードするので注意
