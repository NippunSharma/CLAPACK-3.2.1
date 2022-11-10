This repo contains a modified version of the CLAPACK-3.2.1 library,
that allows the library to build with emscripten (emcc).

Just running `make` in the root directory should work. The build process
will emit the blas (in root directory), libf2c (in F2CLIBS subdirectory) and
lapack (in root directory) libraries (.a files) that can be used to link with your
designed programs and run on the web (using web assembly).
