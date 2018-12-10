# About this repository

This is a fork of the [mercurial repository of dsharp on bitbucket](https://bitbucket.org/haz/dsharp).
Rationale:
- I want to make some minor changes to the program's interface,
- being a git repository makes it easier to include it as a submodule
  in my [Perl 6 dsharp module](https://github.com/taboege/p6-SAT-Counter-dsharp).

The history of the mercurial repository has been pulled in using [fast-export](https://github.com/frej/fast-export)
but author information is incomplete, e.g. "haz" missing an email in the
mercurial repository, which is a mandatory field in git commits.

Below is the README of the upstream repository.

-------

# DSHARP version 1.0

If you would like the solver to use infinite precision numbers for the counting,
you must have the GMP library (libgmp-dev) installed. To use the version with GMP,
copy the Makefile_gmp to Makefile. Otherwise, copy Makefile_nogmp to Makefile and
proceed normally.

To compile this version of DSHARP simply run

```
make
```

Please cite using the following:

```
@inproceedings{Muise2012,
    author = {Muise, Christian and McIlraith, Sheila A. and Beck, J. Christopher and Hsu, Eric},
    booktitle = {Canadian Conference on Artificial Intelligence},
    title = {{DSHARP: Fast d-DNNF Compilation with sharpSAT}},
    keywords = {sat, knowledge compilation},
    year = {2012}
}
```
