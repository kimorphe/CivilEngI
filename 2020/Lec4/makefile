all: note4.pdf prb4.pdf
note4.pdf: note4.dvi 
	dvipdfmx -p a4 note4.dvi
note4.dvi: note4.tex fig4_1.eps fig4_2.eps fig1.eps fig2.eps
	platex note4.tex

prb4.pdf: prb4.dvi 
	dvipdfmx -p a4 prb4.dvi
prb4.dvi: prb4.tex prb.eps
	platex prb4.tex

fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps
fig4_1.eps: Figs/fig4_1.svgz
	inkscape -z -f Figs/fig4_1.svgz -E fig4_1.eps
fig4_2.eps: Figs/fig4_2.svgz
	inkscape -z -f Figs/fig4_2.svgz -E fig4_2.eps
prb.eps: Figs/prb.svgz
	inkscape -z -f Figs/prb.svgz -E prb.eps
