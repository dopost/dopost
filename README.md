https://www.zybuluo.com/mdeditor   编辑阅读器

markdown常用语法
字数721 阅读60 评论0 喜欢3
1.标题(h1~h6)
# h1标题## h2标题...###### h6 标题
效果:
h1标题
h2标题
...
h6标题
2.区块
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet
效果:
This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet
3.列表
无序列表使用星号、加号或是减号作为列表标记：
* Red
+ Green
- Blue
效果:
Red
Green
Blue
有序列表则使用数字接着一个英文句点：
1. Bird
2. McHale
3. Parish
效果:
Bird
McHale
Parish
4.代码区块
要在 Markdown 中建立代码区块很简单，只要将代码包含在```之间
效果:
your code goes here
5.分割线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线
***
---
___
效果:
6.链接
行内式
要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可
This is [an example](http://www.baidu.com/ "Title") inline link.
效果:
This is an example inline link.
参考式
使用 Markdown 的参考式链接，可以让文件更像是浏览器最后产生的结果，让你可以把一些标记相关的元数据移到段落文字之外，你就可以增加链接而不让文章的阅读感觉被打断。
I get 10 times more traffic from [Google] [1] than from[Yahoo] [2] or [MSN] [3].
[1]: http://google.com/ "Google" 
[2]: http://search.yahoo.com/ "Yahoo Search" 
[3]: http://search.msn.com/ "MSN Search"
效果:
I get 10 times more traffic from Google than fromYahoo or MSN.
7.强调
Markdown 使用星号和底线作为标记强调字词的符号，被 星号 或 底线包围的字词会被转成用 em 标签包围，用两个 星号 或 底线 包起来的话，则会被转成 strong
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
效果:
single asterisks single underscores double asterisks double underscores
8.代码
如果要标记一小段行内代码，你可以用反引号把它包起来
Use the `printf()` function.
效果:
Use the printf() function.
9.图片
要在纯文字应用中设计一个「自然」的语法来插入图片是有一定难度的。
行内式的图片语法：
1.一个惊叹号 !
2.接着一个方括号，里面放上图片的替代文字
3.接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。
![效果图1](http://7xr0h8.com1.z0.glb.clouddn.com/aiyouchuan_A0101.jpg "Optional title")
效果:


效果图1

到目前为止， Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的 img标签。
10.自动链接
<http://www.baidu.com/>
效果:
http://www.baidu.com/