This is an OPAM repository for development branches of
[Piqi](https://github.com/alavrik/piqi).

[OPAM](http://opam.ocamlpro.com/) is a package manager for OCaml.

Stable Piqi versions starting from `v0.6.0` will be submitted to the official
[OPAM repository](https://github.com/OCamlPro/opam-repository).

## Installing Piqi using OPAM

1. Add this repository as a _remote_

```
opam remote add piqi git://github.com/alavrik/piqi-opam-repo.git
```

2. After that, run

```
opam install piqi
```

This command will install the latest development version of Piqi, including
`piqi` and `piqic` executables and piqi libraries for OCaml.

The previous stable Piqi 0.5.7 release can be also installed via OPAM. To
install it, run

```
opam install piqi.0.5.7
```
