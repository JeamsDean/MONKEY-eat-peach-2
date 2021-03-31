# MONKEY-eat-peach-2
MONKEY eat peach 2
#include<stdio.h>/*包含头文件*/
int main( )/*定义主函数*/
{
	int x, n;/*定义整形变量*/
	x = 1;/*最后一天只剩了一个桃子*/
	for (n = 9; n >= 0; n--)
	{
		x = (x +1)*(x+1);
	}
	printf("第一天摘了%d个桃子", x);
}
/*从最后一天往前推，每天吃完根号y个桃子后又多吃一个*/
