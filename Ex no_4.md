# EX 4 C Program for analysis of people of certain age groups who are eligible for getting a suitable college admission if their condition and norms get satisfied using nested if statement. Assume eligible age is 18 - 25. Total marks >=180.

## DATE:
## AIM:
To write a C Program for analysis of people of certain age groups who are eligible for getting a suitable college admission if their condition and norms get satisfied using nested if statement. Assume eligible age is 18 - 25. Total marks >=180.
## Algorithm


1. Start the program.
2. Declare integer variables `a` (age) and `tot` (total marks) and read their values using `scanf()`.
3. Check if `a < 18`; if true, display **"Not eligible for college admission"**.
4. Otherwise, check if `a >= 18` and `a <= 25` and `tot >= 180`; if true, display **"Eligible for college admission"**, else display **age above limit or marks less than 180**.
5. Stop the program.

## Program:
```

#include <stdio.h>
int main()
{
int a, tot;
scanf("%d%d",&a, &tot);
if ( a < 18 )
{
printf("Not eligible for college admission");
}
else
{
if (a >= 18 && a <= 25 && tot>=180 )
{
printf("He/She is eligible for college admission\n");
}
else
{
printf("His/Her age is above the upper age limit for college admission or his/her total marks is less than 180.\n");
}
}
return 0;
} 

```

## Output:

<img width="1404" height="176" alt="Screenshot 2026-03-18 214218" src="https://github.com/user-attachments/assets/f39b370e-62a0-4888-afae-c505d1e94365" />



## Result:
Thus the program was executed and the output was verified successfully.
