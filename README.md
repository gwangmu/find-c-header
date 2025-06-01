# C Header Finder

Find a given function's header (in the default search directory).

## Requirement

 - `clang`: any `clang` will do. Just install it. (e.g., `apt install clang`)

## Usage

 0. (Optional) Create a cache.

```
$ ./find_header cache
```

 1. Query a function name.

```
$ ./find_header find <func_name>
```

## Example

```
$ ./find_header cache
info: updating cache...                                                                                                                                                      
info: found 7171 header(s).
...
info: total 7171 header(s) updated.

$ ./find_header find prinf
info: symbol 'printf' found at '/usr/include/stdio.h'.
```
