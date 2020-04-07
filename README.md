# Coq Issue 12043

To reproduce the behavior [here](https://github.com/coq/coq/issues/12043), simply run `make`.

The behavior will disappear if one renames the module in `Theory/Foo.v` to `Module Bar` or any module name not matching `Foo` (don't forget to adjust `Theory/Extrac.v` accordingly.)

Tested with Coq 8.11.
