# My CV

environment:

Texlive 2012/2013

use xelatex to compile (pdflatex also works, but latex/dvipdfmx will make the hyperlink invalid):

xelatex caolei_cv.tex

# My CV -- Chinese version

environment:

Texlive 2013/2014

1. Need to configure Adobe font first...

1. commented out line 94 and 95 of the template resumecls.cls under $TexLiveInstallPath/2014/texmf-dist/tex/xelatex/resumecls, in order to prevent printing "Last modified" in the last line of my CV.

1. use xelatex to compile:

	```bash
	xelatex caolei_cv_20141130_cn.tex
	``` 

1. compile error in cygwin: I can't write on file 'xxx.pdf' but OK in Windows native cmd.exe
