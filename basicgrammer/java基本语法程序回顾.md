# while语句基本原理

## 1到5的累加和，while循环语句基本原理

package com.imooc.flow1;



public class PlusDemo {



​	public static void main(String[] args) {

​		// 1-5的累加和

​		int n=1;

​		int sum=0;//sum是存放和的变量

​		while(n<=5) {

​			sum=sum+n;

​			n++;

​		}

​		System.out.println("all:"+sum);



​	}



}

## 打印字母a-z 中间换行

package com.imooc.flow1;



public class CharDemo {



​	public static void main(String[] args) {

​		// 循环打印26英文字母 分两行

​		char ch='a';

​		int cnt=1;///输出字符a时候cnt=1

​		while(ch<='z') {

​			System.out.print(ch+"");

​			if(cnt%13==0)

​				System.out.println();

​			ch++;//循环的字符顺序 a->b->c->......

​			cnt++;//换行用，计数到13时换行

​		}



​	}



}

### do while

package com.imooc.flow1;



public class DoWhileDemo {



​	public static void main(String[] args) {

​		// do while求1到5的累加和

​		int n=1;

​		int sum=0;

​		do {

​			sum+=n;

​			n++;

​			

​		}while(n<=5);

​		System.out.println("sum="+sum);



​	}



}



## 循环嵌套

### 打印数列

public static void main(String[] args) {

​		Scanner sc= new Scanner(System.in);

​		System.out.print("m-->");

​		int m=sc.nextInt();

​		System.out.print("n-->");

​		int n=sc.nextInt();

​		int r=1;

​		while(r<=m) {

​			System.out.print("o");

​		

​		int c=1;

​		while(c<=n) {

​		System.out.print("o");

​		c++;

​		

​	}

​		System.out.println();

​		r++;

}

​	}

}

m-->3
n-->5
ooooo
ooooo
ooooo
