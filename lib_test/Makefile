CRUNCH = ../main.native
PKGS   = cstruct,lwt,mirage-types,io-page-unix

all:
	$(CRUNCH) t1 -o t1.ml
	ocamlfind ocamlopt -package $(PKGS) -c t1.mli t1.ml

clean:
	rm -rf t1.ml t1.mli t1.cmx t1.cmi t1.cmo t1.o
	rm -rf *~
