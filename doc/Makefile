
HTMLDOCS = \
    dtd2html.html \
    dtd_pl.html \
    dtddiff.html \
    dtdtree.html \
    perlSGML.html \
    sgml_pl.html \
    stripsgml.html

textdoc:
	chmod 644 $(HTMLDOCS)
	lynx -dump dtd2html.html > dtd2html.txt
	lynx -dump dtd_pl.html > dtd_pl.txt
	lynx -dump dtddiff.html > dtddiff.txt
	lynx -dump dtdtree.html > dtdtree.txt
	lynx -dump perlSGML.html > perlSGML.txt
	lynx -dump sgml_pl.html > sgml_pl.txt
	lynx -dump stripsgml.html > stripsgml.txt
	chmod 644 *

