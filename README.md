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
