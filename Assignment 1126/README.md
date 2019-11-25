# Yahan Luo 1126 Assignment
<details>
<summary>Part 1：关于废玻璃的原图、ggplot图、代码以及存在的问题 </summary>

### 原图
<p align="center">
	<img src="https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201029/pic1final.png" width="450"></p>

### ggplot图
<p align="center">
	<img src="https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201126/plastic_ggplot.jpg" width="600"></p>

### 代码
	> library(readxl)
	> R_1123_plastic <- read_excel("R_1123_plastic.xlsx")
	> View(R_1123_plastic)
	> library(ggplot2)
	> p1 <- ggplot(data = R_1123_plastic,aes(x = Year,y = Rate,colour = factor(Type),group = factor(Type)))
	> p1 
	+ geom_point() 
	+ geom_line() 
	+ labs(title = "我国主要再生资源类别回收年增长率")
	
### 出现的问题
* 该怎样调整坐标轴，使这个图看起来稍微体面一点？
* 如何做出一条折线是红色，其他都是灰色的效果？
* 这个图到底为什么这么丑？配色可以再优化吗？该怎样优化？

</details>

<details>
<summary>Part 2：关于未成年人再犯率的原图、ggplot图、代码以及存在的问题 </summary>

### 原图
<p align="center">
	<img src="https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201113/png02.png" width="700">
</p>

### ggplot图
<p align="center">
	<img src="https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201126/crime_ggplot.jpg" width="700"></p>


### 代码
	> library(readxl)
	> commit_crime2 <- read_excel("commit_crime2.xlsx")
	> View(commit_crime2)
	> library(ggplot2)
	> p3 <- ggplot(data = commit_crime2,  aes(x ="",y = Rate,fill =  Commit_crime))  + facet_grid(. ~ Time)
	> p3 
	+ geom_col() 
	+ coord_polar(theta = 'y')
	+ labs(x = "", y = "", title = "最大风险收容项目重犯率与收容时间的关系") 
	
### 出现的问题
* 这个图为什么挤在一起，皱皱巴巴的？我该怎么把它拉开，不要让字挡住？
* 配色好丑啊呜呜呜！我真是————不会调整配色。看书也没有看懂。完全无法调自动生成的颜色。
* 周围的labs还是要调整一下。

</details>

<details>
<summary>Part 3：一些想知道的事情 </summary>

* **关于R**

	* 我的室友想要问一问：R的作用到底什么？尤其在线生成图表的工具这样发达，我们为什么还要企图学代码呢？
	* （尤其是这个R做出来的图还这么丑）
	* （当然我菜是真的）
	
* **关于地图可视化**

	* 我之前写过一个**在线生成地图的网站**的盘点，我觉得大部分同学都是知道这些的（吧），可以在这个的基础上往上教，[请苏老师过目](https://mp.weixin.qq.com/s/QBwiDXTIbhEtNFR4S2bFEA)。
	* 我一直想做3D的地图。但是3D Mapper这个网站没有中国的数据。国内有这样的建筑物3D地图吗？
	* 有没有风格比较特别的地图可视化数读作品呢？（比如特别写实或者特别抽象）想要看看，开拓眼界。
	
* **关于我的Final Project**
	 * 这本书的确很小众，我也在反复掂量是不是要做这样一个题目。如果我的受众只是我的同学，那么我相信他们都会点开看；我所需要考虑的是**怎么让一个没有读过这本书的人，看完我这个作品之后，也会对这本书充满了兴趣。或者至少多了一丝好奇。**
	 * 苏老师觉得呢？你会看一个你没有听过的文学或者艺术作品的可视化读物吗？如果你点进去了，那一瞬间你期待看到的又是什么呢？
	 * **关于这本书**
	 	* 《All The Light We Cannot See》讲述的是二战时期的关于两个孩子和两个国家的命运，这本书是2015年普利策奖虚构类作品奖项获得者，纽约时报畅销榜第1名 连续65周在榜，在国际上还是有一定的名气的。（只是在国内的影响力比较小。）这本书是作者安东尼·多尔的第五部作品，耗时十年。
	 	* 书的结构很特别，以并行两条线索介绍两个孩子不同的命运：一个是居住在法国小镇的盲女孩，另一个是参加德国青年自卫队的天才少年。两个孩子的身份截然不同，但命运让他们走到了一起。
		* 作者在不同的时间和空间反复切换，第一次看这本书的人基本不能完全看懂。可是通读全书，你可以看见两个主人公在彼此的悲剧生活中苦苦挣扎，在成长的过程中没有背叛自己。
		* 尽管全书弥漫着过于忧郁的宿命论色彩，你仍然能感受到人性之光的耀眼。
		
	 


</details>

