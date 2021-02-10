---
layout:     post
title:      Programming Foundations with JS, HTML and CSS
subtitle:   JS, html, css编程学习日志
date:       2021-01-05
author:     Chen 
header-img: img/facebook.jpg
catalog: true
tags:
    - Study
---


### HTML

Course Resources: [https://www.dukelearntoprogram.com/](https://www.dukelearntoprogram.com/)   

Programming Tool: [https://codepen.io/your-work](https://codepen.io/your-work)  

有别的不会的查这个: [https://www.w3school.com.cn/h.asp](https://www.w3school.com.cn/h.asp)

---

<b>注意: 编写特殊符号, &lt ; 代表<,  &gt ;代表>  </b>

&lt;b&gt; &lt;/b&gt; bold text 大写

&lt;p&gt; &lt;/p&lt; paragraph 段落

&lt;em&gt; &lt;/em&gt; emphasize text  强调, 也就是斜体

&lt;img src="path of image" width = "75%" /&gt; image 直接显示

&lt;a href="http://www.linkofwebsite/"&gt; some text  &lt;/a&gt;  指向网址的超链接 和可点击的文字

常见html character entities 查这里: [https://www.w3schools.com/html/html_entities.asp](https://www.w3schools.com/html/html_entities.asp)

---

ul→unorder list 无序列表  
ol→order list 有序列表, 列表自动标号  

```html
<ul>
<li> content1 </li> 
<li> content2 </li>
<li> content3 </li>               
</ul>
```

<ul>
<li>  content1 </li> 
<li>content2</li>               
<li> content3</li>               
    </ul>
 

---

表格 table  

```html
<table>

<tr>     
<th> header1 </th> 
<th> header2 </th>  
<th> header3 </th>  
</tr>          

<tr>      
<td> data1 </td>        
<td> data2 </td>         
<td> data3 </td>             
</tr> 

</table>   
```

<table> 
<tr>      
<th> header1 </th>   
<th> header2 </th> 
<th> header3 </th>   
</tr>         
<tr>
<td>  data1 </td>         
<td> data2 </td>         
<td> data3 </td>             
</tr>                    
</table>        
---










### CSS

#### Syntax , Style and ID

```css
.h1{ 
      text-align: center;
      color : blue;
}
```

上面这个例子会把html中所有h1标题全都居中变蓝，如果想通过CSS修改一类标题或者格式，需要先对class进行声明，比如： 

```html
<li class = "foodLi"> Food List </li>                     Note：声明的class名字不能有括号空格
```

```css
.foodLi { color : green}
```

如果想通过CSS修改某个标题或者格式，需要使用CSS id，比如：

```html
<img src = "cake.jpg" id = "cakeimg" />
```

```css
#cakeimg {float: right}                                    Note：id 选择器以#开头
```

---

#### Color 

颜色选择器：[https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool.)

选择完颜色之后直接使用颜色代码调整文本颜色： 

```css
.foodLi {color: #3f3fbf}                                   %%% 此处对应rbg(63, 63, 191)
```

---

### JavaScript



