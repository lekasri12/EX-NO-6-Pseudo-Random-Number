# EX-NO-6-Pseudo-Random-Number
# DATE:
# AIM: 
   To develop a C program to implement Pseudorandom Number Generation using  Standard Libraries

# Algorithm: 
1. Including all necessary Header files. 
2. Input the number of random numbers and range. 
3. Seed the random number generator. 
4. Initialize a loop. 
5. Generate the Random Numbers. 
6. Print the random numbers.

# PROGRAM:
DEVELOPED BY : G Lekasri

REGISTE NUMBER : 212223100025
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
 
int main()  
{ 
    int count, min, max; 
    printf("Enter the number of random numbers to generate: "); 
    scanf("%d", &count); 
    printf("Enter the minimum value: "); 
     
    scanf("%d", &min); 
    printf("Enter the maximum value: "); 
    scanf("%d", &max); 
    srand(time(NULL)); 
    printf("Pseudorandom numbers:\n");    
    for (int i = 0; i < count; i++)  
    { 
        int random_number = (rand() % (max - min + 1)) + min; 
        printf("%d\n", random_number); 
    } 
    return 0; 
}



```
# OUTPUT:
![Screenshot 2024-10-28 082830](https://github.com/user-attachments/assets/28ef1c79-238e-4d60-9474-d52ed46fb2bd)


# RESULT:
   Thus the implementation of Pseudorandom Number using C program is executed and verified successfully. 



