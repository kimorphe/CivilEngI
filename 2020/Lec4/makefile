note4.pdf: note4.dvi 
	dvipdfmx -p a4 note4.dvi
note4.dvi: note4.tex fig4_1.eps fig4_2.eps
	platex note4.tex
fig4_1.eps: Figs/fig4_1.svgz
	inkscape -z -f Figs/fig4_1.svgz -E fig4_1.eps
fig4_2.eps: Figs/fig4_2.svgz
	inkscape -z -f Figs/fig4_2.svgz -E fig4_2.eps
