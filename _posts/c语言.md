# C语言笔记

## 1.c语言基本格式

1.创建一个后缀为.c的文件

![image-20230817114156866](C:\Users\chenshuo\AppData\Roaming\Typora\typora-user-images\image-20230817114156866.png)

2.输入c语言的标准模板

```c
#include<stdio.h>
int main() 
{

	return 0;
}
```

## 2.注释

作用：解释代码内容（充当笔记），**被注释后的代码不会被执行**

分类：

1.单行注释

```c
//
```

2.多行注释

```c
/*


*/
```

## 3.第一个程序Hello world

```c
#include<stdio.h>
int main() 
{	
	printf("Hello world!");
	return 0;
}
```

