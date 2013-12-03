Optal
===========

Optal compiler
http://optal.ocamlpro.com/

## Dependencies:
 - menhir: http://gallium.inria.fr/~fpottier/menhir/
 - jsonm: http://erratique.ch/software/jsonm
 - uutf: http://erratique.ch/software/uutf

### Installing dependencies with opam
    $ opam install menhir jsonm uutf

## Compiling
    $ make -C src

## Test
    $ src/main test/gas.opl test/gas.json
