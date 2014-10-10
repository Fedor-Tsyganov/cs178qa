obj = countThrees.o readInt32BitLE.o readInt32BitLE.h
a.out : $(obj)
	g++ -o a.out $(obj)
countThrees.o : countThrees.c
	g++ -c countThrees.c
readInt32BitLE.o : readInt32BitLE.c
	g++ -c readInt32BitLE.c
