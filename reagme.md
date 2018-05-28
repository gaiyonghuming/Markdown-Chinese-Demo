Smart中药杯
=================================== 

项目描述
-----------------------------------

该项目是基于ARC EM处理器的智能中药杯，可以帮助中药服用人群，适时适量的用药，保证身体的健康。硬件方面采用ARC EM处理器，WiFi模块、lcd模块、DS1302时钟模块、光敏电阻传感器模块等，用C语言编写程序控制硬件的工作。最终实现指导中药服药人群吃药的效果。<br/>
中药对于一些慢性病的确有较好的疗效，并且目前的中药已从传统的自行熬制，转变为冲服包装好的中药袋。平时服用中药时，一般有两种情况：一、定时冲服；二、一次冲泡好，多次服用。<br/>
中药冲泡好后，如果药剂变冷，会影响患者服药感受或者影响药效；中药每天服用频率有讲究：频率低于医嘱，会导致疗效不够；频率高于医嘱，可能会导致副作用。统计用药习惯，可以辅助判断药品的疗效。<br/>
然而，目前生活中还缺乏一种集上述所有功能为一体的饮用容器。基于此，提出一种Smart中药杯，一举解决上述问题。中药杯的主要功能：1、提醒服药系统（声音提示） 2、显示模块：液晶显示——显示当前中药温度、杯中剩余的药量。预期还可以使用WiFi模块使用更多地方式来提醒用户服药，并在后台记录患者的用药习惯，根据医嘱来辅助用药。<br/>

### 如何运行
* 配置环境
  * 软件环境<br/>
    * 参考软件包——embARC 201709
    * 开发工具及编译工具——GNU Toolchain for ARC Processors, 2017.03 RC2
  * 硬件环境<br/>
    * EMSK开发板
    * 温度检测模块
    * 蓝牙通信模块
    * 液位检测模块
    * WiFi模块
    * 蜂鸣器
    * OLED模块
### 标题的等级表示法
	关于标题的等级表示法，共分为六个等级，显示的文本大小依次减小。不同等级之间以井号#的个数来标识。一级标题有一个#，二级标题有两个#，以此类推。
		
		##二级标题
		###三级标题
		####四级标题
		#####五级标题
		######六级标题
### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可
        
### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码

### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

      /**
      * @param args
	    */
	    public static void main(String[] args) {
		    System.out.println("HelloWorld!");

	    }

    }

### 链接
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />
2.[点击这里我你可以链接到我的博客](http://guoyunsky.iteye.com)<br />

###只是显示百度的图片
![baidu-images](http://www.baidu.com/img/bdlogo.png "baidu")  

###只是显示图片，这里用的是相对路径
![github-01.jpg](/images/01.jpg "github-01.jpg")

### 显示图片也可以用原生的html标签
<img src="http://su.bdimg.com/static/superplus/img/logo_white.png" />

###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: /images/02.jpg "github-02.jpg"

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 部分文字的高亮
如果你想使一段话部分文字高亮显示，来起到突出强调的作用，那么可以把它用\`\`包围起来。
注意这不是单引号，而是Tab键和数字1键左边的按键（注意使用英文输入法）。<br />
	example：
		Thank`You`. Please `Call` Me `Coder`
### 代码片段高亮显示
GitHub的markdown语法还支持部分语言的代码片段高亮显示。只需要在代码的上一行和下一行用\`\`\`标记。
```Java
	public static void main(String[] args){} //Java
```
```c
	int main(int argc,char *argv[]) //C
```
```javascript
	document.getElementById("myH1").innerHTML="Welcome to my Homepage";//javascript
```
```cpp
	string &operator+(const string& A,const string& B) //cpp
```
	
### list列表条目使用
写文章时经常会用到list列表条目。GitHub的markdown语法里也支持使用圆点符。编辑的时候使用的是星号*。
* 国籍：中国
* 城市：北京
* 大学：清华大学 
<br/>注意：星号*后面要有一个空格。否则显示为普通星号。
GitHub还支持多级别的list列表条目：
* 编程语言
	* 脚本语言
		* Python

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>
    

### 插入表格
在Markdown中插入表格比较麻烦，需要Markdown的扩展语法，但是插入HTML就没有那么麻烦了，因此我们可以通过曲线救国的方式来插入表格。       
在Markdown中，`&`符号和`<`会自动转换成HTML。

	<div>
	    <table border="0">
		  <tr>
		    <th>one</th>
		    <th>two</th>
		  </tr>
		  <tr>
		    <td>Hello</td>
		    <td>你好</td>
		  </tr>
	    </table>
	</div>
	
<div>
        <table border="0">
	  <tr>
	    <th>one</th>
	    <th>two</th>
	  </tr>
	  <tr>
	    <td>Hello</td>
	    <td>你好</td>
	  </tr>
	</table>
</div>
