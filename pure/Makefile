all : Makefile-coq
	make VERBOSE=1 -f Makefile-coq

Makefile-coq : _CoqProject
	coq_makefile -f _CoqProject -o Makefile-coq

clean :
	make -f Makefile-coq clean
