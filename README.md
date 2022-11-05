# OfficialTgs
Fully Made Programming Language
**Permissioned By [Tsoding](https://gitlab.com/tsoding/)**
**[Tsoding](https://gitlab.com/tsoding/porth/-/blob/master/LICENSE)**
![LogoTGSFinals](https://user-images.githubusercontent.com/112824573/200144100-a382077c-a0a3-4ee4-8844-b3348d166939.jpg)

## Info
- [x] Self compiling
- [x] Turing Complete
- [x] Close to C 

### Setup Your Environment For TGSharp

**'-c' is used for compiling and building the source code.**
**'-c' and '-r' together compile/build and run the executable.**

```
NOTICE: Get the executable from libraries! Called: 'tgs'

$ ./tgs -c <./file.tgs>
$ ./tgs -c -r <./file.tgs>
```

### Some examples for you to run!

**Hello World**
```
include "stdlib.tgs"

proc main in
   "Hello, World!\n" puts
end
```

# Str Info

- `\n` - New Line
- `\r` - creturn
- `\\` - backslash
- `\"` - dubq
- `\'` - sinq

*Most of these types are only allowed to be used in no other than strings.
For example '"Hello, World\n"' and so on...*
A string next to a letter 'c' like: '"Hello, World"c', means to make it a CSTR.

# How about Ascii?

**Every letter is used in as a ascii type, and ascii type is a letter. Such as, "'E' print"... Print: Used for Number literals not str..., and so E is a code type in ascii, which is 69 since it's a Uppercase E.**

# STORE

- '!' + '32' or '64' or '16' or '18' == store byte
- '@' + '32' or '64' or '16' or '18' == load byte
- convert(int) == converting from a integer element to another
- convert(bool) == converting from a boolean element to another
- convert(ptr) == converting from a pointer element to another

# System Calls/Args

System calls or 'syscall'
Are listed from [0-6]...
- `syscall 1`: returns with 1 arg.
- `syscall 2`: returns with 2 args.
- `syscall`  : returns with 3/default args. (recommended for most cases)
- `syscall 4`: returns with 4 args.
- `syscall 5`: returns with 5 args.
- `syscall 6`: returns with 6 args.
ARGS:
['argv'] & ['argc']
- `argc`: a argument that uses a integer
- `argv`: a argument that uses a pointer


### Types

- `int`: An 64 bit integer.
- `bool`: An variable with the value "true or false".
- `ptr`: An pointer value
- `addr`: An Address, Position, Or the type of an procedure.
