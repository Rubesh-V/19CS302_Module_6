# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
## DATE:25/03/2026
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1. Start.
2. Declare enum type
3. Declare all days in a week
4. Print result
5. End  

## Program:
```
#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}
```

## Output:
![image](https://github.com/user-attachments/assets/d56140ea-4644-4fa1-a01f-bfc05bd204f5)

## Result:
Thus the program was executed and the output was verified successfully.
