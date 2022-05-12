# wordcount
英語の文章をファイルから受け取り、単語を数えて多い順でtop3を表示する

# usage
```shell script
go build
time ./wordcount hoge.txt
```

# sample data
https://drive.google.com/drive/folders/1C0KjkmxOeisIh9TFBSv3XPBQbuJvEOZb?usp=sharing

# problem
このプログラムの問題点を書いておく。
- 非常に遅い
- テストがし辛い
  - panicしている
  - 副作用(標準出力)を伴う関数になっている
