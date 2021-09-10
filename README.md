# study-time

int main ()
{
	int num1=0;
	int num2=0;
	int sum=0;
	
	scanf("%d%d",&num1,&num2);
	sum=num1+num2; 
	printf("sum=%d",sum);
	
	
	return 0;
}  





int main()
{
	printf("   *\n");
	printf("  ***\n");
	printf(" *****\n");
	printf("*******\n");
	return 0;
 } 
    
    
    
int main()
{
	int arr[10] = { 1,2,3,4,5,6,7,8,9,10 };
	//arr[10]是定义一个存放10个整数的数组，其中每个整数都有一个下标，从0开始，1的下标是0,5的下标是4
	printf("%d\n", arr[4]);//这里的arr[4]指的是数组中下标为4的数
	return 0;
}

int Add(int x, int y)
{
	int z = x + y;
	return z;
}            */   //这是自定义的加法函数
{
	int input = 0;
	printf("你要好好学习吗？（0/1):");
	scanf_s("%d",& input);
	if (input == 1)
		printf("光明的未来\n");
	else
		printf("只能搬砖\n");
	return 0;
}


#include <stdio.h>
int global = 2019;//全局变量
int main()
{
	int local = 2018;//局部变量
	//下面定义的global会不会有问题？
	int global = 2020;//局部变量
	printf("global = %d\n", global);
	return 0;
}


#include<stdio.h>
int main()
{
	float f=96.5;
	printf("%f\n", f/3);
	return 0;
}


int Add(int x, int y)
{
	int z = x + y;
	return z;
}               //这是自定义的加法函数
#include<stdio.h>
int main()
{
	int a = 100;
	int b = 298;
	int sum = 0;
	sum = Add(a, b);
	printf("sum=%d\n", sum);
    return 0;
}


#include<stdio.h>
int main()
{
	int line = 0;
	while (line < 5000)
	{
		printf("敲一行代码：%d\n", line);
			line++;
	}
	if (line >= 5000)
		printf("good offer");
	return 0;
}

