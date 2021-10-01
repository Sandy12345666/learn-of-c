# learn-of-c
#include<stdio.h>
//宏定义
#define PI 3.14
#define SUN_FLOWER 100
int main(void)
{
	int number1= 50;
	int number2 = 20;
	int number3;
	double kk = 99.9;
	//定义常量 命名常量全大写
	const int IOAD_MONER = 9999;
	number3 = number1 + number2;
	printf("相加值%d\n", number3);
	number3 = number1 - number2;
	printf("相减值%d\n", number3);
	number3 = number1 * number2;
	printf("相乘值%d\n", number3);
	number3 = number1 / number2;
	printf("相除值%d\n", number3);
	number3 = number2 % number1;
	printf("取余值%d\n", number3);
	number3 = number1++;
	printf("先赋值后运算3值%d\n", number3);
	printf("先赋值后运算1值%d\n", number1);
	number3 = ++number1;
	printf("先运算后赋值3值%d\n", number3);
	printf("先运算后赋值1值%d\n", number1);
	unsigned int number4 = 60;	/*60 = 0011 1100*/
	unsigned int number5 = 13;	/*13 = 0000 1101*/
	int number6 = 0;
	//位运算符的与&
	number6 = number4 & number5;	/*12 = 0000 1100*/
	printf("与: %d\n", number6);
	//位运算符的或|
	number6 = number4 | number5;		/*61 = 0011 1101*/
	printf("或： %d\n", number6);
	//位运算符：异或^
	number6 = number4 ^ number5;
	printf("异或：%d\n", number6);
	//位运算符：取反~
	number6 = ~number4;
	printf("取反：%d\n", number6);
	//二进制左移运算符<<
	number6 = number1 << 2;
	printf("左移：%d\n", number6);
	//二进制右移移运算符>>
	number6 = number1 >> 2;
	printf("右移：%d\n", number6);


	return 0;
}
