# diyige
第一个
Training


Java training class

summer 2015.

Teaching Schedule


72%



No.

Course

Time(days)

Date


1 HTML
CSS
HTML+CSS 6 0829/0830/0912/0913/0919/0920 
2 Java SE 6 1017/1018/1024/1025/1031/1101 
3 JavaScript
jQuery 2 1107/1107 
4 Database 4 1114/1115/1121/1122 
5 Java EE
AJAX
JSON 5 1128/1129/1205/1206/1212 
6 Java EE Frameworks 7 1213/1219/1220
1226/1227/0102/0103 
7 Android 6 0109/0110/0116/0117/0123/0124 
8 Exam 1 0130 
HTML


教学要求
1.掌握常用 HTML 元素
2.构建语义合理的网页


课外参考
1.W3 School
2.Head First HTML与CSS(第2版)


Outline
1.引言
2.HTML 核心基础
3.DOM
4.HTML 常用元素

Chapter 2 核心基础


Source code:
<h1 style="color:#f00;">Hello,HTML!</h1>



5个概念
1.元素 element  h1 
2.标记 tag ◦起始标记 start tag  <h1 style="color:#f00;"> 
◦结束标记 end tag  </h1> 

3.属性 attribute  style 
4.值例 value  color:#f00; 
5.内容 content  Hello,HTML! 

Chapter 3 DOM

JavaScript HTML DOM Navigation


Source code:
<html>
  <head>
    <title>DOM Tutorial</title>
  </head>
  <body>
    <h1>DOM Lesson one</h1>
    <p>Hello world!</p>
  </body>
</html>


From the HTML above you can read:
• <html> is the root node 
• <html> has no parents 
• <html> is the parent of <head> and <body> 
• <head> is the first child of <html> 
• <body> is the last child of <html> 

and:
• <head> has one child: <title>; 
• <title> has one child (a text node): "DOM Tutorial" 
• <body> has two children: <h1> and <p> 
• <h1> has one child: "DOM Lesson one" 
• <p> has one child: "Hello world!" 
• <h1> and <p> are siblings 

Chapter 4 常用元素

Block Elements and Inline Elements
•Block-level Element◦A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).◾ <div> 
◾ <h1> - <h6> 
◾ <p> 
◾ <form> 


•Inline Element◦An inline element does not start on a new line and only takes up as much width as necessary.◾ <span> 
◾ <a> 
◾ <img> 



Elements
•html
•head
•meta
•title
• link 
• script 
• style 
•body
•div
•span
•h1~h6
•p
•a
•img
•pre
•br
•ul li
•ol li
•dl dt dd
•table tr th td
•form
•input
•select
•textarea
•button
•!doctype
•html entity

###############

CSS

教学要求
1.根据设计图，结合 HTML 制作样式美观的网页
2.提高要求：处理跨浏览器兼容性问题


课外参考
1.W3 School
2.CSS ZEN GARDEN


Outline
1.引言
2.核心基础
3.选择器
4.盒子模型
5.浮动
6.定位
7.布局
8.常用样式
9.预处理器



Practice makes perfect.

#########
Chapter 1 引言


Cascading Style Sheets

Hello,CSS!


Source code:
<!-- index.html -->
<h1>Hello,CSS!</h1>

/* style.css */
h1 {
    color: #f00;
}

###################################
Chapter 2 核心基础


Source code
/* style.css */
h1 {
    color: #f00;
}



4个概念
1.选择器 selector  h1 
2.样式声明 declaration  color: #f00; 
3.样式属性 property  color 
4.样式值 value  #f00 
##################################################
Chapter 3 选择器

CSS 的 3 种使用方式

1.内联样式  Inline Styles 


Source code
 <!-- index.html -->
 <h1 style="color: #f00;">headline...</h1>



2.内部样式  Internal Style Sheet 


Source code
 <!-- index.html -->
 <head>
     <style>
         h1 {
             color: #f00;
         }
     </style>
 </head>
 <body>
 <h1>headline...</h1>
 </body>



3.外部样式  External Style Sheet 


Source code
 /* style.css */
 h1 {
     color: #f00;
 }

 <!-- index.html -->
 <head>
     <link href="style.css">
 </head>
 <body>
 <h1>headline...</h1>
 </body>



CSS 选择器
•基本选择器◦标记(元素/标签)选择器
◦class 选择器
◦id 选择器

•复合选择器◦交集选择器
◦并集选择器
◦派生选择器


锚点的伪类  pseudo-class 
- `link`
- `visited`
- `hover`
- `active`


 其他重要的伪类 
 ####################################################
 Chapter 4 Box model

1.box 无处不在


2.box 的并列关系和嵌套关系



preview



margin


border


padding

content 




Source code
<!-- html -->
<div>
    content
</div>

div {
    background: #ddd;
    border: 20px solid #cfc;
    height: 50px;
    margin: 50px;
    pading: 30px;

}
##############################
Chapter 5 Float
•标准流的概念
•浮动改变了什么
•图文混排的实现
•清除浮动  clear 

•塌缩  collapse  的解决


Source code
  <!-- index.html -->
  <div>
      <div id="d1">div1...</div>
      <div id="d2">div2...</div>
      <div id="d3">div3...</div>
      <div class="clear"></div>
  </div>

  /* style.css */
  .clear {
      clear: both;
  }

  #d1,
  #d2,
  #d3 {
      float: left;
}

######################################
Chapter 6 Position & display & visibility

 position 
•静态定位◦标准流

•相对定位◦没有脱离标准流
◦相对于自己原来的位置

•绝对定位◦脱离了标准流
◦相对于距离它 最近的 已定位 的 祖先元素 ◾已定位 指  position  值不是  static 


•固定定位◦脱离了标准流
◦相对浏览器的最左上角

• z-index  ◦对于已定位元素，值越大越靠近上边


 display 
• inline  块级变行内
• block  行内变块级
• inline-block  对外行内，对内块级
• none  不显示且不保留位置

 visibility 
• hidden  不显示但保留位置
##################################################
Chapter 7 Layout
•从外向内 & 从大到小
• box model  的观点
•居中的一种方法  margin: auto; 
######################################
Chapter 8 常用样式
•background◦background-color
◦background-image
◦background-repeat
◦background-attachment
◦background-position

•color
•text-aline◦ text-aline: center;  内容水平居中

•text-decoration
• text-transform 
•text-indent
• vertial-aline 
•line-height◦ line-height: height;  内容垂直居中

•font-family
•font-style
•font-size
•font-weight
•list-style◦list-style-type
◦list-style-position
◦list-style-image

•border◦border-color
◦border-style
◦border-width

•margin ◦margin-top
◦margin-right
◦margin-bottom
◦margin-left

•padding ◦padding-top
◦padding-right
◦padding-bottom
◦padding-left

•width◦min-width
◦max-width

•height◦min-height
◦max-height

•display
•visibility
•position
•z-index
•float
•clear
• overflow 
•cursor
#############################################
Chapter 9 Preprocessor
1.Sass◦http://sass-lang.com

2.Less◦http://lesscss.org

3.Stylus◦http://learnboost.github.com/stylus

#####################################################
JavaScript


教学要求
1.JavaScript 基本语法
2.JavaScript 与 Java 的异同


课外参考
1.W3 School
###################################################
jQuery


教学要求
1.jQuery 基本使用


课外参考
1.W3 School
###############################################
Bootstrap

W3 School
############################################
Java SE


教学要求
1.初步理解面向对象的程序设计


课外参考
1.Java SE API
2.Java编程思想(第4版)


Outline
1.引言
2.语言基础
3.面向对象
4.集合类
5.泛型
6.异常
7.IO
8.附：练习题


补充内容
1. 内部类
2. 集合框架
3. 注释类型
4. 序列化
5. 反射
6. 多线程

###########################################################
chapter 1 引言
1.参考
2.学习方法◦项目导向

3.About Java◦自然语言
◦计算机语言发展◾1GL  二进制机器语言


◾2GL LLL Low Level Language  低级计算机语言
  eg. 汇编语言


◾3GL HLL High Level Language  高级计算机语言
  eg. Java C C++ Delphi Basic Python PHP VC C# VB


◾4GL  第四代计算机语言 
  SQL



◦Java历史◾1991 SUN Green Project
◾1995 Java published
◾Java 语言的版本◾Java Standard Edition
◾Java Enterprise Edition
◾Java Micro(Mobile) Edition  Android
  iOS




◦Java特性◾Write once, Run anywhere  跨平台



◦程序分类◾Application 应用程序
◾App-let 小应用程序  pig-let
  lake-let




4.开发环境◦JDK Java Development Kit
◦Java DOC


5.Hello,world!
 // Hello.java
 public class Test {
 //    psvm + Tab
 //    sout + Enter
     public static void main(String[] args) {
         System.out.println("Hello,world!");
     }
 }

◦Java 程序◾编辑
◾编译
◾运行

◦java 源文件
◦class 类文件/字节码文件


6.Java VM
◦Write once,run anywhere.

###############################################
chapter 2 语言基础

1.标识符和关键字

◦标识符


用来起名的字符
◾包括字母/数字/下划线/美元符号  $ 
◾首字符不能是数字
◾区分大小写
◾不能是关键字以及  true / false 


◦Java 命名规范
◾类名  首字母大写，第二个单词起首字母大写


◾方法名，变量名，参数名  首字母小写，第二个单词起首字母大写


◾ switch / case  中  default  后要写  break 
◾ if  后语句体只有一个，也要写 {} 


◦关键字

◾被 Java 语言占用的一些单词，不能作为标志符


Java 关键字表


类别

关键字

说明

访问控制 private 私有的 
protected 受保护的 
public 公共的 
类、方法和变量修饰符 abstract 声明抽象 
class 类 
extends 扩允，继承 
final 终极，不可改变的 
implements 实现 
interface 接口 
native 本地 
new 新，创建 
static 静态 
strictfp 严格，精准 
synchronized 线程，同步 
transient 短暂 
volatile 易失 
程序控制语句 break 跳出循环 
continue 继续 
return 返回 
do 运行 
while 循环 
if 如果 
else 否则 
for 循环 
instanceof 实例 
switch 根据值选择执行 
case 定义一个值以供 switch 选择 
default 默认 
错误处理 assert 断言表达式是否为真 
catch 捕捉异常 
finally 有没有异常都执行 
throw 抛出一个异常对象 
throws 声明一个异常可能被抛出 
try 捕获异常 
包相关 import 引入 
package 包 
基本类型 boolean 布尔型 
byte 字节型 
char 字符型 
double 双精度浮点 
float 单精度浮点 
int 整型 
long 长整型 
short 短整型 
null 空 
变量引用 super 父类，超类 
this 本类 
void 无返回值 
保留关键字 goto 是关键字，但不能使用 




2.数据类型、直接量和变量
◦数据类型 ◾基本数据类型◾布尔类型  boolean 
◾基本数值类型◾定点类型◾字节  byte 
◾字符  char 
◾短整型  short 
◾整形  int 
◾长整型  long 

◾浮点类型◾单精度浮点数  float 
◾双精度浮点数  double 



◾引用数据类型◾类
◾接口
◾枚举
◾数组


◦变量◾类型
◾名字
◾值
◾存储单元

◦直接量◾基本数据类型直接量◾ char  的直接量◾1 整数（0～65535）
◾'a' 单个字符
◾'\t' 转义字符
◾'\123' 3位八进制字符
◾'\u4E00' 4位十六进制字符，unicode字符


◾字符串直接量
◾ null  一切引用数据类型的直接量



3.运算符

◦算术运算符

◾+


+ 在数值与字符串中的运算规则
  + 的运算顺序是从左至右，其他类型与字符串的 + 为字符串拼接


◾−
◾*
◾/ 整数除法，截去余数。注意先后的区别
◾++ 自增运算
◾−− 自减运算。注意先后的区别
◾% 模运算，求余。符号只与被除数有关

◦关系运算符◾>
◾<
◾>=
◾<=
◾== 可用于任意类型比较
◾!= 可用于任意类型比较


◦布尔逻辑运算符
◾& 逻辑与
◾| 逻辑或
◾^ 异或
◾! 非
◾&& 条件与

◾|| 条件或


短路规则
  &&
  ||
  第一个表达式即可确定运算结果时，不再判断第二个表达式
  使用短路规则与否，可能副作用不同



◦位运算符
◦赋值类运算符◾=
◾+=
◾-=
◾×=
◾/=
◾%=
◾&= 针对布尔值
◾|= 针对布尔值
◾^= 针对布尔值

◦条件运算符◾(condition)?(ture value):(false value) 三目运算符


◦其他运算符
◾ ( 类型 )  强制类型转换
◾ .  引用
◾ []  数组

◾ ()  改变运算优先级，推荐使用


Java 的运算优先级
  非 > 算术 > 关系 > 与 > 或 > 赋值


◾ instanceof 
◾ new 



4.控制结构

◦程序运行的控制结构
◾顺序结构

◾选择结构
◾ if 

◾ if / else ( if )
  注意 `else` 有无的区别



◾ switch / case 


可用于  switch  的变量类型
  byte char int short enum String(JDK 1.7+) 



◾循环结构◾ for 
◾ while 
◾ do / while 

◾ break  跳出当前这一个循环
◾ continue  跳出当前这一次循环


##################################################
chapter 3 面向对象的程序设计


OOP 

Object Oriented Programming

1.类、域、方法、对象
◦类  class  /  type  ◾抽象的概念
◾对世界上万事万物的一种抽象和概括
◾分类的依据◾有相同的特征或属性
◾有相同的行为或功能

◾类 = 属性 + 功能
◾ 类 = 域 + 方法 
◾类是创建对象的模板
◾类的定义[public] class 类名[<类型参数列表>] [类型参数列表 extends 父类型 & 父类型 & ...] [implents 接口名列表] {
  // 类体
}




◦域  field 
◾一类事物共有的特征或属性
◾域和方法常常紧密关联

◾域的定义


等同于变量的定义

直接定义在类体中
  访问限定修饰符 类型名 域名;




◦方法  method 
◾一类事物共有的行为或功能
◾方法的定义访问限定修饰符 返回类型 方法名(参数列表) [throws 受检异常类列表] {
  // 方法体
}



◾参数列表


用  ,  间隔开多个参数

◾ void  方法没有返回值
◾ return  返回控制

◾构造方法  constructor 
◾与类同名
◾没有返回类型
◾初始化成员域

◾类的默认构造方法
◾没有参数

◾没有方法体


初始化类的域为默认值
i.布尔类型默认值  false 
ii.基本数值类型  0  或  0.0 
iii.引用数据类型  null 


◾如果显示声明的构造方法，默认构造方法将不存在
◾ this  指代当前类


◦对象/实例/实例对象  instance  ◾具体的
◾类来生成
◾ new  创建或生成一个类的对象，总是调用类的构造方法



2.继承  inherit 
◦ extends  继承/扩展

◦子类  extends(继承)  父类

◾子类拥有父类的域和方法


注意父类成员的访问限定修饰符
i.父类的  default  成员，只有同包子类可继承
ii.父类的  private  成员，不能继承


◾子类可以有自己的域和方法


◦ super  指代父类
◦子类可以隐式调用父类的默认构造方法
◦子类必须显式调用父类的有参构造方法
◦子类要显示调用父类构造方法时，必须在第一行调用
◦Java 语言里，类是单继承的（接口可以多继承）
◦ instanceof  判断对象是否是类的实例

3.多态  polymorphism  ◦静态多态性◾同一个类内部（也可以发生于子类和父类之间）
◾同名方法的重载  overload 
◾参数不同◾类型不一样
◾数量不一样
◾顺序不一样

◾类的构造方法之间都是重载

◦动态多态性◾子类和父类之间
◾子类重写  overwrite  /覆盖  override  了父类的方法（有相同的声明）
◾子类是否调用、子类在何处调用父类的方法根据方法的定义和需求确定


4.包  package  ◦管理代码的目录结构
◦通常都是公司或组织或学校域名的反写
◦包名都是小写字母
◦所有的类都要放在包里
◦ package  打包语句，必须是类里的第一行代码
◦ import  导包语句
◦Java 的包◾java.lang Java 的语言包，使用这个包的类不需要导入  common sense 



5.封装  encapsulation 
◦访问限定修饰符◾类的访问限定修饰符◾ default class  只有同包的其他类可访问
◾ public class  外包的类可访问，需导入，常用

◾类成员的访问限定修饰符◾ private  私有的，只有同一个类内部可访问
◾ default  默认的，只有同一个包内部可访问
◾ protected  受保护的，外包中子类的实例对象可访问
◾ public  共有的，外包可访问



◦成员域一般都是私有的


隐藏内部的数据


◦成员方法一般都是公有的


为外部提供访问的接口


◦封装的含义


6. abstract  ◦抽象：抽取“像”的部分
◦可以修饰类和方法
◦抽象类◾抽象的类不能实例化
◾抽象的类是用来被扩展的
◾抽象类的子类必须实现抽象类中所有的抽象方法

◦抽象方法◾抽象的方法没有实现
◾抽象的方法必须声明在抽象类中
◾在抽象类的子类中被实现


7. static  ◦静态
◦可以修饰域和方法
◦静态的成员隶属于 类对象 
◦静态方法中只能直接引用静态成员

8. final  ◦终态
◦可以修饰类、域和方法
◦终态的类不能再被子类化
◦终态的域◾只能在声明时或构造方法中被初始化
◾初始化之后值不能再被修改

◦终态的方法不能在子类中被重写
◦静态并终态的域◾只能在声明时初始化
◾初始化之后值不能再被修改
◾常量，都是大写字母，单词之间用下划线  _  分隔


9.接口  interface  ◦与类处于同一个级别
◦接口的定义[public] 接口名[<类型参数列表 extends 父类型 & 父类型 & ...>] [extends 接口名称列表] {
  // 接口体
}


◦接口可以定义域和方法◾接口的域都是公有常量
◾接口的方法都是公有抽象方法

◦接口没有构造方法，不能实例化
◦接口是用来被实现的  implements 
◦类实现接口必须实现接口的所有抽象方法
◦Java 中，一个类可以实现多个接口
◦抽象类与接口之间的联系和区别◾相同点◾都不能实例化
◾都可以定义抽象方法
◾对于他们的子（实现）类做了限制和约束

◾不同点◾抽象类可以定义具体方法，接口不能
◾类只能继承一个抽象类，可以实现多个接口


◦接口本身可以继承  extends  多个父接口

10. 内部类 
11.变量作用域范围◦变量（方法）产生作用的有效范围
◦类作用域范围◾类的起始  {  到类的终止  } 
◾类的域和方法

◦块  block  作用域范围◾从变量声明之处，到当前块结束之处
◾方法中的局部变量  local variable ，方法的参数，循环的变量

◦方法内的局部变量可以覆盖同名的域

12.参数传递方式◦值传递◾方法的参数是基本数据类型

◦引用传递◾方法的参数是引用数据类型
◾传递的是地址的值
◾方法中的改变会影响实际参数
◾注意：String类型以及基本数据类型的封装类是特例（还是值传递）


#####################################################################
Chapter 4 集合


 集合  或  容器  是 Java 中存放数据的重要数据结构

要掌握不同集合类型的  CRUD   Create Retrieve Update Delete  操作和时空复杂度

1.数组
◦同一种类型的值的集合

◦数组是静态的


数组初始化之后，元素的个数不变


◦声明和初始化
数据类型[] 数组名 = new 数据类型[元素的个数];// {元素1, 元素2, ... };


◦下标（索引）  index 

◦二维数组


注意每行列数不同的二维数组


◦多维数组

◦数组循环时，推荐使用  length 


2.字符串  java.lang.String 


字符串初始化后，其值不能改变
◦ String  的重要方法◾构造方法
◾charAt
◾concact
◾contains
◾endsWith
◾equals
◾equalsIgnoreCase
◾format
◾getBytes
◾indexOf
◾isEmpty
◾lastIndexOf
◾length
◾matches
◾replace
◾replaceAll
◾replaceFirst
◾split
◾startWith
◾subString
◾toCharArray
◾toLowerCase
◾toUpperCase
◾valueOf

◦字符串缓冲区  java.lang.StringBuffer  ◾append
◾delete
◾insert
◾reverse

◦ StringBuilder 

3.向量  java.util.Vector  ◦ Vector  的重要方法◾add
◾get
◾size
◾clear


4.哈希表  java.util.Hashtable  ◦ Hashtable  中  key  是唯一的
◦ for-each  循环  iter + Tab 
◦ Hashtable  的重要方法◾put
◾get
◾size
◾clear
◾keySet


5. 集合框架 
#########################################################
Chapter 5 泛型


since Java JDK 5

generic 泛化的，通用的，一般的

1.类型参数列表
 class(interface) 类名（接口名）<类型参数列表 extends 父类型 & 父类型 & ...> {...}



类型参数的命名
 E - Element (used extensively by the Java Collections Framework)
 K - Key
 V - Value
 N - Number
 T - Type
 S,U,V etc. - 2nd, 3rd, 4th types



2.泛型的类

3.泛型的接口
##############################################################
Chapter 6 异常处理

1.异常的产生


2.异常的分类
 java.lang.Object
     java.lang.Throwable
         java.lang.Error
         java.lang.Exception
             java.lang.RuntimeException
             java.io.IOException
             java.*.*Exception


◦非受检异常


RuntimeException类及其子类是非受检异常


◦受检异常


Exception类中除了RuntimeException之外的其他异常类及其子类


◦非受检异常可以通过编译，可能在运行时产生

◦受检异常不能通过编译，必须对其进行处理◾受检异常的处理方式i.使用  try  /  catch  包围
ii.在方法中声明这个异常  throws 




3.异常的处理
 try {
     // 可能产生异常的语句块
 } catch (ExceptionType exceptionType) {
     // 异常的处理
 } finally {
     // 其他的处理
 }

◦ try  后面必须有  catch  或  finally 
◦ catch  可以有多个
◦ finally  最多只能有一个
◦ try  内一旦发生异常， try  内这条语句后的代码都不再执行，无论异常有没有被  catch 
◦ finally  语句块总是会被执行
◦异常的处理方式◾输出异常信息  e.printStackTrace(); 
◾退出程序  System.exit(0) 



4.显示抛出异常  throw 

######################################################################
Chapter 7 Stream & File

1. InputStream  /  OutputStream  /  Reader  /  Writer 


都是抽象类，注意需要  close() 

输入输出是对程序而言的
◦ InputStream  ◾基于 字节 的输入流

◦ OutputStream  ◾基于 字节 的输出流

◦ Reader  ◾基于 字符 的输入流

◦ Writer  ◾基于 字符 的输出流



2. RandomAccessFile 


基本取代  DataInputStream  和  DataOutputStream 
 public class DataInputStream
 extends FilterInputStream
 implements DataInput

 public class DataOutputStream
 extends FilterOutputStream
 implements DataOutput

 public class RandomAccessFile
 extends Object
 implements DataOutput, DataInput, Closeable



3. BufferedInputStream  /  BufferOutputStream  /  BufferedReader  /  BufferedWriter 


提高输入输出效率 
◦ bufferedReader.readLine() 


4. File 
◦ File  指代文件  file  或目录  directory 
◦ File  不处理文件内容，只处理文件或目录的周边信息
◦ File  常用方法◾ canRead 
◾ canWrite 
◾ createNewFile 
◾ delete 
◾ deleteOnExit 
◾ getAbsoluteFile 
◾ getAbsolutePath 
◾ getName 
◾ getParent 
◾ getParentFile 
◾ getPath 
◾ getTotalSpace 
◾ getUsableSpace 
◾ isAbsolute 
◾ isDirectory 
◾ isFile 
◾ isHidden 
◾ lastModified 
◾ length 
◾ list 
◾ listFiles 
◾ listRoots 
◾ mkdir 
◾ mkdirs 
◾ renameTo 
◾ setLastModified 
◾ setReadable 
◾ setReadOnly 
◾ setWritable 


######################################################################
附：练习题


第一次习题： 2， 3， 4， 5， 6， 7， 9， 10， 11，34

第二次习题：12， 13， 14， 15， 16， 18， 19，25， 27

1.古典问题：有一对兔子，从出生后第3个月起每个月都生一对兔子，小兔子长到第三个月后每个月又生一对兔子，假如兔子都不死，问每个月的兔子总数为多少？


2.判断101-200之间有多少个素数，并输出所有素数。素数：只能被1和它本身整除的正整数（1不是素数）
 public class E2 {
     public static void main(String[] args) {
         int counter = 0;
         for (int i = 101; i < 200; i++) {
             boolean b = true;
             for (int j = 2; j < i/2 + 1; j++) {
                 if (i % j == 0) {
                     b = false;
                     break;
                 }
             }
             if (b) {
                 System.out.println(i);
                 counter++;
             }
         }
         System.out.println("total: " + counter);
     }
 }

 /*
 101
 103
 107
 109
 113
 127
 131
 137
 139
 149
 151
 157
 163
 167
 173
 179
 181
 191
 193
 197
 199
 total: 21
 */



3.打印出所有的“水仙花数”，所谓“水仙花数”是指一个三位数，其各位数字立方和等于该数本身。例如：153是一个“水仙花数’，因为153=1的三次方＋5的三次方＋3的三次方。
 public class Test {

     public static void main(String[] args) {
         for (int i = 100; i < 1000; i++) {
             int hundred = i / 100;// 百位上的数字
             int ten = i % 100 / 10;// 十位上的数字
             int single = i % 10;// 个位上的数字
 //            if (i == Math.pow(hundred, 3) + Math.pow(ten, 3) + Math.pow(single, 3)) {
             if (i == (hundred * hundred * hundred + ten * ten * ten + single * single * single)) {
                 System.out.println(i);
             }
         }
     }
 }

 /*
 153
 370
 371
 407
 */



4.将一个正整数分解质因数。例如：输入90，打印出90=2*3*3*5。


5.利用条件运算符的嵌套来完成此题：学习成绩>=90分的同学用A表示，60-89分之间的用B表示，60分以下的用C表示。


6.输入两个正整数m和n，求其最大公约数和最小公倍数。


7.输入一行字符，分别统计出其中英文字母、空格、数字和其它字符的个数。


8.求s=a+aa+aaa+aaaa+aa…a的值，其中a是一个数字。例如2+22+222+2222+22222(此时共有5个数相加)，几个数相加有键盘控制。


9.一个数如果恰好等于它的因子之和，这个数就称为’完数’。例如6=1＋2＋3.编程 找出1000以内的所有完数。


10.一球从100米高度自由落下，每次落地后反跳回原高度的一半；再落下，求它在第10次落地时，共经过多少米？第10次反弹多高？


11.有1、2、3、4个数字，能组成多少个互不相同且无重复数字的三位数？都是多少？1.程序分析：可填在百位、十位、个位的数字都是1、2、3、4。组成所有的排列后再去 掉不满足条件的排列。


12.企业发放的奖金根据利润提成。利润(I)低于或等于10万元时，奖金可提10%；利润高于10万元，低于20万元时，低于10万元的部分按10%提成，高于10万元的部分，可可提成7.5%；20万到40万之间时，高于20万元的部分，可提成5%；40万到60万之间时高于40万元的部分，可提成3%；60万到100万之间时，高于60万元的部分，可提成1.5%，高于100万元时，超过100万元的部分按1%提成，从键盘输入当月利润I，求应发放奖金总数？


13.一个整数，它加上100后是一个完全平方数，再加上168又是一个完全平方数，请问该数是多少？


14.输入某年某月某日，判断这一天是这一年的第几天？(闰年： 西元年份除以400余数为0的，或者除以4为余数0且除以100不为余数0的，为闰年。)


15.输入三个整数x，y，z，请把这三个数由小到大输出。


16.输出9*9口诀。


17.猴子吃桃问题：猴子第一天摘下若干个桃子，当即吃了一半，还不瘾，又多吃了一个第二天早上又将剩下的桃子吃掉一半，又多吃了一个。以后每天早上都吃了前一天剩下的一半零一个。到第10天早上想再吃时，见只剩下一个桃子了。求第一天共摘了多少。


18.两个乒乓球队进行比赛，各出三人。甲队为a，b，c三人，乙队为x，y，z三人。已抽签决定比赛名单。有人向队员打听比赛的名单。a说他不和x比，c说他不和x，z比，请编程序找出三队赛手的名单。


19.打印出如下图案（菱形）
   x
  xxx
 xxxxx
xxxxxxx
 xxxxx
  xxx
   x



要求只使用以下三种语句
1. System.out.print(" ")
2. System.out.print("x");
3. System.out.println("x")



20.有一分数序列：2/1，3/2，5/3，8/5，13/8，21/13…求出这个数列的前20项之和。


21.求1+2!+3!+…+20!的和。


22.利用递归方法求5!。


23.有5个人坐在一起，问第五个人多少岁？他说比第4个人大2岁。问第4个人岁数，他说比第3个人大2岁。问第三个人，又说比第2人大两岁。问第2个人，说比第一个人大两岁。最后问第一个人，他说是10岁。请问第五个人多大？


24.给一个不多于5位的正整数，要求：一、求它是几位数，二、逆序打印出各位数字。


25.一个5位数，判断它是不是回文数。即12321是回文数，个位与万位相同，十位与千位相同。


26.请输入星期几的第一个字母来判断一下是星期几，如果第一个字母一样，则继续 判断第二个字母。


27.求100之内的素数。


28.对10个数进行排序。


29.求一个3*3矩阵对角线元素之和。


30.有一个已经排好序的数组。现输入一个数，要求按原来的规律将它插入数组中。


31.将一个数组逆序输出。


32.取一个整数a从右端开始的4～7位。


33.打印出杨辉三角形（要求打印出10行如下图）
    1
  1 2 1
 1 3 3 1
.........（略）



34.随机生成[1， 20]数10000次，使用两种方法实现（java.lang.Math，java.util.Random），并判断两种方法的效率和分布。


35.输入数组，最大的与第一个元素交换，最小的与最后一个元素交换，输出数组。


36.有n个整数，使其前面各数顺序向后移m个位置，最后m个数变成最前面的m个数。


37.有n个人围成一圈，顺序排号。从第一个人开始报数（从1到3报数），凡报到3的人退出圈子，问最后留下的是原来第几号的那位。


38.写一个函数，求一个字符串的长度，在main函数中输入字符串，并输出其长度。


39.编写一个函数，输入n为偶数时，调用函数求1/2+1/4+…+1/n，当输入n为奇数时，调用函数1/1+1/3+…+1/n(利用指针函数)


40.字符串排序。


41.海滩上有一堆桃子，五只猴子来分。第一只猴子把这堆桃子凭据分为五份，多了一个，这只猴子把多的一个扔入海中，拿走了一份。第二只猴子把剩下的桃子又平均分成五份，又多了一个，它同样把多的一个扔入海中，拿走了一份，第三、第四、第五只猴子都是这样做的，问海滩上原来最少有多少个桃子？


42.809*??=800*??+9*??+1 其中??代表的两位数，8*??的结果为两位数，9*??的结果为3位数。求??代表的两位数，及809*??后的结果。


43.求[0, 7]所能组成的奇数个数。


44.一个偶数总能表示为两个素数之和。


45.判断一个素数能被几个9整除。


46.两个字符串连接程序。


47.读取7个数[1, 50]的整数值，每读取一个值，程序打印出该值的个数。


48.某个公司采用公用电话传递数据，数据是四位的整数，在传递过程中是加密的，加密规则如下：每位数字都加上5，然后用和除以10的余数代替该数字，再将第一位和第四位交换，第二位和第三位交换。


49.计算字符串中子串出现的次数。


50.有五个学生，每个学生有3门课的成绩，从键盘输入以上数据（包括学生号，姓名，三门课成绩），计算出平均成绩，况原有的数据和计算出的平均分数存放在磁盘文件”stud”中

####################################################################
Database


教学要求
1.SQL 语言
2.基本数据库设计


课外参考
1.W3 School
2.MySQL 5.6 Reference Manual (GA)


Outline
1.引言
2.数据库安装
3.SQL 语言
4.附：数据库设计
####################################################################
Chapter 1 引言
1.历史发展◦人工管理
◦文件管理◾超大规模数据

◦数据库◾不适于超大规模数据
◾不适于超大规模并发


2.数据库

3.RDBMS


Relational Database Management System 关系型数据库管理系统

Entity Relationship
◦Oracle
◦MySQL
◦SQL Server
◦PostgreSQL
◦DB2
◦Access

◦SQLite


◦ SQL 


Structural Query Language



4.NoSQL


key - value
◦MongoDB
◦Cassandra
◦Redis

#######################################3
Chapter 2 数据库安装

1.MySQL

◦upzip to your_mysql_directory/


◦Edit configuration file


your_mysql_directory/my-small.ini
  [mysqld]
  default-character-set=utf8
  default-storage-engine=innodb



◦Install


CMD your_mysql_directory/bin
  mysqld --install your_mysql_service_name --defaults-file=your_mysql_directory\my-small.ini

  (if your_mysql_directory include spaces,use double quotation marks)



◦Start or stop MySQL
  run > services.msc

  or:

  CMD
  net start your_mysql_service_name
  net stop your_mysql_service_name



◦Delete service
  SC delete your_mysql_service_name



◦Update MySQL password


CMD your_mysql_directory/bin
  mysql -u root -p

  update mysql.user set password = PASSWORD('your_new_password') where user='root';
  flush privileges;



###########################################################
Chapter 3 SQL 语言

1.DDL


Data Defination Language
◦SQL Create DB
◦SQL 数据类型
◦SQL Create Table
◦SQL Drop

◦SQL Constraints
◾SQL Not Null
◾SQL Unique

◾SQL Primary Key
id  int(11) UNSIGNED AUTO_INCREMENT PRIMARY KEY ,        



◾SQL Foreign Key

◾主表 父表（主键所在的表） / 从表 子表（外键所在的表）
[CONSTRAINT [symbol]] FOREIGN KEY
  [index_name] (index_col_name, ...)
  REFERENCES tbl_name (index_col_name,...)
  [ON DELETE reference_option]
  [ON UPDATE reference_option]

reference_option:
  RESTRICT | CASCADE | SET NULL | NO ACTION




◾SQL Check  MySQL 

◾SQL Default

◦SQL Increment
◦SQL Alter 

◦SQL Create Index
CREATE INDEX ind_test ON demo.table_test (test);
SHOW INDEX FROM demo.table_test;
DROP INDEX ind_test ON demo.table_test;




2.DML


Data Manipulate Language
◦SQL insert
◦SQL update

◦SQL delete


temporarily disable a foreign key constraint in MySQL
Try DISABLE KEYS or

mysql>SET FOREIGN_KEY_CHECKS=0;

make sure to

mysql>SET FOREIGN_KEY_CHECKS=1;

after.



MySQL dupm and import
dump:
mysqldump -u user -p database_name > file_name.sql

import:
mysql>source file_name.sql




3.DQL


Data Query Language
◦SQL select
◦SQL distinct

◦SQL where


行检索


◦SQL AND & OR

◦SQL Order By
◦SQL Top  limit 
◦SQL Like 
◦SQL 通配符  %   _ 
◦SQL In
◦SQL Between And
◦SQL Aliases
◦SQL Nulls◾ is null / is not null 

◦SQL ifnull(,) 
◦SQL Join
◦SQL Inner Join
◦SQL Left Join
◦SQL Right Join
◦SQL Full Join  union  
◦SQL Union
◦SQL Select Into 

◦SQL View


被存储的查询
CREATE [OR REPLACE] VIEW v_test
[AS]
SELECT * FROM test;

show tables;

show create view scott.v_test;



◦子查询


查询的嵌套


◦简单视图
◾『简单查询』生成的，可以修改基表的数据

◦复杂视图◾『复杂查询』生成的，不可以修改基表的数据



4.DTL


Data Transaction Language 事务处理

ACID
◦原子性（Atomicity）
◦一致性（Consistency）
◦隔离性（Isolation）

◦持久性（Durability）
START TRANSACTION; # 开启一次事务

DML... 

COMMIT; # 提交
ROLLBACK; # 回滚
DDL 隐式结束事务

SAVEPOINT save_point_name; # 设置保留点
ROLLBACK TO save_point_name; # 回滚到保留点




5.SQL 函数

◦aggregate 聚合函数
◾SQL max()
◾SQL min()
◾SQL avg()
◾SQL sum()
◾SQL count()
◾SQL first()
◾SQL last()

◾SQL Group By


GROUP BY cloumn_name

把 column_name 列值相同的分为一组


◾SQL Having


组检索



◦标量函数 
◾SQL Date
◾SQL ucase()
◾SQL lcase()
◾SQL mid()
◾SQL len()
◾SQL round()
◾SQL now()
◾SQL format()


####################################################3
Chapter 4 数据库设计

1.NF
◦Normal Forms 范式

◦1NF


没有复义的列，列值唯一


◦2NF


行可以被唯一区分


◦3NF


不能有冗余的列

表的列值不能包含其他表的非主关键字值



2.Demo

◦word
test
  英 [test]  美 [test]

  n.考验；试验；测试
  vt.试验；测试；接受测验

  用作名词 (n.)
  We achieved within seven months an agreement that has stood the test of time.
  我们在七个月内完成一项协议,而且经受住了时间的考验。
  Our test flight was to discover the bugs in the new plane.
  试验飞行是为了发现新飞机有何毛病。
  Tomorrow we'll have a history test.
  明天我们将进行历史测验。

  用作及物动词 (vt.)
  By doing so, you can test the strength of steel.
  这样做,你可以试验一下钢的强度。
  Listening to his continuous stream of empty chatter really tested my patience.
  听他那没完没了的连篇空话对我的耐心真是一大考验。



◦root / affix (prefix infix suffix)
-let
  suffix
1.小的
applet
servlet

-dis
  suffix
1.不，无，相反
dislike
disagree
2.取消，除去，毁
disforest
disroot
3.加在含有“分开”，“否定”等意义的单词之前，表示加强意义
dispart
dissemination
4.分开，离，散
dissect
dissolve
5.有时写作-di
dispirit
divert

-ition
  suffix
1.名词后缀
supposition
competition
2.表示情况，状态
audition
dentition



##################################################
：练习题

Sample database structure


Table  emp 


Field

Type

Null

Key

Default

Extra


EMPNO int(4) NO PRI NULL  
ENAME varchar(10) YES  NULL  
JOB varchar(9) YES  NULL  
MGR int(4) YES  NULL  
HIREDATE date YES  NULL  
SAL double(7,2) YES  NULL  
COMM double(7,2) YES  NULL  
DEPTNO int(2) YES MUL NULL  


Table  dept 


Field

Type

Null

Key

Default

Extra 


DEPTNO int(2) NO PRI NULL  
DNAME varchar(14) YES  NULL  
LOC varchar(13) YES  NULL  


Table  salgrade 


Field

Type

Null

Key

Default

Extra 


GRADE int(11) YES  NULL  
LOSAL int(11) YES  NULL  
HISAL int(11) YES  NULL  

PART I
•# 1. 查找部门30中员工的详细信息。
SELECT *
FROM scott.emp
WHERE DEPTNO = 30

•# 2. 找出从事clerk工作的员工的编号、姓名、部门号。
SELECT
  EMPNO,
  ENAME,
  DEPTNO
FROM scott.emp
WHERE JOB = 'clerk'

•# 3. 检索出奖金多于基本工资的员工信息。
SELECT *
FROM scott.emp
WHERE COMM > SAL

•# 4. 检索出奖金多于基本工资60%的员工信息。
SELECT *
FROM scott.emp
WHERE COMM > SAL * 0.3

•# 5. 希望看到10部门的经理或者20部门的职员(clerk)的信息。
SELECT *
FROM scott.emp
WHERE (DEPTNO = 10 AND JOB = 'manager') OR (DEPTNO = 20 AND JOB = 'clerk')

•# 6. 找出10部门的经理、20部门的职员或者既不是经理也不是职员但是工资(基本工资 + 奖金)高于2000元的员工信息。
SELECT *
FROM scott.emp
WHERE (DEPTNO = 10 AND JOB = 'manager') OR (DEPTNO = 20 AND JOB = 'clerk') OR
      (JOB NOT IN ('manager', 'clerk') AND (sal + ifnull(COMM, 0)) > 2000)

•# 7. 找出获得奖金的员工的工作。
SELECT DISTINCT job
FROM scott.emp
WHERE COMM > 0

•# 8. 找出奖金少于100或者没有获得奖金的员工的信息。
SELECT *
FROM scott.emp
WHERE COMM < 100 OR COMM IS NULL

•# 9. 查找员工雇佣日期中当月的最后一天雇佣的。
SELECT *
FROM scott.emp
WHERE HIREDATE = last_day(HIREDATE);

•# 10. 检索出雇佣年限超过12年的员工信息。
SELECT *
FROM scott.emp
WHERE date_add(HIREDATE, INTERVAL 1 YEAR) > now();

UPDATE scott.emp
SET HIREDATE = '2014-11-22
WHERE ENAME = 'king';

•# 11. 找出姓名以A、B、S开始的员工信息。
SELECT *
FROM scott.emp
WHERE substr(ENAME, 1, 1) IN ('a', 'b', 's');

SELECT *
FROM scott.emp;

•# 12. 找到名字长度为7个字符的员工信息。
SELECT *
FROM scott.emp
WHERE length(ENAME) = 4;

•# 13. 名字中不包含R字符的员工信息。
SELECT *
FROM scott.emp
WHERE ENAME NOT LIKE '%r%';

•# 14. 找出员工名字的前3个字符。
SELECT substr(ename, 1, 3)
FROM scott.emp;

•# 15. 将名字中A改为a。
SELECT replace(ename, 'A', 'a')
FROM scott.emp;

•# 16. 将员工的雇佣日期拖后10年。
SELECT date_add(hiredate, INTERVAL 10 YEAR)
FROM scott.emp;

•# 17. 返回员工的详细信息并按姓名排序。
SELECT *
FROM scott.emp
ORDER BY ENAME;

•# 18. 返回员工的信息并按员工的工作年限降序排列。
SELECT *
FROM scott.emp
ORDER BY HIREDATE;

•# 19. 返回员工的信息并按工作降序工资升序排列。
SELECT *
FROM scott.emp
ORDER BY JOB DESC, SAL + ifnull(COMM, 0);

•# 20. 返回员工的姓名、雇佣年份和月份并且按月份和雇佣日期排序。
SELECT
  ename,
  hiredate,
  extract(YEAR FROM hiredate)  year,
  extract(MONTH FROM hiredate) month
FROM scott.emp
ORDER BY extract(MONTH FROM hiredate), HIREDATE;

•# 21. 计算员工的日薪(按30天)。
SELECT round((sal + ifnull(COMM, 0)) / 30, 2)
FROM scott.emp;

•# 22. 找出2月份雇佣的员工。
SELECT *
FROM scott.emp
WHERE extract(MONTH FROM HIREDATE) = 2;

•# 23. 至今为止，员工被雇佣的天数。
SELECT datediff(now(), hiredate)
FROM scott.emp;

•# 24. 找出姓名中包含A的员工信息。
SELECT *
FROM scott.emp
WHERE ENAME LIKE '%a%';

•# 25. 计算出员工被雇佣了多少年、多少月、多少日。
# ?


PART II
•# 1. 返回拥有员工的部门名、部门号。
SELECT DISTINCT
  d.DEPTNO,
  d.DNAME
FROM scott.dept d, scott.emp e
WHERE e.DEPTNO = d.DEPTNO;

•# 2. 工资水平多于smith的员工信息。
SELECT *
FROM scott.emp
WHERE sal + ifnull(COMM, 0) >
      (
        SELECT sal + ifnull(COMM, 0)
        FROM scott.emp
        WHERE ENAME = 'scott'
      );

•# 3. 返回员工和所属经理的姓名。
SELECT
  e1.ENAME,
  e2.ENAME
FROM scott.emp e1, scott.emp e2
WHERE e1.MGR = e2.EMPNO;

•# 4. 返回雇员的雇佣日期早于其经理雇佣日期的员工及其经理姓名。
SELECT
  e1.ENAME,
  e2.ENAME
FROM scott.emp e1, scott.emp e2
WHERE e1.MGR = e2.EMPNO AND e1.HIREDATE < e2.HIREDATE;

•# 5. 返回员工姓名及其所在的部门名称。
SELECT
  e.ename,
  d.dname
FROM scott.emp e, scott.dept d
WHERE e.DEPTNO = d.DEPTNO;

•# 6. 返回从事clerk工作的员工姓名和所在部门名称。
SELECT
  e.ename,
  d.dname
FROM scott.emp e, scott.dept d
WHERE e.DEPTNO = d.DEPTNO AND JOB = 'clerk';

•# 7. 返回部门号及其本部门的最低工资。
SELECT
  deptno,
  min(sal + ifnull(comm, 0))
FROM scott.emp
GROUP BY DEPTNO;

•# 8. 返回销售部sales所有员工的姓名。
SELECT e.ename
FROM scott.emp e, scott.dept d
WHERE e.DEPTNO = d.DEPTNO AND d.DNAME = 'sales';

•# 9. 返回工资水平多于平均工资的员工。
SELECT *
FROM scott.emp
WHERE sal + ifnull(COMM, 0) >
      (
        SELECT avg(sal + ifnull(COMM, 0))
        FROM scott.emp
      );

•# 10. 返回与SCOTT从事相同工作的员工。
SELECT *
FROM scott.emp
WHERE job =
      (
        SELECT job
        FROM scott.emp
        WHERE ENAME = 'scott'
      );

•# 11. 返回与30部门员工工资水平相同的员工姓名与工资。
SELECT
  ENAME,
  sal + ifnull(COMM, 0)
FROM scott.emp
WHERE sal + ifnull(COMM, 0) = (
  SELECT avg(sal + ifnull(COMM, 0))
  FROM scott.emp
  WHERE DEPTNO = 30
);

•# 12. 返回工资高于30部门所有员工工资水平的员工信息。
SELECT *
FROM scott.emp
WHERE sal + ifnull(COMM, 0) > (
  SELECT avg(sal + ifnull(COMM, 0))
  FROM scott.emp
  WHERE DEPTNO = 30
);

•# 13. 返回部门号、部门名、部门所在位置及其每个部门的员工总数。
SELECT
  d.deptno,
  d.dname,
  d.loc,
  count(e.deptno)
FROM scott.emp e RIGHT OUTER JOIN scott.dept d
    ON e.DEPTNO = d.DEPTNO
GROUP BY e.DEPTNO;

•# 14. 返回员工的姓名、所在部门名及其工资。
SELECT
  e.ename,
  d.dname,
  e.sal + ifnull(e.comm, 0)
FROM scott.emp e, scott.dept d
WHERE e.DEPTNO = d.DEPTNO;

•# 15. 返回雇员表中不在同一部门但是从事相同工作的员工信息。
SELECT
  e1.ename,
  e1.job,
  e1.deptno,
  e2.ename,
  e2.job,
  e2.deptno
FROM scott.emp e1, scott.emp e2
WHERE e1.DEPTNO <> e2.DEPTNO AND e1.JOB = e2.JOB;

•# 16. 返回员工的详细信息，包括部门名。
SELECT
  e.*,
  d.dname
FROM scott.emp e, scott.dept d
WHERE e.DEPTNO = d.DEPTNO;

•# 17. 返回员工工作及其从事此工作的最低工资。
SELECT
  job,
  min(sal + ifnull(comm, 0))
FROM scott.emp
GROUP BY JOB;

•# 18. 返回不同部门经理的最低工资。
SELECT min(sal + ifnull(comm, 0))
FROM scott.emp
WHERE JOB = 'manager'
GROUP BY DEPTNO;

•# 19. 计算出员工的年薪，并且以年薪排序。
SELECT (sal + ifnull(comm, 0)) * 12
FROM scott.emp
ORDER BY 1;

•# 20. 返回工资处于第四级别的员工的姓名。
SELECT
  e.ename,
  e.sal + ifnull(e.comm, 0),
  s.LOSAL,
  s.HISAL
FROM scott.emp e, scott.salgrade s
WHERE e.sal + ifnull(e.comm, 0) BETWEEN s.LOSAL AND s.HISAL AND s.GRADE = 4;

###################################################
Java EE


教学要求
1.HTTP 协议原理
2.基本 Web 开发


课外参考
1.Java EE API


Outline
1.引言
2.JSP 语法
3.JSP 内建对象
4.Servlet
5.JSTL
6.Filter Listener
7.JDBC
8.附：Server
#########################################################
Chapter 1 引言

1.JSP


Java Server Pages 


2.Servlet


servlet


3.JSP & Servlet


JSP 的本质是 Servlet， Servlet 的本质是 Class


4.环境配置
◦应用服务器◾[PDF] the great java app server debate

◦JSP 和 Servlet 的 Container 容器

◦Tomcat

tomcat
◾unzip apache-tomcat-7.0.65-windows-x86 to your_tomecat_directory

◾Windows

◾set environment variable:

your_tomcat_directory/bin/setclasspath.bat
  set JAVA_HOME=your_jdk_directory



◾run or shutdown:

your_tomcat_directory/bin/
  startup.bat

  or

  shutdown.bat




◾browser:
  localhost:8080
  127.0.0.1:8080
  your_ip:8080





5.JSP Hello,world！


6.HTTP(s)


Hyper Text Transfer Protocol 超文本传输协议

###################################################################
Chapter 2 JSP 语法

1.一个典型的JSP


classic.jsp
 <!doctype html>
 <%@ page language="java" contentType="text/html; charset=UTF-8" %>
 <!--这是一个典型的JSP，它包含了JSP中常用的元素-->
 <%!
     String getDate() {
         return new java.util.Date().toString();
     }
     int count = 10;
 %>
 <html>
 <head><title>一个典型的JSP</title></head>
 <body>
 <jsp:include page="header.jsp"/>
 <div style="text-align: center">
     <table style="margin: 0 auto;">
         <tr style="background: #777;">
             <th>----------------</th>
         </tr>
         <%
             // color表示颜色，通过它来动态控制颜色。
             String c1 = "#9cf", c2 = "#8c3";
             for (int i = 0; i < count; i++) {
                 String color;
                 if (i % 2 == 0) {
                     color = c1;
                 } else {
                     color = c2;
                 }
                 out.println("<tr style=\"background:" + color + ";\"><td>----------------</td></tr>");
             }
         %>
     </table>
     <hr/>
     当前的时间是：
     <%-- 下面是使用表达式的例子 --%>
     <%=getDate()%>
 </div>
 </body>
 </html>



header.jsp
 <%@ page language="java" contentType="text/html; charset=utf-8" %>
 <div style="text-align: center">
     <hr/>
     JSP的典型例子
     <hr/>
 </div>



2.JSP 页面元素
i.注释◾HTML 注释  <!-- comment... --> 
◾JSP 隐藏注释  <%-- comment... --%> 
◾Java 注释  // comment /* comment */ 

ii.模板元素◾静态 HTML 元素

iii.脚本元素◾声明  declaration   <%! %>  class 类体内
◾小脚本  scriplet   <% %>  _jspService() 方法体内
◾表达式  expression   <%= %>  out.print() 方法的参数

iv.指令元素  <%@ %>  ◾page 指令
◾include 指令
◾taglib 指令  JSTL 

v.动作元素  <jsp:include page="header.jsp"/> 


3.JSP 的本质是 Java Class

##########################################################
Chapter 3 JSP 内建对象


 Implicit Object  JSP 内建/内置/隐藏/隐含/隐式 对象
•out

• request  请求


request 封装了用户的所有请求信息
1. getParameter()  获取用户填写的表单参数
2. getParameterValues()  获取用户填写的表单参数(多选下拉列表/复选框)
3. getRemoteAddr()  
4. getSession() 
5. setAttribute() 
6. getAttribute() 
7. request.getRequestDispatcher().forward()  页面跳转  forwrad  转发


• response  响应
1. sendRedirect()  页面跳转  redirect  重定向
2.转发 与 重定向◾都可以实现页面的跳转
◾转发不改变地址，重定向改变地址
◾转发可以保存 request 范围内的属性，重定向不能

3.表单提交方式 get 和 post◾都可以提交表单参数
◾get 会在地址栏中显示表单参数与值，post 不会
◾get 提交参数有最大长度限制，post 没有
◾注：来自于连接的请求都是  get  



• session  会话
1.web 应用中，属性的存在范围◾pageContext
◾request
◾session
◾application

2. setAttribute() 
3. getAttribute() 
4. getId()  ◾HTTP stateless 无状态性

5. invalidate() 

•application1. setAttribute() 
2. getAttribute() 

•pageContext1. setAttribute() 
2. getAttribute() 

•page
•config
•exception
#############################################################
Chapter 4 Servlet


服务器端小程序

1. Servlet 


扩展了  javax.servlet.http.HttpServlet  的类


2. Servlet  用来： 


接收请求

处理请求

返回响应


3.注解式配置
 @WebServlet(urlPatterns="/your_pattern")



4.Refactoring 重构


在不改变软件系统外部行为的前提下，改善其内部代码结构

###################################################################
Chapter 5 Filter & Listener

1. Filter 
◦过滤器
◦ javax.servlet.Filter 

◦注解式配置
  @WebFilter(
      urlPatterns="your_pattern", 
      initParams=@WebInitParam=(name="your_key", value="your_value"))




2. Listener 
◦监听器

◦注解式配置
  @WebListener



◦ request  相关监听器接口
i.ServletRequestListener
ii.ServletRequestAttributeListener

◦ session  相关监听器接口i.HttpSessionListener
ii.HttpSessionActivationListener
iii.HttpSessionAttributeListener
iv.HttpSessionBindingListener
v.HttpSessionIdListener

◦ application  相关监听器接口i.ServletContextListener
ii.ServletContextAttributeListener


################################################################
Chapter 5 EL & JSTL


Expression Language

JSP Standard Tag Library

•EL 表达式语言
1. ${expression} 

2.get attribute
  Page           pageScope
  Request        requestScope
  Session        sessionScope
  Application    applicationScope




•JSTL JSP 标准标记库


build.grdle
  compile 'jstl:jstl:1.2'



*.jsp
  <%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>

1.core 核心标签◾c:out
◾c:set
◾c:remove
◾c:catch
◾ c:if 
◾ c:choose  用来包含  c:when  或  c:otherwise 
◾ c:when  在  c:choose  中，至少有一个，可以有多个
◾ c:otherwise  在  c:choose  中，可有可无
◾c:import
◾ c:forEach 
◾c:forTokens
◾c:param
◾ c:redirect 
◾c:url

2.fn 函数
3.fmt 格式化
4.sql 数据库
5.xml xml

################################################################
Chapter 7 JDBC


Java Database Connectivity

1.SQL Injection 


SQL 注入 

#########################################################
附：Web / Application servers
1.Tomcat
2.JBoss
3.Jetty
4.GlassFish
###############################################
AJAX
教学要求
1.掌握使用 jQuery 的 AJAX 相关函数进行异步操作

课外参考
1.jQuery AJAX
Outline
1.引言
2.jQuery AJAX
###################################################
Chapter 1 引言
Asynchronous JavaScript And XML
###################
Chapter 2 jQuery AJAX
• $.ajax() 
#############################################3
JSON


教学要求
1.掌握  JSON  的数据结构
2.掌握  Java  和  JavaScript  常用的  JSON  库


课外参考
1.http://json.org
Outline
1.引言
2.数据结构
3.常用库
#########################################################
Chapter 1 引言
JavaScript Object Notation
###############################################3
Chapter 2 数据结构
1. object   {"key":value,} 
2. array   [value,] 
3. value   string   number   object   array   ture   false   null 
4. string 
5. number 
###########################################
Chapter 3 常用库

•Java

1. org.json 
 // build.gradle
 compile 'org.json:json:20151123'

 // object to json
 JSONObject jsonObject = new JSONObject(model);
 String json = jsonObject.toString(4);

 // json to object



2. Jackson JSON Processor 


gradlew dependencies
 // build.gradle
 compile 'com.fasterxml.jackson.core:jackson-databind:2.5.3'


 ObjectMapper objectMapper = new ObjectMapper();
 objectMapper.configure(SerializationFeature.INDENT_OUTPUT, true);

 // object to json
 String json = objectMapper.writeValueAsString(model);

 // json to object
 Model model = objectMapper.readValue(json, Model.class);



3. Google-gson 
 // build.gradle
 compile 'com.google.code.gson:gson:2.5'

 Gson gson = new GsonBuilder().setPrettyPrinting().create();

 //  object to json
 String json = gson.toJson(model); 

 // json to object
 Model model = gson.fromJson(json, Model.class);



4. fastjson 
 // build.gradle
 compile 'com.alibaba:fastjson:1.2.7'

 // object to json
 String json = JSON.toJSONString(model);

 // json to object
 Model model = JSON.parseObject(json, Model.class);




•JavaScript

##################################################################3
MyBatis


教学要求
1.掌握使用 MyBatis 进行数据持久化开发
2.初步了解 MyBatis 的实现原理


课外参考
1.mybatis 3.3.0 API


Outline
1.引言
2.核心组件
3.配置
4.XML SQL 映射
5.Annotation SQL 映射
6.高级特性
################################################################
Chapter 1 引言
1.MyBatis 的作用◦工作于数据持久层
◦对 JDBC 进行封装

2.MyBatis 的特性◦学习曲线低
◦配置灵活
◦便于优化

######################################################

Chapter 2 核心组件


Mapper / Configuration / Mapper Interface / SqlSessionFactory / SqlSession / Service

1.Create database and table
 DROP DATABASE IF EXISTS test;
 CREATE DATABASE test;

 # user
 DROP TABLE IF EXISTS test.user;
 CREATE TABLE test.user
 (
   id       INT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
   username VARCHAR(255),
   password VARCHAR(255)
 );



2.Update build.gradle
 compile 'org.mybatis:mybatis:3.3.0'



3.Create model class
 public class User implements Seriable {
     private Integer id;
     private String username;
     private String password;

     // setters and getters
 }



4.Create mapper.xml


注意：在使用  Mapper  接口时，  namespace  的取值是  Mapper  接口的全限定名
 <?xml version="1.0" encoding="UTF-8"?>
 <!DOCTYPE mapper
         PUBLIC "-//mybatis.org//DTD Mapper 3.0//EN"
         "http://mybatis.org/dtd/mybatis-3-mapper.dtd">
 <mapper namespace="mapper.UserMapper">
     <insert id="create" parameterType="model.User" useGeneratedKeys="true" keyProperty="id">
         INSERT INTO user VALUES (NULL, #{username}, #{password})
     </insert>
 </mapper>



5.Create mybatis-config.xml
 <?xml version="1.0" encoding="UTF-8"?>
 <!DOCTYPE configuration
         PUBLIC "-//mybatis.org//DTD Config 3.0//EN"
         "http://mybatis.org/dtd/mybatis-3-config.dtd">
 <configuration>
     <properties resource="jdbc.properties"/>
     <environments default="dev">
         <environment id="dev">
             <transactionManager type="JDBC"/>
             <dataSource type="POOLED">
                 <property name="driver" value="${driver}"/>
                 <property name="url" value="${url}"/>
                 <property name="username" value="${username}"/>
                 <property name="password" value="${password}"/>
             </dataSource>
         </environment>
     </environments>
     <mappers>
         <mapper resource="user-mapper.xml"/>
     </mappers>
 </configuration>

 # jdbc.properties
 driver = com.mysql.jdbc.Driver
 url = jdbc:mysql:///test
 username = your_username
 password = your_password



6.Create MyBatisSession sigleton class 
 public class MyBatisSqlSession { 
     private static SqlSessionFactory sqlSessionFactory;

     private static SqlSessionFactory getSqlSessionFactory() { 
         if (sqlSessionFactory == null) {
             try { 
                 sqlSessionFactory = new SqlSessionFactoryBuilder().build(Resources.getResourceAsStream("mybatis-config.xml"));
             } catch (IOException e) {
                 e.printStackTrace();
             } 
         } 
         return sqlSessionFactory;
     } 

     public static SqlSession getSqlSession(boolean autoCommit) {
         return getSqlSessionFactory().openSession(autoCommit);
     } 
 }



7.Create mapper interface
 public interface UserMapper { 

     int create(User user);
 }



8.Create service class
 public class UserService {

     // create record by XML configuration
     private static int createUserViaXML() {
         try (SqlSession sqlSession = MyBatisSqlSession.getSqlSession(true)) {
             return sqlSession.insert("mapper.UserMapper.create", new User{"Tester1", "password1"});
         }
     }

     // create record by Mapper interface
     private static int createUser() {
         try (SqlSession sqlSession = MyBatisSqlSession.getSqlSession(true)) {
             UserMapper userMapper = sqlSession.getMapper(UserMapper.class);
             return userMapper.create(new User{"Tester2", "password2"});
         }
     }

     public static void main(String[] args) {
         createUserviaXML(); // MyBatis method 1
         createUser(); // MyBatis method 2: Type Safer
     }
 }



9.Create JUnit test class
     // ...


########################################################################3
Chapter 3 配置

1. mybatis-config.xml 


使用 XML 文件进行配置的方式
 <?xml version="1.0" encoding="UTF-8"?>
 <!DOCTYPE configuration
 PUBLIC "-//mybatis.org//DTD Config 3.0//EN"
 "http://mybatis.org/dtd/mybatis-3-config.dtd">
 <configuration>
     <properties resource="application.properties">
         <property name="username" value="your_username"/>
         <property name="password" value="your_password"/>
     </properties>
     <settings>
         <setting name="cacheEnabled" value="true"/>
     </settings>
     <typeAliases>
         <typeAlias alias="user" type="model.User"/>
         <package name="model"/>
     </typeAliases>
     <typeHandlers>
         <typeHandler handler="typehandler.YourTypeHandler"/>
         <package name="typehandler"/>
     </typeHandlers>
     <environments default="development">
         <environment id="development">
             <transactionManager type="JDBC"/>
             <dataSource type="POOLED">
                 <property name="driver" value="${jdbc.driverClassName}"/>
                 <property name="url" value="${jdbc.url}"/>
                 <property name="username" value="${jdbc.username}"/>
                 <property name="password" value="${jdbc.password}"/>
             </dataSource>
         </environment>
         <environment id="production">
             <transactionManager type="MANAGED"/>
             <dataSource type="JNDI">
                 <property name="data_source" value="java:comp/jdbc/MyBatisDemoDataSource"/>
             </dataSource>
         </environment>
     </environments>
     <mappers>
         <mapper resource="user-mapper.xml"/>
         <mapper url="file:///absolute_path/user-apper.xml"/>
         <mapper class="mapper.UserMapper"/>
     </mappers>
 </configuration>


◦ Environment 
◾每个数据环境定义为一个  environment 
◾ environment  的 id 表明数据环境的不同用途，如  development  /  test  /  production  等
◾通过  environments  的  default  属性指定当前的数据环境

◾一个应用程序可以使用多个数据环境
  // use default environment
  inputStream = Resources.getResourceAsStream("mybatis-config.xml");
  defaultSqlSessionFactory = new SqlSessionFactoryBuilder().build(inputStream);

  // use environment a
  aSqlSessionFactory = new SqlSessionFactoryBuilder().build(inputStream, "environment-id_a");

  // use environment b
  bSqlSessionFactory = new SqlSessionFactoryBuilder().build(inputStream, "environment-id_b");



◾每个  environment  中须定义  transactionManager  和  dataSource 


◦ Datasource  ◾ dataSource  主要用来指定数据库连接属性
◾ dataSource  的  type  属性可以为以下 3 种值i. UNPOOLED  ◾每次数据库操作创建一个新的连接，操作结束关闭连接
◾适用于用户少的系统

ii. POOLED  ◾数据库连接池方式，每次操作从池中取出一个连接，操作结束放回池中
◾适用于大多数开发或测试场景

iii. JNDI  ◾从  JNDI  数据源中取得数据库连接
◾适用于生产环境



◦ TransactionManager  ◾ MyBatis  支持两种事务管理方式i. JDBC  ◾应用程序负责事务处理
◾使用  commit / rollback  等方式进行事务处理
◾使用  JdbcTransactionFactory  创建  TransactionManager 
◾如使用  Tomcat  部署的应用程序

ii. MANAGED  ◾应用服务器负责事务处理
◾使用  ManagedTransactionFactory  创建  TransactionManager 
◾如使用  JBoss / WebLogic / GlassFish 



◦ Properties  ◾指定属性文件
◾属性文件以  key - value  方式存储属性信息
◾ properties  中可以使用  property  元素设置默认属性信息，会被属性文件的同名属性覆盖


◦ TypeAliases 
◾类型别名
◾简化  mapper  中的全限定名  Fully Qualified Name 
◾如果指定  package   name  会自动注册包中的类型为全部小写的别名

◾还可以用  @alias  注解指定一个类型的别名，这种方式覆盖  typeAliases  元素的设置
@Alias("specified-alias")
public class Model {}




◦ TypeHandlers 
◾ MyBatis  内置类型处理器能够处理的类型◾基本数据类型及其封装类
◾byte[]
◾java.util.Date / java.sql.Date / java.sql.Time / java.sql.TimeStamp
◾java enums


◾对其他特定类型，需要使用类型处理器进行类型转换

i.扩展  BaseTypeHandler<T>  抽象父类
 public YourCustomTypeHandler extends BaseTypeHandler<CustomType> {
 }



ii.在  mybatis-config.xml  中注册类型处理器
 <typeHandlers>
     <typeHandler handler="your.package.YourCustomTypeHandler"/>
 </typeHandlers>





◦ Settings 

◾ MyBatis  默认全局设定
<settings>
  <setting name="cacheEnabled" value="true"/>
  <setting name="lazyLoadingEnabled" value="true"/>
  <setting name="multipleResultSetsEnabled" value="true"/>
  <setting name="useColumnLabel" value="true"/>
  <setting name="useGeneratedKeys" value="false"/>
  <setting name="autoMappingBehavior" value="PARTIAL"/>
  <setting name="defaultExecutorType" value="SIMPLE"/>
  <setting name="defaultStatementTimeout" value="25000"/>
  <setting name="safeRowBoundsEnabled" value="false"/>
  <setting name="mapUnderscoreToCamelCase" value="false"/>
  <setting name="localCacheScope" value="SESSION"/>
  <setting name="jdbcTypeForNull" value="OTHER"/>
  <setting name="lazyLoadTriggerMethods" value="equals,clone,hashCode,toString"/>
</settings>




◦ Mappers 
◾配置  Mapper XML  文件的路径◾ resource  定义  classpath  映射文件
◾ url  定义全限定文件系统路径或网络  URL 
◾ class  定义映射接口
◾ package  映射接口所在的包路径




2. Java API 


使用 Java API 的方式进行配置
 public static SqlSessionFactory getSqlSessionFactory() {
     SqlSessionFactory sqlSessionFactory = null;
     try{
         DataSource dataSource = DataSourceFactory.getDataSource();
         TransactionFactory transactionFactory = new JdbcTransactionFactory(); // new ManagedTransactionFactory();
         Environment environment = new Environment("development", transactionFactory, dataSource);
         Configuration configuration = new Configuration(environment);
         configuration.getTypeAliasRegistry().registerAlias("user", User.class);
         configuration.getTypeHandlerRegistry().register(YourTypeHandler.class,YourTypeHandler.class);
         configuration.addMapper(UserMapper.class);
         sqlSessionFactory = new SqlSessionFactoryBuilder().build(configuration);
     } catch (Exception e){
         throw new RuntimeException(e);
     }
     return sqlSessionFactory;
 }

 public class DataSourceFactory {
     public static DataSource getDataSource() {
         String driver = "com.mysql.jdbc.Driver";
         String url = "jdbc:mysql:///test";
         String username = "your_username";
         String password = "your_password";
         PooledDataSource dataSource = new PooledDataSource(driver, url, username, password);
         return dataSource;
     }
 }
##########################################################################################
Chapter 4 XML SQL Mapping
1.Mapper XML
2.Mapper interface
3.CRUD◦Insert
◦Delete
◦Update
◦Select

4.ResultMap
5.Association◦one to one
◦one to many

6.Dynamic SQL
############################################################################3

Chapter 5 Annotation SQL mapping
########################################3
Spring


教学要求
1.理解 Spring IoC 机制
2.掌握 Spring MVC 框架


课外参考
1.Spring Framework Reference Documentation
2.Spring Framework 4.2.4.RELEASE API


Outline
1.引言
2.Ioc / DI
3.Spring MVC
#################################################################33
Chapter 1 引言


Spring overview

Spring overview
1.Spring Framework
2.IoC / DI
3.Spring MVC
4.AOP
#####################################################
Chapter 2 IoC / DI


Inversion of Control Containers and the Dependency Injection pattern

by Martin Fowler
• strong coupling  强耦合：◦高层应用类 依赖于 底层模块类
◦底层模块类 控制 高层应用类
◦底层有改变，高层应用类有大量的代码级更改

• loose coupling  松散耦合◦高层应用类 不依赖于 底层模块类
◦底层模块类 不能控制 高层应用类C
◦底层有改变，高层应用类不需要做代码级更改 


• Inversion of Control  控制关系的反转


从 松散耦合 到 强耦合 的  decoupling  解耦 过程中，实现了控制关系的反转C


•Spring IoC
1. Constructor  Injection
2. Setter  Injection

####################################################################
Chapter 3 Spring MVC

1.update build.gradle
 compile 'commons-fileupload:commons-fileupload:1.3.1'
 compile 'org.springframework:spring-webmvc:4.2.4.RELEASE'



2.update web.xml
 <!-- Spring DispatcherServlet -->
 <servlet>
     <servlet-name>web</servlet-name>
     <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
 </servlet>
 <!-- mapping -->
 <servlet-mapping>
     <servlet-name>web</servlet-name>
     <url-pattern>/</url-pattern>
 </servlet-mapping>

 <!-- Spring ContextLoaderListener -->
 <listener>
 <listener-class>org.springframework.web.context.ContextLoaderListener</listener-class>
 </listener>

 <!-- Spring applicationContext.xml Location -->
 <context-param>
     <param-name>contextConfigLocation</param-name>
     <param-value>classpath:applicationContext.xml</param-value>
 </context-param>



3.create WEB-INF/DispatcherServlet_name-servlet.xml
 <?xml version="1.0" encoding="UTF-8"?>
 <beans xmlns="http://www.springframework.org/schema/beans"
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
        xmlns:context="http://www.springframework.org/schema/context"
        xmlns:mvc="http://www.springframework.org/schema/mvc"
        xsi:schemaLocation="
        http://www.springframework.org/schema/beans
        http://www.springframework.org/schema/beans/spring-beans.xsd
        http://www.springframework.org/schema/context
        http://www.springframework.org/schema/context/spring-context.xsd
        http://www.springframework.org/schema/mvc
        http://www.springframework.org/schema/mvc/spring-mvc.xsd">

     <mvc:annotation-driven />
     <context:component-scan base-package="controller" />

     <bean id="multipartResolver" class="org.springframework.web.multipart.commons.CommonsMultipartResolver"/>
     <bean class="org.springframework.web.servlet.view.InternalResourceViewResolver">
         <property name="prefix" value="/"/>
         <property name="suffix" value=".jsp"/>
     </bean>
 </beans>



4.create Controller
 @Controller
 @RequestMapping("/user")
 public class UserController {

     @RequestMapping("/add")
     private void add() {
         // ...
         System.out.println("add...");
     }


########################################################################3






































































































































