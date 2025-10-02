### C Compilation Process :-

##### Compilation begins from source file which is then preprocessed , compiled , assembled and then finally executed.

```mermaid
graph TD
    A[SourceCode]-->B[Preprocessor]
    B--Preprocessed file(.i file)-->C[Compiler]
    C--Assembly code(.s file)-->D[Assembler]
    D--Object file(.o file)-->E[Linker]
    E-->F[FinalOutputCode]
```

### What happens during compilation?
#### The source code is compiled to an executable which undergoes the following stages :-
1) Pre-processing.
1) Compiling.
1) Assembling.
1) Linking.
