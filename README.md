# Program-3-e
## C-Module 3
## EX_NO-03)e)-ARRAY
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C Program to Print the sum, count of even & odd Numbers in an Array
## ALGORITHM:
1. Start the program.
2. Declare integer variables: num, sum, odd, and even. Initialize sum, odd, and even to 0.
3. Read an integer value num from the user using scanf.
4. Declare an integer array of size num.
5. Use a for loop from 0 to num-1 to read num elements into the array using scanf.
6. Use a for loop from 0 to num-1 to calculate the sum of all array elements and store it in sum.
7. Use another for loop from 0 to num-1 to count:

    a. Even numbers and increment the even counter.

    b. Odd numbers and increment the odd counter.

9. Print the total sum, the count of even numbers, and the count of odd numbers.
10. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int num,sum=0,odd=0,even=0;
    scanf("%d",&num);
    int a[num];
    for(int i=0;i<num;i++)
    {
        scanf("%d",&a[i]);
    }
    for(int j=0;j<num;j++)
    {
        sum+=a[j];
    }
    for(int i=0;i<num;i++)
    {
        if(a[i]%2==0)
        even+=1;
        else
        odd+=1;
    }
    printf("Total Sum: %d\n",sum);
    printf("Even numbers: %d\n",even);
    printf("Odd numbers: %d\n",odd);

    
}
```
## OUTPUT:
<img width="839" height="303" alt="Screenshot 2025-10-19 223306" src="https://github.com/user-attachments/assets/d06ba6eb-3cdc-4f64-b337-56e95da00cf4" />

## RESULT:
Thus the program to Print the sum, count of even & odd Numbers in an Array has been executed successfully
