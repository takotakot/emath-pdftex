1. emath??.sty $B$H$O(B
    $BCf3X!&9b9;$G?t3X$N%W%j%s%H$r:n$k:]$KI,MW$J5-9f!$(B
  $B4D6-$r=8$a$?%^%/%m=8$G$9!%(B
  $B$3$N%Q%C%1!<%8$O!$(Bemath $B%7%j!<%:$NE}9gHG$G$9!%(B
    (2005/11/03 $B8=:_$N:G?7%P!<%8%g%s$r=8$a$F$$$^$9!%(B)

2. $BA0Ds$H$J$k(B LaTeX $B$N%P!<%8%g%s(B
  LaTeX2e $B$rA0Ds$H$7$^$9!%(B

3. $B%$%s%9%H!<%k(B
 (1) emathfyymmdd.lzh (yymmdd $B$OG/7nF|$r<($9?tCMNs!K(B
   $B$r2rE`$7$FF@$i$l$k(B sty.lzh $B$r2rE`$7$^$9!#(B
   $B2rE`@h$O!$(BTeX $B$r%$%s%9%H!<%k$7$?%U%)%k%@$N2<$K(B texmf $B%U%)%k%@$,(B
   $B$"$k$O$:$G$9$,!$$5$i$K$=$N2<$K(B
      ...\texmf\tex\platex\misc\emath
   $B$H$$$&%U%)%k%@$r:n@.$7$F!$$=$NCf$K(B sty.lzh $B$r2rE`$7$^$9!#(B
 (2) $B@bL@=q$,(B doc.lzh $B$K$"$j$^$9$+$i!$(B
       ...\texmf\doc\emath
   $B$H$$$&%U%)%k%@$r:n@.$7!$$=$3$r2rE`@h$K;XDj$7$F$/$@$5$$!#(B
   $B$=$N7k2L!$$5$i$K2<$K(B
      b4yoko3
      emath
      ....
   $B$J$I$N%5%V%U%)%k%@$,:n@.$5$l$F!$$=$NCf$K(B
   $B;HMQ@bL@=q(B sample?.tex $B$J$I$,3JG<$5$l$^$9!%(B
 (3) pdf.lzh $B$K$O!$@bL@=q$N0lIt$r(B PDF $B7A<0$K$7$?$b$N$,4^$^$l$F$$$^$9!#(B
   doc.lzh $B$HF1$8$/(B
       ...\texmf\doc\emath
   $B$r2rE`@h$K;XDj$7$F2rE`$7$F$/$@$5$$!#(B

$B$J$*!$2rE`%=%U%H$N@_Dj$K$h$C$F$O>e5-$N$h$&$K$J$i$J$$$3$H$b$"$j$^$9!%(B
$B$=$N>l9g$O!$>e5-$N$h$&$J%U%)%k%@$r:n@.$7$F%U%!%$%k$r3JG<$7$F$/$@$5$$!%(B

   ($BCm#1(B) Unix $B7O$N(BOS (Mac OS X $B$r4^$`!K$G$4MxMQ$NJ}$O(B
              http://emath.s40.xrea.com/x/unix.htm
         $B$r$4Mw$/$@$5$$!#(B

  $B!JCm#2!K(Bls-R $B%U%!%$%k$r;HMQ$5$l$F$$$k>l9g$O!$99?7$r$*K:$l$J$/!#(B

4. $B$^$:$O!%!%!%(B
    $B$3$N%Q%C%1!<%8$NCf?4$O(B emath.sty $B$G$9!%(B
  $B$^$:$O!$(Bdoc\emath\emath $B$K$"$k(B sample.tex $B$r%?%$%W%;%C%H$7$F$_$F$/$@$5$$!%(B
  $B?^7A!&%0%i%UIA2h5!G=$O(B emathP.sty $B$,C4$C$F$$$^$9!%(B
        doc\emath\emathP $B$K$"$k(B sampleP.tex $B$r$4Mw$/$@$5$$!%(B
  $B%0%i%UIA2h$O(B perl $B$HO"7H$7$F9T$&(B emathPp.sty $B$,JXMx$G$9$,!$(B
  $B$=$l$K$D$$$F$O(B
        doc\emath\emathPp\samplepp.pdf
  $B$r$4Mw$/$@$5$$!#(B
  
5. $BI,MW$J%9%?%$%k%U%!%$%k$H$=$N:_=h(B
   $BI,MW$J%9%?%$%k%U%!%$%k$K$D$$$F=R$Y$^$9!%(B
   $B4pK\E*$J%Q%C%1!<%8$H$7$F!"(B
      amsmath, tools, graphics
   $B%Q%C%1!<%8$OI,?\$G$9!#(B

     $B$3$N$&$A!$(Bamsmath $B$O(B v 2.** $B$rA0Ds$H$9$k%3%^%s%I$,$$$/$D$+$"$j$^$9!#(B
   v 1.** $B$NJ}$O(B amsmath $B%Q%C%1!<%8$r%P!<%8%g%s%"%C%W$7$F$/$@$5$$!#(B

   $B$=$NB>$K!"(B
      epic.sty, eepic.sty
      eclarith.sty
   $B$,I,MW$G$9!%$3$l$i$N:_=h$O!$Nc$($P<!$NDL$j$G$9!%(B

  (1) epic.sty, eepic.sty
        CTAN:macro/latex/contrib/other/
  (2) eclarith.sty
        http://mechanics.civil.tohoku.ac.jp/~bear/bear-collections/index-j.html

  (3) Perl $B$HO"7H$7$F%0%i%U$rIA2h$9$k5!G=$r$4MxMQ$N>l9g$O!$(B
        ...\texmf\doc\emath\emathPp\samplepp.pdf
      $B$r$4Mw$/$@$5$$!#(B

6. emath $B%7%j!<%:$N35MW(B
    $B3F%9%?%$%k%U%!%$%k$N$*$b$J;HMQL\E*$r5-=R$7$^$9!%(B
      emath.sty       $BA4HL(B
      emathP.sty      $B?^7A!&%0%i%UIA2h(B
      $B!!!!$3$N%9%?%$%k%U%!%$%k$O$D$.$N#5$D$KJ,3d$5$l$F$$$^$9!#(B
      $B!!!!!!!!J?LL:BI8$r07$&(B              emathPh.sty
      $B!!!!!!!!(Bx,y$B:BI8$NC10LD9$r0[$K$9$k(B   emathPxy.sty
      $B!!!!!!!!6u4V:BI8$r07$&(B              emathPk.sty
      $B!!!!!!!!(BPerl $B$H$NO"7H=hM}$r$9$k(B     emathPp.sty
      $B!!!!!!!!:nI=4D6-(B hyou, Hyou $B$r07$&(B  emathT.sty
      emathPs.sty     PostScript $B$GIA2h$9$k(B
      emathAe.sty     $B2rEz$r4,Kv$K=8$a$k(B
      emathB.sty      $BJ,?t7W;;(B
      emathBk.sty     $BJ#?t%Z!<%8$K$o$?$k0O$_OH$r:n$k(B breakbox$B4D6-$N(B
                      $B%P%j%(!<%7%g%s$r$$$/$D$+=8$a$F$"$j$^$9!#(B
                      $B2rEzIt$rFsCJAH$K$7$F!$1&B&$KCm<a$r$D$1$k%9%?%$%k$r(B
                      $BA@$C$F$$$^$9!#(B
      emathBt.sty     $BK\J8$HK5Cm$N4V$K=D7S@~$rF~$l$^$9(B
      emathC.sty      $B7W;;$r$9$k%5%V%^%/%m(B
      emathE.sty      enumerate $B4D6-$N3HD%(B
      emathFx.sty     txfonts $B$J$I$GMQ0U$5$l$F$$$k%U%)%s%H$N$D$^$_?)$$(B
      emathHe.sty     $BJ?J}:,$N7W;;(B
      emathK.sty      $B%+%J$K$h$kHV9fIU$1(B
      emathN.sty      $BN.$l?^IA2h(B
      emathPa.sty     $B<P8r:BI87O(B
      emathR.sty      $BJ#?t$N(B LaTeX $BJ8=q%U%!%$%k$rE}9g(B
      emathT.sty      $BNsI}$r;XDj$7$?I=$r:n@.$9$k4D6-(B hyou, Hyou
                      $B!JA}8:I=$rG0F,$K$*$$$F$$$^$9!K(B
      emathW.sty      $B=D=q$-$N=|K!(B
      emathZ.sty      $B<y7A?^IA2h(B
      b4yoko3.sty     $B9M::MQ(B B4$B2##3CJAH(B
      (b4yoko4)
      hako.sty        $B%;%s%?!<;n83$N2rEzOH!JHV9fIU$1$HAj8_;2>H(B)
      (arhako.sty         $BLV3]$1!K(B
      itembbox.sty    $B>e2<8+=P$7$D$-7S@~%\%C%/%9(B
      itembkbx.sty    $BJ#?t%Z!<%8$K$o$?$k8+=P$7$D$-7S@~%\%C%/%9(B
      showexample.sty TeX$B%=!<%9$H%?%$%W%;%C%H$7$?7k2L$NBPHf!JBPLu(B TeX$B!K(B
           $B%U%!%$%kL>$r(B showex.sty $B$H$7$?$b$N$b$"$j$^$9!#FbMF$OF10l$G$9!#(B
      showProg.sty    $BBPLu(BTeX $B$G!$%=!<%9It$K25It;a$N(B program.sty $B$r;H$&!#(B

7. emath $B$N;HMQNc(B
    emath??.sty $B$r;HMQ$7$?J8=q$NNc$O(B
      http://emath.s40.xrea.com/
  $B$G8x3+$7$F$$$^$9!%(B
  $BL\<!$N(B
      $B;HMQNc(B
  $B$+$i$?$I$l$^$9!%(B
    $BBg3XF~;n%;%s%?!<;n83$NLdBj(B    
    $BBg3XF~;nLdBj=8!JBg3XJL!&J,LnJL(B)
    $B9bEy3X9;F~;nLdBj(B
    $BCf3X9;F~;nLdBj(B
    $B<x6HMQ%W%j%s%H(B
    $BDj4|9M::$NLdBj!&2rEz(B
    emath $B$N%3%^%s%I$r;HMQ$9$k9V:B(B
  $B$J$I$,$"$j$^$9!%(B

8. $B%5%]!<%H$J$I(B
    $B$3$N%Q%C%1!<%8$N%5%]!<%H$O(B 
      http://emath.s40.xrea.com/ $B$N7G<(HD(B
    $B$G9T$C$F$$$^$9!%(B
    $B%P%0Js9p!$<ALd!$Ds0F$J$I$O$=$A$i$K$*4j$$$7$^$9!%(B

    $B$^$?!$:Y$+$$%P!<%8%g%s%"%C%W$O(B
      http://emath.s40.xrea.com/
    $B$N!V=$@5%Q%C%/!W%Z!<%8$G8x3+$7$F$$$-$^$9!%(B

  $B$3$N%Q%C%1!<%8$K4^$^$l$k%U%!%$%k$NCx:n8"$J$I$K$D$$$F$O(B
      http://emath.s40.xrea.com/
  $B$N%5%]!<%H%Z!<%8$r$4Mw$/$@$5$$!#(B
  
                                                $BBg7'!!0l90(B
                                                       tDB
