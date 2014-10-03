obj=ServerCountThrees.o readInt32BitLE.o readInt32BitLE.h

test : moveobjs movebin
	./myserver
moveobjs : createdir
	mv *.o ./objects
movebin : createbin
	mv *.c ./bin
createbin : compile
	mkdir ./bin
createdir : compile
	mkdir ./objects
compile : $(obj)
	g++ -o myserver $(obj)
