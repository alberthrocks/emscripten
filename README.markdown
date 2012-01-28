This is my fork of Emscripten to work on adding SDL functions for my project, JSWabbitemu, as well as additional functions outside the scope of my project.
Not too sure about license yet, but I think the code matters more, right? ;)

The important file is `src/library_sdl.js`, but you may see some testcases in `tests/`.
Enjoy! Please feel free to file bug reports, etc. as needed.

Original README follows...

Emscripten
==========

Emscripten is an LLVM-to-JavaScript compiler. It takes LLVM bitcode - which can be generated from C/C++, using llvm-gcc or clang, or any other language that can be converted into LLVM - and compiles that into JavaScript, which can be run on the web (or anywhere else JavaScript can run).

Links to **demos**, **tutorial**, **FAQ**, etc: <https://github.com/kripken/emscripten/wiki>

Main project page: <http://emscripten.org>

Emscripten is MIT licensed, see LICENSE.txt.

