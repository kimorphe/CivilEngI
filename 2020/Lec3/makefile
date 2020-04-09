note3.pdf: note3.dvi 
	dvipdfmx -p a4 note3.dvi
note3.dvi: note3.tex fig3_1.eps  fig3_2.eps fig3_3.eps fig3_4.eps fig3_5.eps
	platex note3.tex
fig3_1.eps: Figs/fig3_1.svgz
	inkscape -z -f Figs/fig3_1.svgz -E fig3_1.eps
fig3_2.eps: Figs/fig3_2.svgz
	inkscape -z -f Figs/fig3_2.svgz -E fig3_2.eps
fig3_3.eps: Figs/fig3_3.svgz
	inkscape -z -f Figs/fig3_3.svgz -E fig3_3.eps
fig3_4.eps: Figs/fig3_4.svgz
	inkscape -z -f Figs/fig3_4.svgz -E fig3_4.eps
fig3_5.eps: Figs/fig3_5.svgz
	inkscape -z -f Figs/fig3_5.svgz -E fig3_5.eps
