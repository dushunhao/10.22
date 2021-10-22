#define _CRT_SECURE_NO_WARNINGS 1

#include <stdio.h>

int main()

{

	int i = 0;
  
	for (i = 0; i <= 100; i++)
  
	{
  
		if (i % 2 == 0)
    
			printf("%d ", i);
      
	}
  
	return 0;
  
}


int main()

{

	int i = 1;
  
	while (i <= 10)
  
	{
  
		if (i == 5)
    
		{
    
			printf("%d ", i);
      
			i++;
      
		}
    
	}
  
	return 0;
  
}



int main()

{

	int ch = 0;
  
	while ((ch = getchar()) != EOF)
  
	{
  
		putchar(ch);
    
	}
  
	return 0;
  
}


int main()

{

	int ch = 0;
  
	while ((ch = getchar()) != EOF)
  
	{
  
		if (ch<'0' || ch>'9')
    
			continue;
      
		putchar(ch);
    
	}
  
	return 0;
  
}


int main()

{

	char password[20] = { 0 };
  
	printf("请输入密码：>");
  
	scanf("%s", password);
  
	printf("请确认密码(Y/N):>");
  
	int tmp = 0;
  
	while ((tmp = getchar()) != EOF)
  
	{
  
		;
    
	}
  


	int ch = getchar();
  
	if (ch == 'Y')
  
	{
  
		printf("确认成功\n");
    
	}
  
	else
  
	{
  
		printf("密码错误\n");
    
	}
  
	return 0;
  
}

