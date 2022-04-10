# Swaping-numbers

#include<stdio.h>
int main()
{
	int a=10, b=20;
	printf("Before swap a=%d b=%d \n",a,b);
	a=a+b;	// a=10+20=30 
	b=a-b;	// b=30-20=10
	a=a-b;	// a=30-10=20
	printf("After swap a=%d b=%d",a,b);
	return 0;
}
