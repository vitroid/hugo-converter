DEST="/Users/matto/Library/CloudStorage/GoogleDrive-vitroid@gmail.com/My Drive/gitwork/chem-web/exampleSite/content/laboratory/"

all:
	ls *.xlsx | sed -e s/xlsx/ja.md/g | xargs make

%.ja.md: %.xlsx laboratory.py laboratory.en.md laboratory.ja.md
	python laboratory.py $*
	cp $*.en.md $*.ja.md $(DEST)
