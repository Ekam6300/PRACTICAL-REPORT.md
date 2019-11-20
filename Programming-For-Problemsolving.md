#     **PROGRAMMING FOR PROBLEM SOLVING**
## NAME - *EKAMJOT SINGH*
## ROLL NO. - *1915020*
## BRANCH - *COMPUTER SCINECE AND ENGINEERING* 
## SECTION - *CSE(A1)* 
# DEPARTMENT OF COMPUTER SCIENCE ENGINEERING
## *GURU NANAK DEV ENGINEERING COLLEGE,LUDHIANA*
![LOGO](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXOYGxoUmjkfjKYi4PqjUEc-BsknLsvVJesGpv54Tag2mFC6Pc_Q6ups3q&s=10)
## *PROGRAM No. 1:-PROGRAM TO PRINT WELCOME MESSAGE*
```C
#include <stdio.h>
int main() 
{ 
puts("Welcome To Budding engineers");
}
```

##	OUTPUT
Welcome To Budding engineers
## *PROGRAM No. 2:-PROGRAM TO PRINT THE ADDRESS*

```C
#include <stdio.h> 
int main()
{ 
puts("Principal\nPanth Rattan Shiri Gurcharan Singh Tohra Complex\nGuru Nanak Dev Engineering College\nGill Park\nLudhiana - 141006\nIndia");
}
```
## OUTPUT
```C
Principal
Panth Rattan Shiri Gurcharan Singh Tohra Complex
Guru Nanak Dev Engineering College
Gill Park\nLudhiana-141006
India
```

## *PROGRAM No. 3:-TO FIND THE SUM OF TWO NUMBERS*
```C
#include <stdio.h>
int main()
{
int a,b,c;
printf("enter the numbers");
scanf("%d %d",&a,&b);
c=a+b;
printf("sum of numbers is %d\n",c);
return 0;
}
```

## OUTPUT
```C
enter the numbers 50
25
sum of numbers is 75
```

## *PROGRAM No. 4:-TO CONVERT CELCIUS TO FARENHEIT* 
```C 
#include<stdio.h>
int main()
{
float f,c;
printf("Enter the temperature in Fahrenheit= ");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("Temperature in Celsius= %.2f\n",c);
return 0;
}
```

## OUTPUT

```C
Enter the temperature in Fahrenheit= 45
Temperature in Celsius= 7.22
```

## *PROGRAM No.5 :- TO FIND AREA AND PERIMETER OF CIRCLE*
```C
#include <stdio.h>
void main()
{
float diameter, perimeter, area;
printf("enter Diameter");
scanf("%f", &diameter);
perimeter = 22/7 * diameter;
area = perimeter * diameter / 4.0;
printf("\n\nDia: %.2f\nPerimeter:
%.2f\nArea: %.2f\n\n",diameter, perimeter, area);
}
```

## OUTPUT
```C
 enter Diameter:56
 diameter: 56.00
 perimeter: 168.00
 area: 2352.00
 ```
 ## *PROGRAM NO. 6:- SWAPPING OF TWO NUMBERS*
```C
#include<stdio.h>
int main()
{
int a,b,n;
printf("Enter the two numbers : ");
scanf("%d %d",&a,&b);
printf("no. before swapping are %d,%d\n",a,b);
a=a+b;
b=a-b;
a=a-b;
printf(" no. after swapping are %d,%d\n",a,b);
return 0;
}
```
## OUTPUT
```C
Enter the two numbers :
56
43
no. before swapping are 56,43
no. after swapping area 43,56
```
## *PROGRAM NO.7 :- TO CHECK WHETHER THE NO. IS ODD OR EVEN*
```C
#include <stdio.h>
int main()
{
int a;
printf("Enter number: ");
scanf("%d",&a);
if (a%2==0)
printf("%d is Even",a);
else
printf("%d is Odd",a);
return 0 ;
}
```
## OUTPUT
```
Enter number: 67
67 is Odd
```
## *PROGRAM NO.8:- TO FIND FACTORIAL*
```C
#include<stdio.h>

int main()
{
int i,n,ans=1;
printf("Enter the no: ");
scanf("%d",&n);
for(i=1;i<=n;i++)
ans=ans*i;
printf(" factorial of %d is : %d\n",n,ans);
return 0;
}

```
## OUTPUT
```
Enter the no: 5 
 factorial of 5 is : 120
```
 ## *PROGRAM No.9 :-PROGRAM FOR REVERSING A NUMBER*

```C
#include<stdio.h>

int main()
{
int n,r,ans=0;
printf("Enter the no: ");
scanf("%d",&n);
while(n>0)
{
r=n%10;
ans=ans*10+r;
n=n/10;
}
printf("Reversed no is : %d\n",ans);
return 0;
}
```
## OUTPUT
```
Enter the no: 567
Reversed no is : 765
```
## *PROGRAM No.10 :-FIZZ BUZZ GAME*
```C
#include<stdio.h>
int main()
{
int i,n; 
printf(" Enter the limit: ");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(i%3==0&&i%5!=0)
printf("fizz\t");
if(i%5==0&&i%3!=0)
printf("buzz\t");
if(i%15==0)
printf("fizzbuzz\t");
if(i%3==0||i%5==0)
   printf(" ");
   else 
  printf("%d\t",i);
}
return 0;
}
```
## OUTPUT
```
 Enter the limit: 15
1       2       fizz     4      buzz     fizz    7      8       fizz     buzz    11     fizz     13     14      fizzbuzz
```

## *PROGRAM No.11 :-SIMPLE ARTHEMETIC CALCULATOR*
```C
#include <stdio.h>

int main()
{
    float principle, time, rate, simple_intrest ;

   
    printf("Enter principle (amount): ");
    scanf("%f", &principle);

    printf("Enter time: ");
    scanf("%f", &time);

    printf("Enter rate: ");
    scanf("%f", &rate);

     
    simple_intrest = (principle * time * rate) / 100;

   
    printf("Simple Interest = %f", simple_intrest);

    return 0;
}
```
## OUTPUT
```
Enter an operator (+, -, *, /): *
Enter two operands: 43
34
43.0 * 34.0 = 1462.0
```
## *PROGRAM No.13 :-PALLANDROME NUMBER*
```C
#include <stdio.h>
    int main()
    {
        int n, reversedInteger = 0, remainder, originalInteger;
        printf("Enter an integer: ");
        scanf("%d", &n);
        originalInteger = n;
        
        while( n!=0 )
        {
            remainder = n%10;
            reversedInteger = reversedInteger*10 + remainder;
            n /= 10;
        }
       
        if (originalInteger == reversedInteger)
            printf("%d is a palindrome.", originalInteger);
        else
            printf("%d is not a palindrome.", originalInteger);
        
        return 0;
        }
```
## OUTPUT
```

```
## *PROGRAM No.13 :- TO DISPLAY FIBONACCI SERIES*
```C
#include<stdio.h>
int main()
{
int a =1,b=1,s,i;
printf("enter i");
scanf("%d",&i);
for(a=1;a<=i;)
{
s=a+b;
printf("%d",s);
b=a;
a=s;
}
return 0;
}
```
## OUTPUT
```
Enter an integer: 56
56 is not a palindrome.
```
## *PROGRAM No.14 :-TO DISPLAY 1D ARRAY*

```C
#include<stdio.h>

int main()
{
  int array[5],i; 
printf("Enter the five elments of array :\n ");
for(i=0;i<5;i++)
{
  scanf("%d",&array[i]);
}
printf("Elements of array are:\n ");

for(i=0;i<5;i++)
{
   printf("%d\t",array[i]);
}
return 0;
}
```
## OUTPUT
```
Enter the five elments of array :
 45
65
43
65
87
Elements of array are:
 45     65      43      65      87 
```
## *PROGRAM No.15 :- TO DISPLAY 2D ARRAY*
```C
 #include<stdio.h>

int main()
{
  int arr[3][5],i,j;
printf("Enter the elements of array : \n");

for(i=0;i<3;i++)
{
   for(j=0;j<5;j++)
   scanf("%d",&arr[i][j]);
}

printf("2D array entered by you is : \n");

for(i=0;i<3;i++)
{
   for (j=0;j<5;j++)
    printf("%d\t",arr[i][j]);
printf("\n");
}

return 0;
}
```
## OUTPUT
```
Enter the elements of array : 
45
64
253
65
897
5
65
6
8
3
5

55
5
5
5
2D array entered by you is : 
45      64      253     65      897
5       65      6       8       3
5       55      5       5       5
```
## *PROGRAM No.16 :-ADDITION OF TWO MATRICES*
```C
#include<stdio.h>
int main()
{
int a[3][3], b[3][3],c[3][3];
printf("Enter the value of matrix A\n");
for(int i=1;i<=3;i++);
{ 
for(int j=1;j<=3;j++)
scanf("%d\n",&a[3][3]);
}
printf("Enter the value of matrix b\n");
for(int t=1;t<=3;t++);
{
for(int y=1;y<=3;y++)
scanf("%d\n",&b[3][3]);
}
c[3][3]=a[3][3]+b[3][3];
printf("|            |\n");

for(int i=0;i<=2;i++)
{
for(int j=0;j<=2;j++)
printf("|%d\t,c[3][3]|\n");
printf("|            |\n");
}
return 0;
}
```
## OUTPUT
```
Enter the value of matrix A
5        
5
4
4
Enter the value of matrix b
3
3
5
|            |
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|            |
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|            |
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|87097952       ,c[3][3]|
|            |
```
## *PROGRAM No.17 :-MATRIX TRANSPOSE*

```C
#include<stdio.h>

int main()

{ int a[3][3],c[3][3],i,j;

printf("Enter the elements of matrix A : \n");

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d\n",&a[i][j]);
}

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[j][i]=a[i][j];
}

printf(" transpose of matrix A :\n");


for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d\t",c[i][j]);
printf("\n");
}
return 0;
}
```
## OUTPUT
```
Enter the elements of matrix A : 
32
43
23
43
54
23
34
45
34
2
 transpose of matrix A :
32      43      34
43      54      45
23      23      34
```
## *PROGRAM No.18 :- TO FIND MATRIX MULTIPLICATION*
```C
#include<stdio.h>

int main()
{
int a[3][3],b[3][3],c[3][3],i,j;

printf("Enter the values of matrix a : \n");

for(i=0;i<3;i++)
{
   for(j=0;j<3;j++)
   scanf("%d",&a[i][j]);
}
printf("Enter the values of matrix b:\n ");
for(i=0;i<3;i++)
{
    for(j=0;j<3;j++)
        scanf("%d",&b[i][j]);
}
for(i=0;i<3;i++)
{
     for(j=0;j<3;j++)
     c[i][j]=a[i][0]*b[0][j]+a[i][1]*b[1][j]+a[i][2]*b[2][j];
}
printf("matrix a * b = \n");
for(i=0;i<3;i++)
{
    for(j=0;j<3;j++)
     printf("%d\t",c[i][j]);
    printf("\n");
}
return 0;
}


```
## OUTPUT
```
Enter the values of matrix a : 
65
54
34
6
4
3
6
3
4
Enter the values of matrix b:
 5
3
9
23
65
876
4
4
23
matrix a * b = 
1703    3841    48671
134     290     3627
115     229     2774
```
## *PROGRAM No.19 :- TO FIND SQUARE USING FUNCTION*
```C
#include<stdio.h>
int square(int a);
int main()
{
int a,ans;
printf("Enter the number : ");
scanf("%d",&a);
ans=square(a);
printf("Value of square is : %d\n",ans );
return 0;
}

int square(int a)
{
a=a*a;
return a;
}
```
## OUTPUT
```
Enter the number : 546
Value of square is : 298116
```
## *PROGRAM No.20 :- SWAPPING BY CALL BY VALUE USING FUNCTION*
```C
#include<stdio.h>
    void swap(int a, int b)
    {
       int temp;
 
       temp = b;
       b = a;
       a = temp;
        printf("Values of a and b is %d  %d\n",a,b);
    }
     int main()
{
   int x, y;

   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
   swap(x, y); 

   printf("After Swapping\nx = %d\ny = %d\n", x, y);

   return 0;
   }
```
## OUTPUT
```
Enter the value of x and y
43
34
Before Swapping
x = 43
y = 34
Values of a and b is 34  43
After Swapping
x = 43
y = 34
```
## *PROGRAM No.21 :- SWAPPING BY CALL BY REFERNCE USING FUNCTION*
```C
#include<stdio.h>
void swaping_no ( int *var1, int *var2 )
{
   int temp_no ;
   temp_no = *var1 ;
   *var1 = *var2 ;
   *var2 = temp_no ;
}
int main()
{
 int num1,num2;
 printf("enter the numbers");
 scanf("%d %d",&num1,&num2);
   printf("Before swapping:");
   printf("\nnum1 value is %d", num1);
   printf("\nnum2 value is %d", num2);

 
   swaping_no( &num1, &num2 );

   printf("\nAfter swapping:");
   printf("\nnum1 value is %d", num1);
   printf("\nnum2 value is %d", num2);
   return 0;
}
```
## OUTPUT
```
enter the numbers6
5
Before swapping:
num1 value is 6
num2 value is 5
After swapping:
num1 value is 5
num2 value is 6
```
## *PROGRAM No.22 :- TO FING FACTORIAL USING RECURSION*
```C
#include<stdio.h>
int fact(int n);
int fact(int n)
{
int ans;
if(n==0)
ans=1;
else
ans=n*fact(n-1);
return ans;
}

int main()
{
int n,result;
printf("Enter the no whose factorial you want to get : ");
scanf("%d",&n);
result=fact(n);
printf("factorial of %d is: %d \n",n,result);
return 0;
}
```
## OUTPUT
```
Enter the no whose factorial you want to get : 9
factorial of 9 is: 362880
```
## *PROGRAM No.23 :- FIBONACCI USING RECURSION* 
```C
  #include<stdio.h>
     
    int Fibonacci(int n);
     
    int main()
    {
       int n, i = 0, c;
       printf ("Enter the number of elements : ");
       scanf("%d",&n);
     
       printf("Fibonacci series\n");
     
       for ( c = 1 ; c <= n ; c++ )
       {
          printf("%d\n", Fibonacci(i));
          i++; 
       }
     
       return 0;
    }
     
    int Fibonacci(int n)
    {
       if ( n == 0 )
          return 0;
       else if ( n == 1 )
          return 1;
       else
          return ( Fibonacci(n-1) + Fibonacci(n-2) );
    } 
```
## OUTPUT
```
Enter the number of elements : 8
Fibonacci series
0
1
1
2
3
5
8
13
```
## *PROGRAM No.24 :-PROGRAM TO DISPLAY STRCTURE*
```C
#include<stdio.h>

struct data
{
 char name[20];
 char branch[10];
  int roll_no;
};

int main()
{
struct data c;
printf("Enter your name,branch,roll no :\n");
scanf("%s %s %d",&c.name,&c.branch,&c.roll_no);
printf("YOUR DATA\n name : %s\nbranch : %s\nroll no : %d\n",c.name,c.branch,c.roll_no);
return 0;
}
```
## OUTPUT
```
Enter your name,branch,roll no :
anurag 
cse
1915011
YOUR DATA
 name : anurag
branch : cse
roll no : 1915011
```
## *PROGRAM No.25 :-TO ENTER DATA OF STUDENTS USING STRCTURE*
```C
#include<stdio.h>

struct record
{
int roll_no;
char name[20];
int marks;
long contact_no;
};

int main()
{
int i;
struct record r[5];
for(i=1;i<6;i++)
{
  printf("STUDENT %d \nEnter roll no,name,marks,contact no: ",i);
scanf("%d %s %d %ld",&r[i].roll_no,&r[i].name,&r[i].marks,&r[i].contact_no);
}
for(i=1;i<6;i++)
{
   printf("for student %d \n roll no :%d \n name: %s  \n marks: %d \n contact no: %ld \n\n ",i,r[i].roll_no,r[i].name,r[i].marks,r[i].conta$
}
return 0;
}
```
## OUTPUT
```
Enter roll no,name,marks,contact no: 1
anurag
45345
5455454565
Enter roll no,name,marks,contact no: 2
guri
343
6757567566
STUDENT 3 
Enter roll no,name,marks,contact no: 3
gurdeep
545
4564564456
STUDENT 4 
Enter roll no,name,marks,contact no: 4
gitu
754334
6878776767
STUDENT 5 
Enter roll no,name,marks,contact no: 5     
happy
3434
9787878776
for student 1 
 roll no :1 
 name:  anurag

 marks:45345
 contact no:  5455454565

 for student 2 
 roll no :2 
 name:  guri 
 marks:  343
 contact no: 6757567566

 for student 3 
 roll no :3 
 name: gurdeep  
 marks: 545
 contact no:  4564564456

 for student 4 
 roll no :4 
 name: gitu
 marks: 754334
 contact no: 6878776767

 for student 5 
 roll no :5 
 name:   happy
 marks:  3434
 contact no: 9787878776
```
