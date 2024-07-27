#include<stdio.h> 
#include<conio.h> 
#define SIZE 100 
void main() 
{ 
int n, key, a[SIZE], i, found =0; 
printf("Enter the size of array : "); 
scanf("%d", &n); 
//hu
printf("Enter the numbers in array \n"); 
for(i=0; i < n; i++) 
scanf ("%d", &a[i]); 
printf("Enter the elements to be searched : "); 
scanf("%d", &key); 
// lenear search logic 
for(i=0; i < n; i++)
{ 
if (a[i] == key) 
{ 
found=1; 
break; 
} 
} 
if (found == 1) 
printf("Key Element %d found at position= %d\n", key , i+1 ); 
else 
printf("Key Element NOT found\n"); 
getch(); 
}

