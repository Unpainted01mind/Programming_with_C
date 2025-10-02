### Identifiers :-
An identifier is a unique name given to a program element such as array,variable,function etc which is used to refer them later in the program.

```c
#include <stdio.h>
int main(){
    int var=10;
    int arr[]={1,2,3};
    printf("Value of the variable is: ",var);
    return 0;
}
```
In the above program var is an identifier for an integer type variable to store the value 10 , which is being referred in the print function.

### Rules for naming identifiers :-
* Identifiers can be uppercase(A-Z)/lowercase(a-z) , numeric , or can have underscores (_)
* The first character of an identifier must be either an underscore or a letter
* Identifiers are case sensitive.
* Keywords such as printf,scanf,int,float etc can't be used as Identifiers.

  ### Some naming conventions : -
  1) For variable names
     * use camelCase
     * ex :- studentName,stringLength
     * for constants use MAX_SIZE,PI,MIN
  2) for functions use camelCase.
  3) for structs use PascalCase , ex - VariableTypes.

### Some key differences between Identifiers and Keywords : -
<!DOCTYPE html>

<html>
<head>
    <title>This is a new webpage.</title>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>
<p>
    This is a new paragraph--
</p>

<table>
    <tr>
        <td >1.</td>
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
<br>

</html>
