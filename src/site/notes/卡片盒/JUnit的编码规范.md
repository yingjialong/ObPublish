---
{"dg-publish":true,"dg-permalink":"/ObPublish/OP1666002880","permalink":"/ObPublish/OP1666002880/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false,"dgShowInlineTitle":false}
---


### 类名 ： 
定义测试类，类名是由被测试类名 Test 构成。例如：CalculatorTest
### 包名： 
定义的测试类需要放在 xxx.xxx.xxx.test 包中。例如：package com.mylifes1110.test;
### 方法名： 
测试方法的方法名有两种定义方式 test 测试方法和测试方法。例如：testAdd 和 add
### 返回值：
因为我们的方法只是在类中测试，可以独立运行，所以不需要处理任何返回值，所以这里使用 void。例如：public void add();
### 参数列表： 
因为我们的方法是用来测试的，至于参数列表的传入是没有必要的。我们在测试的时候自行传入需要的参数测试即可。所以在此参数列表为空。例如：例如：public void add();
### @Test 注解： 
测试是需要运行来完成的。如果我们只有一个 main 方法，显然在结构上还是需要我们去注释掉测试过的。解决此问题这里我们需要在测试方法上方加@Test 注解来完成测试，只要是加该注解的方法，可以单独运行此方法来完成测试。
### @Test 注解 jar 包 Junit4、5：
@Test 注解是需要我们导入 jar 包才能使用的。jar 包有两个分别是：junit-4.13-rc-2 和 hamcrest-core-1.3。这里我使用的是 Junit4，单元测试还有 Junit5，版本差异我没有做了解。主要是可以完成测试才是硬道理！
### IDEA 快捷导入 Junit4、5： 
我们可以先创建测试类和方法，然后在测试方法上方加入@Test 注解，此时 IDEA 显示的@Test 注解是飘红的，这时候我们使用 Alt + Enter 组合键来打开导入 Junit 单元测试列表，然后再选择 Junit4 或者 Junit5 确定即可导入成功！这时候再查看注解就没有飘红了！











---
*citation*:: 
*reference*:: 
*relation*:: 