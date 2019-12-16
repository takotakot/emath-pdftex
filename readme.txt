  サブディレクトリ sty 内にある emath.sty などのファイルを
現在の emath.sty などに上書きします。

lsr を使用している環境では，コマンドプロンプトから
　　　　mktexlsr
を実行する必要があります。


前の訂正版からの主な変更：



emathBk.sty v 0.52   2019/07/02
    \smash に \hbox を被せる（aminophenさんのご教示による BBS #13851)

emathMw.sty v 0.49 2019/07/02
    \MigiRangai内では，局所的に \let\leavevmode@ifvmode\relax (BBS #13839)

emathEy.sty v 0.38 2019/07/01
    betaenumeratem環境

emathPh.sty v 4.92 2019/06/01
    \Kuromaru,\Siromaru: \DeclareRobustCommand とする

kaitouwaku.sty 0.03 2019/05/30
  \syoumon@migikei

emathPh.sty v 4.91 2019/03/12
    \Pzyuusin: 多角形の重心

emathBk.sty v 0.50 2019/03/30
  \breakbox 保留(BBS #13716)

EMfbox.sty v 0.76 2019/03/21 
   \rectbox: Underfull \hbox への対応 (BBS #13713)

emathWfp.sty v 0.01 2019/01/27 
   \Pzyohou: \[ \] を外し，array に [t]オプション (BBS #13673)


emathWp.sty v 0.02 2019/01/27 
    \Pzyohou: \[ \] を外し，array に [t]オプション (BBS #13673)

emathGps.stv 0.36 2019/01/24
    medlnopt=..: メディアン線に対する修飾（センター）

emathLb.sty 0.28 2019/01/10
  \writeLabel: \mbox{}を挿入 (BBS #13661)

emathW.sty 0.42 2018/12/23
  \gozyohou: 戻り値の定義を局所的に \xdef --> \edef (BBS #13656)

