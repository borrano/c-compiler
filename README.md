# toy c-compiler based on KAIST Compiler Design course project.

- Usage: stack run -- -c Source [-q|--executable]
- Test: stack test compiles, runs and compares output with gcc-riscv output


### Todo: 

- register allocation: Add stack spilling .
- front end: Add error handling/messages:  If it encounters anything that are not supported, it gives an exception or produces wrong output.
- front end: fix typecasting rules: what to do when adding unsigned char with unsigned short
- tests: fix optimization tests   
- infra: port ir interpreter to haskell.  
- reimplement assembly generation and struct conversion parts (/irgen/structs.hs). 