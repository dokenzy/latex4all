latex4all
=========

LaTeX 입문자를 위한 간단한 설명서

TODO
----

Writing a build script(SCon or Makefile)

Compile
--------

1. xelatex --shell-escape latex4all(3번)
2. texindy -L korean -I omega latex4all.idx
3. xelatex --shell-escape latex4all(2번)
