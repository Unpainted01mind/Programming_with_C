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
|Feature | Keyword | Identifier|
|--------|---------|-----------|
|Definition|Its a reserved word with a special meaning|its used to identify variables,functions,etc|
|Usage|predefined and used to define and structure the control flow of program| used to store values/string.|
|Example|int,return,printf,float etc|totalSum,MAX_SIZE,Var_Struct|
|Modification|they are predefined and hence can't be modified|they can be modified given they follow naming rules|
|Case Sensitivity|Both are case sensitive|Both are case sensitive|
