### Golang Notes

#### Execution vs compilation Speed
- Compilation speed - The time it takes to translate source code into machine code. Compilation happens at build time.
- Execution speed - The time it takes to run a compiled program. Execution happens at runtime.

#### Compiled vs Interpreted languages
- **Compiled** - The program is converted directly to machine code that a processor can execute. Using these languages, 
the developers can have more control over memory management and cpu utilization. These languages need build time and 
whenever there is change, program needs to be re-build. C, C++, Go, Rust. Due to compilation at build time, their execution 
speed is faster than interpreted languages. Error detection happens at build/compile time. Compiled binaries are distributed
for programs. Less flexibility at runtime.
- **Interpretted** - These languages use interpreter which converts to machine code and executes the program line by line.
They donot have build time but higher execution speed. Error detection happens at runtime. These languages offer more flexibilty 
at runtime.

