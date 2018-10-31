  サブディレクトリ sty 内にある emath.sty などのファイルを
現在の emath.sty などに上書きします。

lsr を使用している環境では，コマンドプロンプトから
　　　　mktexlsr
を実行する必要があります。


前の訂正版からの主な変更：

emathC.sty
  \AppendOption

emathGps.sty
  TBwidth=..: 縦と横で同一に (BBS #13482)

emathPp.sty
  <zenkinsenOpt=..> を指定した場合の左右端点 (BBS #12535)
  \YGraph: <rightP> オプション：「範囲内」の判定 
    		"f(x)>=ymin" などとあるべきところが "f(x)>ymin" 
    		などとなっていたのを修正 (BBS #13541)

emathQf.sty
  \prPolynomial*: <syoubeki> オプションを有効に (BBS #13538)

EMxymatrix.sty
  pict2e 対応 (BBS #13547)

hako.sty
  \hak@: centermodetrue の場合，\ref{..} についての補正 (BBS #13578)
