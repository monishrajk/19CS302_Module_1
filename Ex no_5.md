# EX 5 C program to calculate total, average and percentage of 4 subjects for engineering admission.
## DATE:
## AIM:
To write a C program to calculate total, average and percentage of 4 subjects for engineering admission.

## Algorithm

1. Start the program.
2. Declare integer variables `a`, `b`, `c`, `d` and floating variables `tot`, `avg`, `percent`.
3. Read the four marks `a`, `b`, `c`, and `d` using `scanf()`.
4. Calculate the **total**, **average**, and **percentage** using the given formulas.
5. Display the total, average, and percentage using `printf()` and stop the program.
   

## Program:
```
#include <stdio.h>
int main()
{
    int a,b,c,d;
    float tot,avg,percent;
    scanf("%d%d%d%d",&a,&b,&c,&d);
    tot=a+b+c+d;
    avg=(a+b+c+d)/4.0;
    percent=(a+b+c+d)/4.0*(1.00);
    printf("Total marks = %.2f \n",tot);
    printf("Average marks = %.2f\n",avg);
    printf("Percentage = %.2f\n",percent);
    return 0;

}
    
```

## Output:

<img width="819" height="225" alt="Screenshot 2026-03-18 220039" src="https://github.com/user-attachments/assets/ce7b06cf-e500-4146-8eef-6deb98be7d73" />


## Result:
Thus the program was executed and the output was verified successfully.
