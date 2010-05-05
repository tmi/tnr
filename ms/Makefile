love: metrSpc.dvi
	dvipdf metrSpc.dvi && rm metrSpc.dvi
metrSpc.dvi: metrSpc.tex mac.tex lec1.tex lec2.tex lec3.tex lec4.tex lec5.tex lec6.tex lec7.tex lec8.tex lec9.tex lec10.tex lec11.tex
	tex metrSpc.tex
arch: metrSpc.tex mac.tex lec1.tex lec2.tex lec3.tex lec4.tex lec5.tex lec6.tex lec7.tex lec8.tex lec9.tex lec10.tex lec11.tex
	tar -czf metrSpc.tar.gz metrSpc.tex mac.tex lec*.tex
clean:
	rm -f metrSpc.log metrSpc.tar.gz 
