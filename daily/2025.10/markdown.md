# Markdown 的使用
## 段落的划分  
第一段（插入文本）  
第二段（插入文本）需要**双空格加回车**或者**双回车**
## 文本的处理
**填入要加粗的文本**  
*填入要变成斜体的文本*  
***填入既要加粗也要斜体的文本***  
~~填入要加删除线的文本~~  
对不同段之间加入分割线：第一段（插入文本）
***
第二段（插入文本）
___
第三段（插入文本）
## 标题的处理
#的个数加空格表示第几级标题（最多六级标题）
## 列表的使用
* 我是第一项任务
* 我是第二项任务

**或者（+ -）但是不可以混用，混用代表新列表的创立，混用也可以用tab键交错建立**
1. 我是第一项任务
2. 我是第二项任务（有序列表）  

* [ ] 第一项待完成的任务
* [x] 第二项完成的任务S

## 代码块的使用
    public class Main{
        public static void main(String[] args){
            System.out.println("Hello World");
        }
    }  
```java
public class Main{
    public static void main(String[] args){
        System.out.println("Hello World");
    }
} 
```  
在字符串里面插入代码块用`equal()`方法  
## 引用用法
>（引用的内容）
> >（引用的内容）  
  
## 插入
**插入超链接**  
[百度](https://baidu.com)或者[百度](a)  
[a]：https://baidu.com  
**插入图片链接**  
![图片](’图片链接‘)  
**插入图表**  

| 姓名 (左对齐） | 年龄(右对齐） |  性别（居中对齐）  |
|:---------|--------:|:----------:|
| 张三       |      25 |     男      |

## 嵌入Html内容
<img style="" height="" src=" ">
<span style="color: red; font-size: 40px"> 自定义字体 </span>

## 数学公式插入(类似于Latex)
$x=1$  $x=\frac{1}{2}$  
$$ 
x=1x=2 
$$