### nihongocmd
thinking the command lang nihongo

### command 
command head　＞命令：引数１：引数２：引数３：引数４：引数５；
~~~~
＞ア：「あいうえを」
~~~~
values　＄あいうえを
~~~~
＄あ：引数１：引数２
~~~~
return value ＄＄
~~~
＄あ：「あいうえを」
＄＄
~~~
string head 「」
~~~~
「あいうえを。かきくけこ。
さしすせそ」
~~~~
comment out　；
~~~~
；これより後ろは命令として解釈しない。
~~~~
string or number
~~~~
＄あ：「１２３４５」；文字列
＄い：１２３４５；数字
~~~~
multi string
~~~~
「あいうえを
かきくけこ
さしすせそ
わおん」
＄あ：＄＄；変数あ、に代入
~~~~
intercept value on string　％＄あ％
~~~~
「あいうえを」
＄あ：＄＄
「％＄あ％かきくけこ」
~~~~
console log　＞＄あ
~~~~
「あいうえを」
＄あ：＄＄
＞＄あ；　或いは、＞＄＄
；この命令は、以下の様に内部変更され、等価である。
＞ログ：＄あ
~~~~
mathmatics　＝
~~~~
＝３＋２
；＄＄は５
~~~~

### にしを命令
変数優先型で、末尾に変換命令を付ける。
~~~~
目的語は、引数の可能性があるが、目的語が省略される場合、命令のみで良く、解釈しやすい。
~~~~
~~~
１２３４５．８＜やあ、整数にして、出力して、静止をして
；１２３４５
~~~


