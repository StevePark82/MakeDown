#demo2

## 链接

### 内嵌式链接
外部链接：  
[链接的文字-百度](https://www.baidu.com)

内部链接1:  
链接本仓库的其他文档  
[链接的文字-demo1](demo1.md)

内部链接2:  
链接本文档的其他部分  
[链接的文字-代码块](demo1.md#代码块)

### 引用式链接
在文档最后将文档内容中引用的链接进行集中书写，这样可以解决同样的链接需要书写多次的问题。

外部链接：
[百度]

内部链接1:  
链接本仓库的其他文档  
[demo1]

内部链接2:  
链接本文档的其他部分  
[代码块]

## 图片

- 图片的makedown语法  
    ![alt](url text)

- 内嵌式-链接外部的图片  
![baidu](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "百度图片")

- 内嵌式-链接内部的图片  
![sony](images/th.jpeg)  
由于web浏览器是在下面的链接中保存的demo2.md.html，所以要将图片放放在.../preview里面的images目录下
file:///Applications/HBuilder.app/Contents/configuration/org.eclipse.osgi/bundles/104/data/preview/demo2.md.html

- 引用式-链接外部的图片  
![baidu][baidu-logo]

- 引用式-链接内部的图片  
![sony][robot]  
由于web浏览器是在下面的链接中保存的demo2.md.html，所以要将图片放放在.../preview里面的images目录下
file:///Applications/HBuilder.app/Contents/configuration/org.eclipse.osgi/bundles/104/data/preview/demo2.md.html

## 引用
> 这是一段引文。  

--出自《》

多重引文，有多少个引文有多少个> 符号

>>>> 这是4层引文

## 代码块
- 行内代码  
1对 单个反引号：  
在python中可以通过`var = 'hello python'`来定义一个字符串类型的变量，通过`print(var)`进行变量输出。

- 块式代码  
一对 三个反引号：  
如果在```后面跟上编程语言的话，会有高亮显示：  

```python
var = 'hello python'
print(var)
```


<--- 下面是我们在本文中引用到的链接 --->

[百度]: https://www.baidu.com
[demo1]: demo1.md
[代码块]: demo1.md#代码块
[baidu-logo]: https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png
[robot]: images/th.jpeg
