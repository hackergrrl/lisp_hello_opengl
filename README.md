# Common Lisp + OpenGL: Hello World

A simple lisp file that runs a tiny OpenGL program that you can make live edits
to using Emacs and SLIME.

## Requirements

1. Emacs
2. SLIME (Emacs package; included in Emacs nowadays I think)
3. Quicklisp (Common Lisp package manager)

## Usage

1. Open `hello.lisp` in emacs
2. Run `slime-init` in emacs
3. Run `(ql:quickload "sdl2")` and `(ql:quickload "cl-opengl")` in the newly
   created `CL-USER` repl. They'll be loaded if on your computer already, or
   downloaded if not.
4. `C-c C-k` to compile + load the file
5. run `(main)` in the REPL to begin
6. make changes to the source file (like vertex colours) and type `C-c C-k`
   again to live reload

