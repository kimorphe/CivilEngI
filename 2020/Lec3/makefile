all: note3.pdf prb3.pdf
note3.pdf: note3.dvi 
	dvipdfmx -p a4 note3.dvi
prb3.pdf: prb3.dvi 
	dvipdfmx -p a4 prb3.dvi
prb3.dvi: prb3.tex prb.eps
	platex prb3.tex
note3.dvi: note3.tex fig3_1.eps  fig3_2.eps fig3_3.eps fig3_4.eps fig3_5.eps \
	fig1.eps fig3.eps fig4.eps fig5.eps fig6.eps fig7.eps fig8.eps fig9.eps fig10.eps \
	fig11.eps fig12.eps fig13.eps fig14.eps fig15.eps fig16.eps
	platex note3.tex

prb.eps: Figs/prb.svgz
	inkscape -z -f Figs/prb.svgz -E prb.eps
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps
fig4.eps: Figs/fig4.svgz
	inkscape -z -f Figs/fig4.svgz -E fig4.eps
fig5.eps: Figs/fig5.svgz
	inkscape -z -f Figs/fig5.svgz -E fig5.eps
fig6.eps: Figs/fig6.svgz
	inkscape -z -f Figs/fig6.svgz -E fig6.eps
fig7.eps: Figs/fig7.svgz
	inkscape -z -f Figs/fig7.svgz -E fig7.eps
fig8.eps: Figs/fig8.svgz
	inkscape -z -f Figs/fig8.svgz -E fig8.eps
fig9.eps: Figs/fig9.svgz
	inkscape -z -f Figs/fig9.svgz -E fig9.eps
fig10.eps: Figs/fig10.svgz
	inkscape -z -f Figs/fig10.svgz -E fig10.eps
fig11.eps: Figs/fig11.svgz
	inkscape -z -f Figs/fig11.svgz -E fig11.eps
fig12.eps: Figs/fig12.svgz
	inkscape -z -f Figs/fig12.svgz -E fig12.eps
fig13.eps: Figs/fig13.svgz
	inkscape -z -f Figs/fig13.svgz -E fig13.eps
fig14.eps: Figs/fig14.svgz
	inkscape -z -f Figs/fig14.svgz -E fig14.eps
fig15.eps: Figs/fig15.svgz
	inkscape -z -f Figs/fig15.svgz -E fig15.eps
fig16.eps: Figs/fig16.svgz
	inkscape -z -f Figs/fig16.svgz -E fig16.eps

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
