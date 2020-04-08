note2.pdf: note2.dvi 
	dvipdfmx -p a4 note2.dvi
note2.dvi: note2.tex fig1.eps fig2_1.eps fig2_2.eps fig2_3.eps fig1.eps fig2.eps fig3.eps
	platex note2.tex
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps

fig2_1.eps: Figs/fig2_3.svgz
	inkscape -z -f Figs/fig2_1.svgz -E fig2_1.eps
fig2_2.eps: Figs/fig2_2.svgz
	inkscape -z -f Figs/fig2_2.svgz -E fig2_2.eps
fig2_3.eps: Figs/fig2_3.svgz
	inkscape -z -f fig2_3.svgz -E fig2_3.eps
