note2.pdf: note2.dvi 
	dvipdfmx -p a4 note2.dvi
note2.dvi: note2.tex fig2_1.eps fig2_2.eps fig2_3.eps
	platex note2.tex
fig2_1.eps: fig2_1.svgz
	inkscape -z -f fig2_1.svgz -E fig2_1.eps
fig2_2.eps: fig2_2.svgz
	inkscape -z -f fig2_2.svgz -E fig2_2.eps
fig2_3.eps: fig2_3.svgz
	inkscape -z -f fig2_3.svgz -E fig2_3.eps
