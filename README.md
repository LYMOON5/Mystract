#include<stdio.h>
#include<assert.h>

//字符串连接
char *Mystrcat(char *des,const char *scr)
{
	char * p = des;
	assert(des!= NULL && scr!=NULL);
	while(*des!='\0')
	{
		des++;
	}
	while(*des++ = *scr++)
	{
		
	}
	return p;
}

int main()
{
  printf("%s\n",Mystrcat("abc","xyz"));//字符串连接测试用例
  printf("%s\n",Mystrcat("hello","world"));//字符串连接测试用例
  printf("%s\n",Mystrcat("123","xyz"));//字符串连接测试用例
  
  return 0;
}
