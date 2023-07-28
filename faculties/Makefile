DEST="/Users/matto/Library/CloudStorage/GoogleDrive-vitroid@gmail.com/My Drive/gitwork/chem-web/exampleSite/content/faculty/"

all:
	ls *.xlsx | sed -e s/xlsx/ja.md/g | xargs make

%.ja.md: %.xlsx faculty.py faculty.ja.md faculty.en.md
	python faculty.py $*
	cp $*.en.md $*.ja.md $(DEST)
