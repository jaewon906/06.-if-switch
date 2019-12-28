#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>


int main(void)
{
	int a;
	printf("몇명이 왔나요??\n");
	scanf("%d", &a);

	if (a == 1 || a == 2)
	{
		printf("2인석으로 안내해드립니다.\n");

	}
	else if (a == 3 || a == 4)
	{
		printf("4인석으로 안내해드립니다.\n");
	}
	else 
	{
		printf("대형석으로 안내해드립니다.\n");
	}
	system("pause");
}
