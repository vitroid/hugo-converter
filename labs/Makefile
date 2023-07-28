DEST="/Users/matto/Library/CloudStorage/GoogleDrive-vitroid@gmail.com/My Drive/gitwork/chem-web/exampleSite/content/laboratory/"

all:
	ls *.xlsx | sed -e s/xlsx/md/g | xargs make

%.md: %.xlsx laboratory.py laboratory.md laboratory.ja.md
	python laboratory.py $*
	cp $*.md $*.ja.md $(DEST)
