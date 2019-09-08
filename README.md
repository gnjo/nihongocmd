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
名詞を動詞化する事で、短い命令を作る事が出来る。
名詞を動詞化する規則が、にしを命令である。
例えば、出力、
出力にして
出力して
出力をして
目的語は、引数の可能性があるが、目的語が省略される場合、命令のみで良く、解釈しやすい。

せいしして、は命令の末尾を示す、し、が名詞の末尾と重複する為、解釈し難い。
三種類の末尾を用意し、発声者を教育すれば厳密に判断可能である。
静止命令の場合、せいしをして。せいしにして、は解析的に精度が高い。
~~~~
~~~
１２３４５．８＜ヤー、整数にして、出力して、静止をして
；１２３４５
~~~
~~~
番と全体は使用禁止である。変数操作に使う。
結果｜１０．５｜１＊１０＜ヤー、二番を整数にして、三番を計算して、全体を表示して、以上。
；結果１００
~~~

~~~~
発想原点
日本語の熟語は、動詞と目的語を内包している。
熟語は、名詞であるが、厳密には名詞的である。
熟語を動詞化すれば、少ない時間で発声出来る。
関数は、命令と引数から成立している。
関数は、動詞と目的語から成立していると、日本語的に置き換える事が、まま、出来る。
１．動詞と目的語を判読できれば、関数を実行できる。

目的語の番号が判れば、厳密に、引数として抜き出せる。
番号だけではなく、集合として全体を引数として実行する場面は多い。
２．引数の指示番号を全体を指示する事が出来れば、引数を厳密にし、関数を実行できる。

以上から
「にしを番全」命令を定義出来る。

例示
結果｜１０．５｜１＊１０＜ヤー、二番を整数にして、三番を計算して、全体を表示して、以上。
；結果１００

細部
「にしを」は動詞化する規則変化である。名詞の「出力」を動詞化する場合を例示する。
出力にして
出力して
出力をして

「番全」は関数実行時に、引数を正確に渡す為に必要である。関数実行を別言語で示す。
引数１｜引数２｜引数３＜ヤー、一番を出力して、以上。
//console.log('引数１')
引数１｜引数２｜引数３＜ヤー、全体を出力して、以上。
//console.log('引数１','引数２','引数３')

発声学的に必要かは不明だが、命令の先頭と末尾を指示する、開始、終了文句を蛇足として含めている。
主語を示す「は」は、要約語であろうが、今の所一つだけ。「にしを番全命令は」である。
~~~~
