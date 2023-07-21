all:
	ls *.xlsx | sed -e s/xlsx/md/g | xargs make

%.md: %.xlsx laboratory.py laboratory.md laboratory.ja.md
	python laboratory.py $*
