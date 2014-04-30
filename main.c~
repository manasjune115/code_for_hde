#include<stdio.h>
#include<stdlib.h>
#include<math.h>
void enter(int );
void elements(int a[], int);
void sum_of_square(int a[], int ,double* total);
int count=0;
int main()
{
	int n;
	printf("Enter the number of test cases\n ");
	scanf("%d",&n);
	enter(n);
return(0);
}

void enter(int n)
{
	if(n<=0)
	return;
	
	count++;
	int a[100],size;
	 
	double total=0;
	double *ptr;
	ptr=&total;

	printf("************************************************\n");		
	printf("Test case %d \n",count);
	printf("Enter the number of element\n");
	scanf("%d",&size);
	printf("Enter the elements\n");
	elements(a,size);
	sum_of_square(a,size,ptr);	
	printf("The sum of the square of the numbers is %lf \n",*ptr);
	
	enter(n-1);
	printf("**************************************************\n");	

	return;
}

void elements(int a[], int size)
{
	if(size<=0)
	return;
	scanf("%d",&a[size-1]);
	elements(a,size-1);
	return;	
}
void sum_of_square(int a[],int size,double* total)
{
		//length=sizeof(a)/sizeof(a[0]);

	if(size<=0)
	return ;
	if(a[size-1]<0)
	{
			
	}
	else
	{
		*total+=a[size-1]*a[size-1];
	}
	sum_of_square(a,size-1,total);
	return ;


}

