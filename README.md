# low_level


## Test:

`nasm assembly.asm -f elf64`
`gcc -c main.c -o main.o`
`gcc assembly.o main.o -o test -no-pie`
`./test`