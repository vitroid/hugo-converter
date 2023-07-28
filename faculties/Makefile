DEST="/Users/matto/Library/CloudStorage/GoogleDrive-vitroid@gmail.com/My Drive/gitwork/chem-web/exampleSite/content/faculty/"

all:
	ls *.xlsx | sed -e s/xlsx/md/g | xargs make

%.md: %.xlsx faculty.py faculty.ja.md faculty.md
	python faculty.py $*
	cp $*.md $*.ja.md $(DEST)
