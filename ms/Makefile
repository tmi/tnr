love: metrSpc.dvi
	dvipdf metrSpc.dvi && rm metrSpc.dvi
metrSpc.dvi: metrSpc.tex mac.tex lec1.tex lec2.tex lec3.tex lec4.tex lec5.tex lec6.tex lec7.tex
	tex metrSpc.tex
arch: metrSpc.tex mac.tex lec1.tex lec2.tex lec3.tex lec4.tex lec5.tex lec6.tex lec7.tex
	tar -czf metrSpc.tar.gz metrSpc.tex mac.tex lec1.tex lec2.tex lec3.tex lec4.tex lec5.tex lec6.tex lec7.tex
clean:
	rm -f metrSpc.log metrSpc.tar.gz 
