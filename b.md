---
title: 代码块测试
categories: 测试文章
date: 2021-11-11 19:24:00
description: 测试文章
abbrlink: 1
---
## 测试代码块

```java
package Test;


public class ArrayUtilTest {
	public static void main(String[] args) {
		Arrayutil util=new Arrayutil();
		int[] arr=new int[]{32,34,33,6,2,-88,-25,9,0};
		int max=util.getMax(arr);
		System.out.println("最大值为："+max);
		
	    System.out.println("排序前：");
	    util.print(arr);
	    util.sort(arr);
	   System.out.println("排序后：");
	   util.print(arr);
	   
	   System.out.println("查找：");
	 
	}
	
}

```

