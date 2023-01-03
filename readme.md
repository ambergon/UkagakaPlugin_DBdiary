# DBdiary
簡単な日記を作成するためのプログラムです。

## 使用可能な関数一覧
```
"\![raiseplugin,DBdiary,OnCallInputDirtyDiary,before_text,after_text]"
"\![raiseplugin,DBdiary,OnCallInputBeautifulDiary,before_text,after_text]"
"\![raiseplugin,DBdiary,OnGetBeautifulDiary,yyyymmdd,before_text,after_text,notWrite,notExist]"
```

## 日記を書く
二種類の方法で日記を書くことができます。
- DirtyDiary
    保存名が日付+日記内容.txtになります。<br>
    日記の中には「Dirty Diary」に統一されます。<br>

- BeautifulDiary
    保存名が日付.txtになります。<br>
    こちらはゴーストから日記内容を取得できるようにしています。<br>

#### 日記の保存先
プラグインフォルダ/Diary/yyyymmdd{Dirty Diary only}.txt


## DirtyDiaryを呼び出す。
このプラグインをインストールしている状態で下記のサクラスクリプトを打ち込んでください。<br>
入力欄が出てきます。<br>
ゴーストに発言させる場合はbefore_textやafter_textの部分を適時書き換えてください。<br>
他のテキストと相性が悪かったためこのような形になりました。<br>
```
"\![raiseplugin,DBdiary,OnCallInputDirtyDiary,before_text,after_text]"
```

## BeautifulDiaryを呼び出す。
使用方法は同じです。
```
"\![raiseplugin,DBdiary,OnCallInputBeautifulDiary,before_text,after_text]"
```

##日記の内容を引っ張り出す。
同じくbefore_text,after_textをうまく使ってやってください。<br>
指定した日付の日記の内容を取得します。<br>
notWriteは何も書かれていなかった時、<br>
notExistは日記がなかった時に表示されます。<br>
```
"\![raiseplugin,DBdiary,OnGetBeautifulDiary,yyyymmdd,before_text,after_text,notWrite,notExist]"
```


## お借りしたもの
yaya.dll
[Releases · YAYA-shiori/yaya-shiori · GitHub](https://github.com/YAYA-shiori/yaya-shiori/releases)


## Other
このプログラムを利用することによるいかなる問題や損害に対して、私は責任を負いません。<br>
またゴースト等に同梱して配布していただいて構いません。<br>
main.uka内部を好きに書き換えてくれて構いません。<br>


## 小言
実際に作ってみたものの、raisepluginが使いづらく、<br>
プラグイン化のメリットはゴーストのデータを汚さないことぐらいでしょうか.<br>


## Author
[ambergon](https://twitter.com/Sc_lFoxGon)




