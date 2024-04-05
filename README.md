# Cos-pro-2

#연산자
```c
#include <stdio.h>

int main(void)
{
	int num1=3, num2 = 4;
	int result1 = num1 + num2;
	int result2 = num1 - num2;
	int result3 = num1 * num2;
	int result4 = num1 / num2;
	int result4 = num1 % num2;

	//num1 = num2 = 0;

	printf("num1: %d,num2: %d \n", num1, num2);
	printf("%d + %d =%d \n", num1, num2, result1);
	printf("%d - %d =%d \n", num1, num2, result2);
	printf("%d * %d =%d \n", num1, num2, result3);
	printf("%d / %d =%d \n", num1, num2, result4);
  printf("%d % %d =%d \n", num1, num2, result5);
	return 0;
}
```

#복합연산자
```c
#include <stdio.h>

int main(void)
{
	int num1=4, num2=4, num3=6;
	num1 += 3;
	num2 *= 4;
	num3 %= 5;
	printf("Result: %d, %d, %d \n", num1, num2, num3);
	return 0;
}
```
