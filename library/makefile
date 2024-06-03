TAR = $(wildcard *.html)

.PHONY: all clean

all: $(TAR)
	 make -C philosophy

%.html : %.lagda.md %.md ../styles/default.css ../elements/header.html ../elements/footer.html
	agda -i .. --html --html-highlight=code $<
	mv html/library.$(word 2, $^) $(word 2, $^)
	rm -rf html
	sed -i -e 's#href="library.philosophy.#href="library/philosophy/#g' $(word 2, $^)
	pandoc $(word 2, $^) -s --mathjax -o $@ -c ../styles/default.css -B ../elements/header.html -A ../elements/footer.html

clean:
	rm -f $(TAR)