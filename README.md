```sh
opam switch create ./ ocaml-base-compiler.4.06.1
# will fail to build msgpck.
rm dune-project
opam reinstall msgpck
# now it works
git checkout -- dune-project
# now it fails again?
```
