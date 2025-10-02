## C Compilation Process :-

#### Compilation begins from source file which is then preprocessed , compiled , assembled and then finally executed.

```mermaid
graph TD
    A[SourceCode]-->B[Preprocessor]
    B--Preprocessed file(.i file)-->C[Compiler]
    C--Assembly code(.s file)-->D[Assembler]
    D--Object file(.o file)-->E[Linker]
    E-->F[FinalOutputCode]
```

## What happens during compilation?
### The source code is compiled to an executable which undergoes the following stages :-
1) **Pre-processing.**
1) **Compiling.**
1) **Assembling.**
1) **Linking.**

### 1) **Pre-processing** :-
### It involves various processes like:-
* creation of filename.i(.i file)
* Expansion of macros
* Expansion of included file
* Removal of comments
* Conditional Compilation

#### In the end our code is still preserved.
* printf contains a/b instead of divide(a,b)
* &lt;stdio.h&gt; isn't seen as the header file itself is inside our compiled file instead of the preprocessor directive.

### 2) Compilation :-
Basically involves filename.i being compiled to an intermediate compiled output called filename.s which is an Assembly file.

### 3) Assembling :-
The Assembler converts the input fileame.i to an object file -> filename.o which contains machine level instructions. It contains existing code translated to machine code but doesn't resolve functions like printf().

### 4) Linking :-
 Its the final phase of our program, where function calls are linked to their definitions. The linker adds some extra code which is required when our program begins and ends. 

#### For example -> giving command line arguments via the terminal(console).

#### Linking is of two types :-
1) **Static Linking** :- The  machine code is copied to a single file and then executed.
2) **Dynamic Linking** :- Only the names of shared libraries are included in the code which are referred during execution.

#### GCC by default does Dynamic Linking hence printf() is dynamically linked.