# test_8_12
#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>

int main()
{
	int f =5.20;
	scanf("请输入:>",&f);
	printf("%f\n",f);
	return 0;
}


//using namespace std;
//
//int main()
//{
//	int a=0;
//	int b,c,d;
//	printf("%p\n",&a);
//	cin>>b>>c;
//	d=b+c;
//	cout<<"b+c="<<d<<endl;
//	return 0;
//}


//字符串：由双引号引起的一串字符
//int main()
//{
//	char arr1[]="abc";//字符串的末尾，默认含有'\0'-是字符串的结束标志
//	char arr2[]={'a','b','c',0};//-可以是0，也可以是'\0'
//	printf("%s\n",arr1);
//	printf("%s\n",arr2);
//	return 0;
//}

//常量：
//字面常量；
//const修饰的常变量；
//#define定义的标识符常量，例如：#define MAX 10，意思是MAX是常量10

//枚举常量：enum （枚举函数），例如：
//enum Sex
//{
//	MALE,
//	FEMALE,
//	SECRET
//};
//
//int main()
//{
//	printf("%d\n",MALE);//0
//	printf("%d\n",FEMALE);//1
//	printf("%d\n",SECRET);//2
//	return 0;
//}

//int main()
//{
//	int a=0;
//	int b=0;
//	const int c=0;
//	scanf("请输入两个参数:> %d %d", &a,&b);
//	printf("c=%d",c);
//	return 0;
//}

///int main()
//{
//	char arr[10]={0};
//	scanf("%s",&arr);
//	printf("%s\n",arr);
//	return 0;
//}
