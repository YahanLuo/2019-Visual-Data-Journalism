# Yahan Luo 1120 Assignment
<details>
<summary> Part 1：成品链接 </summary>
  
### 成品链接

* 成品链接在此处！[请戳这里](https://readymag.com/u25494332/allthelightwecannotsee/)

* 一些小小的tip：
  * https://readymag.com/u25494332/allthelightwecannotsee/
  * **请使用Chrome浏览器！请使用Chrome浏览器！请使用Chrome浏览器！**
  * **如果打不开，请挂VPN**，**请挂VPN**，**请挂VPN**。站点在国外，我也没办法。
  * 加载速度太慢。希望可以等待一下呜呜呜呜。（其实也似乎只能等待？
  * 缩放比例在90%到110%为佳。
  * 大部分图像有交互，上下滑滑，随便点点？
  
</details>

 <details>
 <summary> Part 2：过程描述 </summary>
 
### 选题想法

这在我之前的md里面有，不再赘述。请戳[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/tree/master/Assignment%201120)还有[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/tree/master/Assignment%201126)。

### 制作过程

 1. **初级文本分析** （12月1日~12月5日）
 
    * 既然是做文本分析，那么文本自然是第一步。所以我的大部分资料都是围绕《所有我们看不见的光》（后简称《光》）这本书的中英文原著的文本进行。
    * 首先，我找不到纯英文版本的《光》。于是我用八爪鱼爬取了一个在线阅读的界面，把英文原文给copy了下来。将其导出成word。
    * 其次，我把里面所有的标点都去除，只留下干净的单词，导出成TXT。
    * 我最开始是企图做词频，使用了一种粗暴野蛮的方法————把txt导入在线词频网站，直接统计。
    * 但这样的问题在于，无意义的小词是最多的。比如"it","that","the"。
    * 而且，不同的网站居然结果还不一样！请看[这个](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/wordfrequency.xlsx)，和[这个](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/wordfrequency02.xlsx)。真的不一样。
    * 他喵了个咪的，这怎么能忍。
  
 2. **中级文本分析**（12月6日~12月7日）
 
    * 在研究了好几天R无果，既写不来词频也搞不来人物关系更分析不来情感波动之后（还被王小宁嘲笑了）
    * 我决定自己数！
    * 但是我不是要数文章。这本书的特点是 **分小节** ————写一段情节，提取一下主要的内容，打个小节。
    * 于是，我整理出了每一小节的**所属章**，**年份**，**具体日期**，**中英文标题**，**主人公**，**标题词性**。
    * 经过艰苦卓越坐痛屁股的努力，我终于摊着两本纸质书，把它给整理完了。
    * 戳[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/All_the_light_title_final.xlsx)看我的**小节整理清单**.
    
 3. **可视化之一**（12月7日~12月8日）
 
    * 此时的我陷入困境，拿着这些数据又有什么用呢？
    * 此时我打开了我的老朋友Tableau（要我说Tableau真的是可视化的好朋友！操作简便，图形种类也比较多，是真的可以给手足无措的我打开新世界大门的。）
    * 但是Tableau也没能给予我灵感。（S**t）
    * 我开始快乐摸鱼。（太真实了）
    * 我打开了google earth，想要看一看Saint Malo的样子。一看吓一跳————这也太美了！（我宣布，我心中的第一旅行地从雅典变成了圣马洛）
    * 言归正传，我截了沃博雷尔街4号的街景，就退出来了。
    * 但这时，我福至心灵了————为什么不用**地理可视化**呢？这本书里面那么多真实的地名，完全可以在地图上找到。
    
 4. **高级文本分析**（12月8日~12月15日）
  
    * 说干就干，我立刻着手整理了书中提到的所有**地名**，[戳这里看我的笔记](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/%E5%A4%87%E6%B3%A8%202019%E5%B9%B412%E6%9C%888%E6%97%A5.pdf)
    * 因为整理，我又通读了一遍文本，突然明白，有的**意象**是在反复反复反复出现的。其实之前我就有感觉，但是没想过要去整理它。
    * 我在页边上简单整理了一下我脑子里最先出现的几个意象，居然发现两条人物线的意象可以一一对应，代表恐惧的，代表勇气的，代表亲情的。
    * 我立刻开始着手整理。
    * 我的整理方法非常粗暴：直接在微信读书里面搜索这个关键词，看它出现在哪些小节。
    * 讲道理，这是有讲究的。为什么不用词频？一个词在一个地方的反复吟咏，不能算是其多次出现。为什么不用英文小节？因为英文的整理出来的文本比较混乱，我只能看出词频，看不出它属于哪个小节。这样寻找，效率太低。而在微信读书中，我只要一搜索便出现，且我对于文本太熟悉（毕竟也读了七八遍），我基本知道漏掉了哪些，又有哪些是这个词语，但是指代的不是这个意象。
    * 在这个时候，我再一次福至心灵————既然物体可以搜索，那么**人名**为什么不可以？
    * 基于我之前的小节名称的Excel，我很快整理出一份**人物出现的小节**数的清单，并基于这两份Excel，清理了**两个人同时出现在一小节**的情况。
    * 在这里，可能我就会受到一些质疑。为什么这个算意象但哪个不算？为什么这个算人物互动但那个不算？首先，意象这个东西真的还蛮玄学，我的确也不知道有的分类方法是否可行。所以接受diss。但两个人出现在同一小节的标准，我还是有的。即两个人必须产生某种程度上的互动，比如交谈，比如一个人想起了另一个人。
    * 戳[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/images%20and%20relationship.xlsx)看我的整理清单（有三张表）。
    
  5. **内容框架确定**（12月8日~12月9日）
  
     * 其实这个时候我还没有开始整理意象和人名，但是看着逼近的ddl，我很着急。
     * 晚上和王思涵一起讨论的时候，我才发现原来从图的角度来说，我已经有很多内容了。确定了要做意象图，要做人物关系图，要再做一个地理可视化。
     * 以及我想把内容从书中引申出去，延展到现实的层面，让它意义更丰富。
     * 也就是在这个时候，我确定了主题 **"All the light we cannot see : About the book, beyond the page"**
     * 为什么没有中文名字？很简单，我想不出来好听的。
     * 就在8日晚上，我记得清清楚楚！我拿着ipad开始画mockup。 **那可真的是，如有神助的一夜** 真的就是一口气就把mockup给顺下来了。自己也满意。
     * 戳[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/mockup%20for%20all%20the%20light.pdf)，看我(精美）的 mockup。
  
  6. **可视化之二** （12月13日~12月16日）
  
     * 白天画画，晚上做图。
     * 画画靠ipad，[Procreate这个软件](https://procreate.art/)，导入老照片，描线，再加以修改。画主要人物，和艾蒂安的房子。
     * 做图本来是想用Tableau的，但是无奈配色真的不太行，于是就先在导出基本的圆圈的大小；再在ps里面修改颜色。
     * 意象图也是如此
     * 人物之间的线条也是ps画的。
     
  7. **史料收集** （12月11日~12月19日）
    
     * 这一部分主要是收集史料。
     * 这个时候我就发出痛苦的嚎叫了———为什么二战的数据集这么少！！！而且我想要的城镇死亡人数，疾病致死率，基本生活情况受影响人数什么的，全都没有。全部是统计什么飞机型号。轮船记录，你这让我怎么用？
     * 这绝不是我找不到。我连德国法国的官方在线档案库和地方在线档案库都翻过了，依然没有。
     * 后来，我仔细想了一下，这也很好理解。二战时，草菅人命的情况太多。死了人，有的时候草草掩埋一下就完事，谁来统计数量呢？**就连二战死亡的总人数，都是估算值**
     * **“此时无数胜有数”。战争的残酷，实在让我心头一紧。**
     * 当然，我还是找到了一些可用的数据和一些很不错的照片。照片主要是来自WW2这个数据库，内容之翔实，让人叹为观止。选了几张放在md上面了，自取。
   
     
  8. **第一部分：视觉呈现整合** （12月14日~12月18日）
  
     * 在视觉呈现上，我选择了一款和Wix很像的小众网页编辑器——**readymag**。虽然它需要氪金，但是，基础的操作和第一个作品的发布，都是不要钱的。
     * 在第一部分的文本上，我按照之前mockup的逻辑一路往下写。15号把文案发给苏老师看。虽然被苏老师diss了说**转折突兀**，但是由于我实在想不到一个别的组织串联的逻辑，所以也就没改。（哭哭）
     * 戳[这里](https://github.com/YahanLuo/2019-Visual-Data-Journalism/blob/master/Assignment%201220/%E4%B9%A6%E9%A1%B5%E4%B9%8B%E5%A4%96.pdf)，看我的头大的第一版文案。
     * 在第一部分的图上，我还想搞事情，企图用iframe插入一个**可拖拽的动力关系图**。其实都在hanabi做好了，但不知为何，底色改不了。真的无语。镝数倒是可以改底色，但是没有这个动力关系图。
     * 在此@苏老师催促开发部赶紧支持底色自选吧！
     * 总之，视觉呈现整合真的是，搞死我。每一个动效都要单独导出图层，再一层一层地叠加上去。尽管如此，这还是比写代码容易多了。高声感谢readymag！
     
  9. **可视化之三**（12月16日~12月19日）
  
     * 文章和后半部分的可视化元素并不多，照片，图标。当然，我在想，如何平衡这二者的比例，让人感受到真实的时候别忘了这还是一片数据新闻。
     * 不过，**这种刻意的平衡是必要的吗？**
     * 当我发现动效是可行的时候，我又开始想要搞事情了。
     * 比如最后那个部分**什么人干什么**的可视化，就一张表格几条轴的那个。我是19号下午才做的。本来的想法是直接放文案。但是实不相瞒。太丑了。
     * 所以我想了一下，觉得这样把线索明明白白展示在图上比较好。本来我的背景不是一张网格，而是一张圣马洛的地图。但是我个人觉得这个太冗杂，无效信息太多，会干扰读者。所以选择了网格作为背景。本来还有三条线索，我都删除了。只保留了核心的三个人物。
     * 也算是**在象形和抽象之间的平衡**吧。
     
 10. **第二部分：视觉呈现整合** （12月18日~12月19日）
 
     * 最后一部分整合相较于前面来说简单得多，没有了骚气的动效，画画圆，放放图，写写煽情文案，都很简单。
     * 从圣马洛的命运切入其实不在我计划之中，但我觉得这是值得一说的。
     * 最大的遗憾就是最后一部分关于Napola的数据太少，我也无力再可视化。以至于那一部分的体量看起来很单薄，感觉撑不起一个高潮迭起的结尾。
     * 后期有时间我会重做那一部分。
     * 19日晚上10点，我上传了结尾处最后一张台词图。
     * 杀青。

</details>

<details>
<summary> Part 3：Reference </summary>
  
 ### 参考资料 
1. 文本信息
  
  * [微信读书：《所有我们看不见的光》](https://weread.qq.com/web/reader/f12329605c5526f12a64291kc81322c012c81e728d9d180)
  * [Litcharts: All the Light We Cannot See](https://www.litcharts.com/lit/all-the-light-we-cannot-see)
  
2. 圣马洛的数据
  * [INSTITUTE FOR HISTORICAL REVIEW: The Burning of Saint Malo *by Philip Beck*](http://www.ihr.org/jhr/v02/v02p301_Beck.html)
  * [Saint Malo 官网Data.StMalo-Agglomération](https://data.stmalo-agglomeration.fr/explore/dataset/monuments-historiques-classes-a-saint-malo/table/?sort=date&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjNjZjMmE1In1dLCJ4QXhpcyI6ImRhdGUiLCJtYXhwb2ludHMiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic29ydCI6IiIsImNvbmZpZyI6eyJkYXRhc2V0IjoibW9udW1lbnRzLWhpc3RvcmlxdWVzLWNsYXNzZXMtYS1zYWludC1tYWxvIiwib3B0aW9ucyI6eyJzb3J0IjoiZGF0ZSJ9fX1dLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D)
  * [The Battle of Saint-Malo in World War II](http://www.klangslattery.com/blog/entry/the-battle-of-saint-malo-in-world-war-ii)
  
3. 图片 
  * [Saint-Malo-Rama: Saint-Malo en 1944, images d’une ville fantôme – partie 1](https://www.saint-malo-rama.com/2013/05/10/saint-malo-en-1944-images-dune-ville-fantome-partie-1.html)
  * [WW2: World War 2 Photo](https://ww2db.com/photo.php)
  * [Saint Malo Google Earth Image](https://earth.google.com/web/)
  
4. 关于Napola的数据
  * [Pforta](https://en.wikipedia.org/wiki/Pforta)
  * [National Political Institutes of Education](https://en.wikipedia.org/wiki/National_Political_Institutes_of_Education)
  
5. 字数统计工具
  * [Writer Words: Word Frequency Counter](http://www.writewords.org.uk/word_count.asp)
  * [Text Fixer: Online Word Counter for Text](https://www.textfixer.com/tools/online-word-counter.php#newText2)
  
6. 其他参考资料
  * [WW2: World War 2 Statistics](http://www.world-war-2.info/statistics/)
  * [WW2: World War 2 Casualties](http://www.world-war-2.info/casualties/)
  * [WW2: World War 2 Documents And Letters](https://ww2db.com/photo.php?list=sp&sp=d&startRow=20&keyword=&source=&color=&foreigntype=&foreigntype_id=&dt=&image_id=)
  * [The Wiener Holocaust Library: The Holocaust Explained](https://www.theholocaustexplained.org/life-in-nazi-occupied-europe/oppression/disabled/)

</details>
