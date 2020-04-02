prb1.pdf: prb1.dvi 
	dvipdfmx -p a4 prb1.dvi
prb1.dvi: prb1.tex fig1_1.eps fig1_2.eps fig1_3.eps fig1_4.eps
	platex prb1.tex
fig1_1.eps: fig1_1.svgz
	inkscape -z -f fig1_1.svgz -E fig1_1.eps
fig1_2.eps: fig1_2.svgz
	inkscape -z -f fig1_2.svgz -E fig1_2.eps
fig1_3.eps: fig1_3.svgz
	inkscape -z -f fig1_3.svgz -E fig1_3.eps
fig1_4.eps: fig1_4.svgz
	inkscape -z -f fig1_4.svgz -E fig1_4.eps
