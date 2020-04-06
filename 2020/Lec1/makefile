note1.pdf: note1.dvi
	dvipdfmx -p a4 note1.dvi 
note1.dvi: note1.tex arrow.eps identity.eps smul.eps vadd.eps iprod.eps eprod.eps components.eps vadd_cmp.eps eprod_xyz.eps\
       	fig1_1.eps fig1_2.eps fig1_3.eps fig1_4.eps fig1_2ans.eps\
       	fig1_5.eps fig1_6.eps fig1_7.eps fig1_8.eps
	platex note1.tex

arrow.eps: arrow.svgz
	inkscape -z -f arrow.svgz -E arrow.eps
identity.eps: identity.svgz
	inkscape -z -f identity.svgz -E identity.eps
smul.eps: smul.svgz
	inkscape -z -f smul.svgz -E smul.eps
vadd.eps: vadd.svgz
	inkscape -z -f vadd.svgz -E vadd.eps
iprod.eps: iprod.svgz
	inkscape -z -f iprod.svgz -E iprod.eps
eprod.eps: eprod.svgz
	inkscape -z -f eprod.svgz -E eprod.eps
components.eps: components.svgz
	inkscape -z -f components.svgz -E components.eps
vadd_cmp.eps: vadd_cmp.svgz
	inkscape -z -f vadd_cmp.svgz -E vadd_cmp.eps
eprod_xyz.eps: eprod_xyz.svgz
	inkscape -z -f eprod_xyz.svgz -E eprod_xyz.eps
fig1_1.eps: Prb1/fig1_1.svgz
	inkscape -z -f Prb1/fig1_1.svgz -E fig1_1.eps
fig1_2.eps: Prb1/fig1_2.svgz
	inkscape -z -f Prb1/fig1_2.svgz -E fig1_2.eps
fig1_2ans.eps: Prb1/fig1_2ans.svgz
	inkscape -z -f Prb1/fig1_2ans.svgz -E fig1_2ans.eps
fig1_3.eps: Prb1/fig1_3.svgz
	inkscape -z -f Prb1/fig1_3.svgz -E fig1_3.eps
fig1_4.eps: Prb1/fig1_4.svgz
	inkscape -z -f Prb1/fig1_4.svgz -E fig1_4.eps
fig1_5.eps: Prb1/fig1_5.svgz
	inkscape -z -f Prb1/fig1_5.svgz -E fig1_5.eps
fig1_6.eps: Prb1/fig1_6.svgz
	inkscape -z -f Prb1/fig1_6.svgz -E fig1_6.eps
fig1_7.eps: Prb1/fig1_7.svgz
	inkscape -z -f Prb1/fig1_7.svgz -E fig1_7.eps
fig1_8.eps: Prb1/fig1_8.svgz
	inkscape -z -f Prb1/fig1_8.svgz -E fig1_8.eps
