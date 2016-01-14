書庫ファイル emathc??????.zip を解凍して得られる emath.sty などのファイルを
現在の emath.sty などに上書きします。
lsr を使用している環境では，コマンドプロンプトから
　　　　mktexlsr
を実行する必要があります。


前の訂正版からの主な変更：

emath.sty
  \dashtag: 見直し (BBS #12767)

emathPsb.sty
  EMpsrectbox, EMpsfbox: oval, shade オプションの併用 (BBS 12870)

emathPk.sty
  \iiitenretu*: <perl> オプションの処理 (BBS #12756)

emathPh.sty
  \Kurosikaku, \Kurosankaku, \Sirosankaku
    \@xyhosei の初期化など (BBS 12742)
  \Bunten: kuromaru, siromaru 局所化
  \EnkoToubun: <tatebou> オプション
  \emSankaku: <size=..> オプション

EMcolor.sty, EMrgbcolornam.def
  darkgray の定義修正

emathT.sty
  orikaesitabular, turntabular: orikaesitabular.sty として独立

pszahyou.sty
 \emSankaku: emathPh.sty の定義との互換

emathPs.sty
  \pssquare*: 塗りを \pscirc* と揃える

emathC.sty
  \Ifor: 初期値，終値に計算式を許容

emathW.sty, emathWs.sty
  引き算結果が負となることを許容 (BBS #12634)

emgyouretu.sty
  \pgyouretu: ネスト (BBS #12759)
