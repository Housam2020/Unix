

System: xA.o xB.o xC.o x.c

	gcc -o System x.c xA.o xB.o xC.o


xB.c: xA.c

	tr "A" "B" < xA.c > xB.c

xC.c: xA.c

	tr "A" "C" < xA.c > xC.c

xA.o: xA.c

	gcc -c xA.c
xB.o: xB.c
	gcc -c xB.c
xC.o: xC.c
	gcc -c xC.c



