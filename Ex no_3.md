# EX 3 C program to find principle amount based on simple interest, time & rate of interest.
## DATE:
## AIM:
To write a C program to  find principle amount based on simple interest, time & rate of interest.

## Algorithm

1. Start the program.
2. Declare floating-point variables `si`, `year`, `rate`, and `principle`.
3. Read the values of `si`, `year`, and `rate` using `scanf()`.
4. Calculate the principal amount using the formula `principle = (si * 100) / (year * rate)`.
5. Display the principal amount using `printf()` and stop the program.
   

## Program:
```
#include <stdio.h>
int main()
{
    float si, year, rate,principle;
     
      scanf("%f", &si);
      scanf("%f", &year);
      scanf("%f",&rate);
principle =(si *100)/(year*rate);
   printf("Principle amount is = %.2f", principle);
    return 0;
}


```

## Output:
<img width="816" height="178" alt="Screenshot 2026-03-18 213330" src="https://github.com/user-attachments/assets/ee06fd62-b34d-4fbb-8209-8ddae2457847" />



## Result:
Thus the program was executed and the output was verified successfully.
