TAR = $(wildcard *.html)

.PHONY: all clean

all: $(TAR)

%.html : %.lagda.md %.md ../styles/default.css ../elements/header.html ../elements/footer.html
	agda --html --html-highlight=code $<
	mv html/$(word 2, $^) $(word 2, $^)
	rm -rf html
	pandoc $(word 2, $^) -s --mathjax -o $@ -c ../styles/default.css -B ../elements/header.html -A ../elements/footer.html

clean:
	rm -f $(TAR)