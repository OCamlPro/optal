Optal
===========

Optal compiler
http://optal.ocamlpro.com/

## Dependencies:
 - menhir: http://gallium.inria.fr/~fpottier/menhir/
 - jsonm: http://erratique.ch/software/jsonm
 - uutf: http://erratique.ch/software/uutf

### Installing dependencies with opam
    $ opam install ocp-build menhir jsonm uutf

## Compiling
    $ ocp-build -init

## Test
    $ _obuild/optal/optal.asm test/gas.opl test/gas.json
