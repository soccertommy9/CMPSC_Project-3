# CMPSC_Project-3


//Fibonacci Series using Recursion 
#include<iostream>
#include<stdio.h>
#include<cstdlib>
#include<math.h>


using namespace std;

int fib(int n) 
{ 
if (n <= 1) 
	return n; 
return fib(n-1) + fib(n-2); 
} 

int rand();
int main () 
{ 

   double G;
    G=(rand()%18)+5;

int n=G; 
printf("%d", fib(n)); 
getchar(); 
return 0; 
} 
