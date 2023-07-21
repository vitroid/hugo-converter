all:
	ls *.xlsx | sed -e s/xlsx/md/g | xargs make

%.md: %.xlsx faculty.py
	python faculty.py $*
