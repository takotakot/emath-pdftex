$B9M::MQ;f$N=q<0$G!$#B#42#$NB?CJAH$r$9$k$?$a$N%9%?%$%k%U%!%$%k$G$9!%(B

  $BFsCJAH$K$D$$$F$O!$(Btwocolumn $B%*%W%7%g%s$rMQ$$$k$N$,4JC1$G$9!%(B
pLaTeX2e $B$K$J$C$F$+$i!$HGLL$,69$/$J$C$F$$$^$9$N$G!$(B
$B$=$NE@$r=$@5$7$?$N$,F1:-$N(B sample0.tex $B$G$9!%(B

  $B$5$F!$;0CJ!&;MCJ$J$j$^$9$H!$(Bmulticol $B%Q%C%1!<%8$rMQ$$$kJ}K!$,$"$j$^$9$,!$(B
$B?t3X$N9M::$N$h$&$KM>Gr$,B?$$>l9g$OD4@0$,LLE]$G$9!%(B
$B$H$$$&$3$H$G!$(B
    $B;0CJAHMQ$N%9%?%$%k(B b4yoko3.sty
    $B;MCJAHMQ$N%9%?%$%k(B b4yoko4.sty
$B$r:n$C$F$_$^$7$?!%(B

  $B;HMQK!$NBg;(GD$J@bL@$r$7$^$9!%(B

step 1. $B9M::$N%?%$%H%k$r(B  \testname $B$N0z?t$H$7$F5-=R$7$^$9!%(B
  $B!JNc!K(B \testname{\ 1$B3XG/!X?t3X(BI$B!YFs3X4|Cf4V9M::(B\ \ 1998.10.22($BLZ(B)\ }

step 2. $B0lKg$N%7!<%H$NFbMF$r(B sheet $B4D6-Fb$K5-=R$7$^$9!%(B
    step 2-1 $B0lCJL\$NFbMF$r(B column $B4D6-Fb$K5-=R$7$^$9!%(B
             $B$3$N4D6-$O!$<B<A(B enumerate $B4D6-$G$9$+$i!$(B
             $BBgLd$N$O$8$a$K(B \item $B$r5-=R$7$^$9!%(B
    step 2-2 $BFsCJL\$r(B column $B4D6-Fb$K5-=R$7$^$9!%(B
    step 2-3 $B;0CJL\$G$9!%(B

$B$9$J$o$A(B

    \begin{sheet}
        \begin{column} 
            \item aaa 
        \end{column}
        \begin{column} 
            \item bbb
        \end{column}
        \begin{column} 
            \item ccc 
        \end{column}
    \end{sheet}

$B$H$$$&9=@.$K$J$j$^$9!%(B
  $B$J$*!$#1$D$NNs(B(column)$B$KJ#?t$NLdBj$rF~$l$k$H$-$O!$$=$N4V3V$r6u$1$k$N$K(B
  	(1) \vspace{5cm} $B$J$I$H6uGr$ND9$5$r;XDj$9$kJ}K!(B
$B$H(B
	(2) \vfill $B$G6QEy3d$9$kJ}K!(B
$B$N#2$D$NJ}K!$,$"$j$^$9!%(B

$B>\$7$/$O!$0J2<$N%5%s%W%k%U%!%$%k$r$4Mw$/$@$5$$!%(B

    sample0.tex twocolumn $B%*%W%7%g%s$rMQ$$$?FsCJAH$N%5%s%W%k(B

    sample1.tex $B;0CJAH$N%5%s%W%k(B
    sample2.tex                 $B!JJ#?tKg!K(B
    sample3.tex                 $B!JN>LL0u:~!K(B
    sample4.tex $B;0CJAH$N<BNc(B
    sample5.tex                 $B!J2rEz$rN"LL$K0u:~$9$k<BNc!K(B

    sample6.tex $B;MCJAH$N%5%s%W%k(B

    sample7.tex $B=D4V3V$r(B \vfill $B$G6QEy3d(B
