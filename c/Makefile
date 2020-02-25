.PHONY: all
all:
	clang Song.c

.PHONY: test
test: all
	./a.out > golden-master-current.txt
	diff golden-master.txt golden-master-current.txt
