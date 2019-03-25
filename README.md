// c-program-to-enter-the-elements-in-an-array
#include<stdio.h>
void main()
{
	int l,i;
	printf("enter the size of array");
	scanf("%d",&l);
	int a[l];
	printf("enter the elements into array");
	for(i=0;i<l;i++)
		scanf("%d",&a[i]);
	printf("elements in the  array");
	for(i=0;i<l;i++)
		printf("%d ",a[i]);
}
  
