#
# bash scripts prepare Makefile
#
# ShVV 2018-01-12
#


#FIXME: add install target for all the scripts in here

src = \
	md2html \

out = \
	md2html.html \

all: $(out)


md2html.md: md2html
	touch $@

md2html.html: md2html.md
	./md2html $? > $@


clean:
	-rm $(out)

#EoF
