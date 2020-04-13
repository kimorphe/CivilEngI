note2.pdf: note2.dvi 
	dvipdfmx -p a4 note2.dvi
note2.dvi: note2.tex fig1.eps fig2_1.eps fig2_3.eps \
	fig1.eps fig2.eps fig3.eps fig4.eps fig5.eps fig6.eps fig7.eps fig8.eps fig9.eps
	platex note2.tex
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps
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
