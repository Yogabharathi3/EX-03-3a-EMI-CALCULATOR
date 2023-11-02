# EX-03-3a-EMI-CALCULATOR
## AIM 
To write a program to prepare EMI calculator using function without return type 
and with arguments. 
## ALGORITHM 
1. Start the program. 
2. Read principal amount, rate of interest and months. 
3. Pass these values as arguments to function. 
4. Calculate EMI using the formula, amt=(p*r*pow(1+r,t))/(pow(1+r,t)-1) 
5. Display the result. 
6. Stop the program. 
## PROGRAM
```
#include <stdio.h> 
#include<math.h> 
void emicalculator(float p,float r,float t) 
{ 
 float amt; 
 r=r/(12*100); 
 t=t*12; 
 amt=(p*r*pow(1+r,t))/(pow(1+r,t)-1); 
 printf("Monthly EMI is= %.3f",amt); 
} 
int main() 
{ 
 float p,r,t; 
 scanf("%f%f%f",&p,&r,&t); 
 emicalculator(p,r,t); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-03-3a-EMI-CALCULATOR/assets/118899387/5d33687b-7db4-4068-933b-0f3125e479c1)
## RESULT 
Thus the program to prepare EMI calculator using function without return type 
with arguments has been executed successfully

