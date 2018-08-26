# pattern-x-to-y-rotate
#include<stdio.h>
int main()
{
	int a,b,i,j,k;
	printf("enter a value\n");
	scanf("%d",&a);
	printf("enter b value\n");
	scanf("%d",&b);
	   for(i=a;i<=b;i++)
	   {
	      printf("\t%d",i);
	      for(j=i+1;j<=b;j++)
	      {
	      	printf("\t%d",j);
	      }
	      for(k=a;k<i;k++)
	      {
	      	printf("\t%d",k);
		  }
		  printf("\n");
	}
}
