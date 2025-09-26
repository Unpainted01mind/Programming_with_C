# C-Programming
This is a summarised version of C concepts which will come in handy for quick reference or revision. 

### C Overview:- 
* Developed in 1972 by Dennis M.Ritchie at Bell Labs of AT&T labs.
* Originally made to develop UNIX OS.
* Mid Level Programming Language.

### Writing First Program in C :-

```c
#include <stdio.h>
int main(){
    printf("Hello World Bye");
    return 0;
}
```
### Structure of a C Program :-

<table>
    <tr>
        <td colspan="2" rowspan="2" > </td>
        <td>1.</td>
        <td>#include &lt;stdio.h&gt;.</td>
        <td>header file.</td>
    </tr>
    <tr>
    <td>2.</td>
    <td>int main()</td>
    <td>main function.</td>
    </tr>
    <tr>
    <td colspan="2" rowspan="5">BODY</td>
    <td>3.</td>
    <td>&#123;</td>
    <td>Start of main function body</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>//Printing hello world</td>
        <td>Comment (doesnt affect code)</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>printf("Hello World")</td>
        <td>displaying Hello World </td>
    </tr>
    <tr>
        <td>6.</td>
        <td>return 0;</td>
        <td>returns 0 for successfull program completion</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>&#125;</td>
        <td>End of function body</td>
    </tr>
</table>

### Explaination of each line:-
#### 1. Header File :-
* is a .h file,containing function declarations and macro definitions. 
* lines starting with # is processed by preprocessor which is invoked by a compiler.
#### Some Standard header files in C:-
* stdio.h -> defines basic i/o functions like printf,scanf.
* stdlib.h -> used for numeric conversion,random num generator and memory allocation.
* string.h,math.h -> define string and math functions.

#### 2. Main Method :-
* Basically the entry point of the program.
* Program execution begins with first line of main()
* int-> return type of main
* int main(){}->main doesnt need any parameters.

#### 3. Body of the Main Function :-
* 
