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
    // a single line comment.
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
* Contains our program code which can be
* sorting, searching , file handling etc.
#### 4. Comments :-
* Comments are used to describe our code and are ignored by the compiler.
* // denotes a single line comment.
* /* */ denotes a multi line comment which goes up to multiple code blocks.
#### 5. Print Statement :-
* Statements are instructions given to the compiler and end with semicolon (;)
* Here print statement tells the compiler to display the line "Hello World".
#### 6. Return Statement :-
* Used to return a value of the return type of the function
* here 0 (int) is returned since main function has return type as int
* 0 means successfull program completion.

### History of C :-
#### C evolved through the following versions :-
* ANSI C was internationally adopted in 1990
* C99 was created in 1999.
* C11 in 2011.
* 2024 published ISO/IEC 9899:2024 , based on C23 is the most recent version of C.
