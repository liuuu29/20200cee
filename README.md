# 20200cee
## 第一題 進階題：分式化簡 
```c
#include <stdio.h>
int main()
{
	int m,n,i;
	scanf("%d%d",&m,&n);
	for(int i=m;i>=1;i--)
	{
		if((m%i==0)&&(n%i==0))
		{
			m=m/i;
			n=n/i;
		}
	}
	printf("%d %d\n",m,n);
	return 0;
}
```
## 第二題 進階題：讀入整數反序列印
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第三題 進階題：A的B次方函數 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第四題 進階題：漸增數列相加 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第五題 基礎題：找零錢 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第六題 基礎題：因數個數 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第七題 基礎題：找倍數 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
}
```
## 第八題 基礎題：整數轉換為等級 
```c
#include <stdio.h>
int a[10];
int main()
{
	int n;
	for(int i=1;i<=10;i++)
	{
		if(n==0)
		break;
		else scanf("%d",&a[i]);
	}
	for(int i=10;i>=1;i--)
	{
		if(a[i]!=0) printf("%d ",a[i]);
	}
	printf("\n");
}
```
## 第一題
```c
#include <stdio.h>
int main()
{
	int n1=10, n2=20, n3=30;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	int *p=&n1;
	*p=200;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);
	
	return 0;
}
```
## 第二題
```c
#include <stdio.h>
int main()
{
	int n1=10, n2=20, n3=30;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	int *p=&n1;
	*p=200;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	int *p2=&n3;
	*p2=300;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	p2=p;
	*p2=400;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);
	
	return 0;
}
```
## 第三題
```c
#include <stdio.h>
int main()
{
	int n1=10, n2=20, n3=30;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	int *p=&n1;
	*p=200;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);

	int *p2=&n3;
	*p2=300;
	printf("n1:%d n2:%d n3:%d\n", n1,n2,n3);


	
	return 0;
}

```
## 第四題
```c
#include <stdio.h>
int main()
{
	int n[3]={10, 20, 30};
	printf("n[0]:%d n[1]:%d n[2]:%d\n", n[0],n[1],n[2]);

	int *p=&n[0];
	*p=200;
	printf("n[0]:%d n[1]:%d n[2]:%d\n", n[0],n[1],n[2]);

	

	int *p2=&n[2];
	*p2=300;
	printf("n[0]:%d n[1]:%d n[2]:%d\n", n[0],n[1],n[2]);

	p2=p;
	*p2=400;
	printf("n[0]:%d n[1]:%d n[2]:%d\n", n[0],n[1],n[2]);


	
	return 0;
}
```

