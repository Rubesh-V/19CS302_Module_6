# EX 27 C program that demonstrates the use of typedef to create a new alias name for a data type.
## DATE:25/03/2026
## AIM:
To write a C program that demonstrates the use of typedef to create a new alias name for a data type.

## Algorithm
1.Start 
2.Declare a new alias uint for unsigned int using typedef.
3.Define a structure with two members: name (character array) and age (integer).
4.Create a new alias Person for the structure using typedef.
5.Declare a variable a of type uint and assign it a value.
6.Display the value of a.
7.Declare a variable p1 of type Person.
8.Display the name and age stored in p1.
9.End
## Program:
```
#include <stdio.h>
typedef int MyInt;
int main() {
 MyInt num = 10;
 printf("The value of num is: %d\n", num);
 return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/97eb97e2-3739-4c0f-9f7f-f0ff63ff62b0)


## Result:
Thus the program was executed and the output was verified successfully.
