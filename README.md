# f03pthread
Proof of concept of an interface to POSIX Threads (`pthreads`) for modern
Fortran (2003, 2008, 2018).

## Build
Use the Makefile to build the interface:
```
$ make pthread
```
Or run your favourite Fortran compiler directly:
```
$ flang -c pthread.f90
```

## Examples
Please check the directory `examples` for some demos:

* **simple** runs a routine inside a `pthread`.

Compile the examples with:
```
$ make <name>
```

## Licence
ISC