##### Typora软件
    实时查看MD代码编辑效果，再也不用在github上左右横跳预览修改。但是github目前仅支持HTML的部分元素（目前支持的 HTML 元素有：<kbd> <b> <i> <em> <sup> <sub> <br>等 ，
    如果要使用其他元素，还是要以HTML编写。

# 一级标题
    语法规则：#，一个空格，标题内容
## 二级标题
    语法规则：##，一个空格，标题内容
### 三级标题
    语法规则：###，一个空格，标题内容
#### 四级标题：
    语法规则：####，一个空格，标题内容
##### 五级标题
    语法规则：#####，一个空格，标题内容
  **注意：到五级标题，如果要往下再分级，标题效果已经不明显了。如下六级标题。**  

###### 六级标题
    语法规则：######，一个空格，标题内容
    
#### =====================================================================================

##### 换行
    Andy：You should check the phone number,There is nobody called renzhongshu here.  
    Red：Okay.
    语法规则：在行末输入两个空格
    
##### 粗体
   **楚休红:唯刀百辟，唯心不易。**  
     语法规则：0或1个tab，内容前后加上**或__（两个短下划线）  
     
##### 斜体
   _Rambo：I don't like "First Blood"._  
    语法规则：内容前后加上“_”，但是如果行首加了两个tab，该语法失效。  
    
##### 粗斜体
   ***Ross:She is not Rachel,She is not Rachel.***  
   ___Rachel:I'm sorry,Ross,You have a right to know the truth that I am not straight.I am so sorry.___  
    语法规则：内容前后加上***或者___（三个短下划线）。  

##### 单行或多行文本框
    语法规则：在各行行首加入两个tab。  

##### 删除线
  ~~Nothing's gonna change my love for you~~。 
   
    语法规则:内容前后加上两个“~”。
      
##### 圆点
   * ***We choose to go to the moon,We choose to go to the moon,We choose to go to the moon in this decade and do the other things, not because they are easy, but because they are hard...***  
   
   <font face="微软雅黑"><font color="apple">___复读使人强大，同样一句话，只说一句“我们选择登月”显得略有苍白，<kbd>**说三句给人的感觉就像这段话加粗又高亮**</kbd>___</font></font>  
    
    语法规则：在行首加入*和一个空格；次级标题在*号前加入一个tab。依次类推。
    
##### 插入图片
    语法规则：![自定义]（图片链接）；但是貌似上传图片到repo，好像也无法正常显示。网上改写hosts文件，进行DNS重映射的方法，试过也不行。可能被防火墙拦截了。

##### 插入链接
    [RFC5071](https://datatracker.ietf.org/doc/rfc5970/)
    <https://datatracker.ietf.org/doc/rfc5970>
    语法规则：[自定义]（链接）

##### 代码
```python
print("Hello World!")
```
    语法规则：在代码段前和结尾加上```，表示该区域内为代码段，并在```后面加上python或指定其他语言（若不指定语言显示效果和普通字符没有区别）。
