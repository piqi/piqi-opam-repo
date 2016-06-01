**THIS REPOSITORY IS DEPRECATED**

To install development versions of piqi and piqilib use opam pinning instead:


    opam pin add --dev-repo piqi
    opam pin add --dev-repo piqilib


**OLD README:**

This is an [OPAM](http://opam.ocaml.org/) repository for the development
(`master`) branches of [piqi/piqilib](https://github.com/alavrik/piqi) and
[piqi-ocaml](https://github.com/alavrik/piqi-ocaml).

Usage
-----

To install the latest development version of Piqi for OCaml:

    opam repo add piqi git://github.com/piqi/piqi-opam-repo.git

    opam install piqi

The `master` version should be picked by OPAM automatically.

Note that the latest stable Piqi version can be installed using the official
[OPAM repository](https://github.com/ocaml/opam-repository) by running just

    opam install piqi
