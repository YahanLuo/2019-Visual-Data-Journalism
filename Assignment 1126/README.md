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
* 配色好丑啊呜呜呜！我真是————不会调整配色。
</details>

<details>
<summary>Part 3：一些想知道的事情 </summary>



</details>

