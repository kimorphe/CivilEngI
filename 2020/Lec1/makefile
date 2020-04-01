note1.pdf: note1.dvi
	dvipdfmx note1.dvi 
note1.dvi: note1.tex arrow.eps identity.eps smul.eps vadd.eps
	platex note1.tex

arrow.eps: arrow.svgz
	inkscape -z -f arrow.svgz -E arrow.eps
identity.eps: identity.svgz
	inkscape -z -f identity.svgz -E identity.eps
smul.eps: smul.svgz
	inkscape -z -f smul.svgz -E smul.eps
vadd.eps: vadd.svgz
	inkscape -z -f vadd.svgz -E vadd.eps
