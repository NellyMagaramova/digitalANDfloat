# digitalANDfloat
#include "stdafx.h"
#include "stdio.h"
#include <cstdlib>

int _tmain(int argc, _TCHAR* argv[])
{
	//int x=11, y=4;
	//float z=4;
	int x, y;
	float z;
	printf("enter a first digit (x) \n");
	scanf("%d",&x);

	printf("enter a second digit (y) \n");
	scanf("%d",&y);

	printf("enter a third digit  (z) \n");
	scanf("%f",&z);

printf("\n \n rezult in the integer value x/y   %d  \t",x/y);
printf("\n rezult in the float  value x/z  %f \t", x/z);
printf("\n remainder of division %d \n",x%y);


system("PAUSE");
	return 0;
}
