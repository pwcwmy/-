## 个人网站搭建
#### 内容结构
我设计的个人网站涵盖了六大板块，分别为：个人主页（index.html)、我的爱好（hobby.html)、我的相册（photo.html)、我的音乐（music.html)、唯美的DIY搜索引擎（SearchEngine.html)、简约大气的登录注册页面（login.html)。<br>
每个页面之间的切换皆可通过点击页面顶部的导航栏和底部（页面右下角）的超链接实现，会在新窗口打开。页面底色选用黑色，展示内容多用黑白灰三色，简约雅观。<br>
工程文件中包括html、css、img三个文件夹和一个index主页面。<br>
css文件夹中有一个共用的文件为base.css，为导航栏和底部的样式，减少了不必要的代码冗余。css样式与html页面分离，使得html文件更加简洁明了。<br>
#### 立意构思
我很高兴能在学习与设计实践中探索前端技术精彩而广袤的世界，体会乐趣与成就感。我想把个人网站视作一个视窗，记录我的美好生活，同时展示学习成果，后续也会注意隐私和版权问题，不断充实完善个人的网页。租赁服务器或借助在线代码托管平台，建立自己的站点，将自己的个人网站上线，把学习资源或者是有趣的生活片段都上传上去，便于更好的分享，也可以回首看看自己走过的路。<br>
#### 技术栈
个人主页的搭建会基于html4、html5、css2、css3、JavaScript、Vue等技术。<br>
设计方法：深入理解盒模型，浮动与相对定位、绝对定位相结合，内容以无序列表ul、img、video、music、文字段落为主。<br>
## JavaWeb开发初探

## 前端开发keepTrying
1.设计布局及方法<br>
（1)版心960px<br>
从上至下依次为：头部、菜单栏、主体（第一行高铁图片、第二行一行三块、第三行一行四块)、页脚（底部导航栏）均在demo.html中做了清晰的注释和封装。<br>
（2）设计方法：深入理解盒模型，浮动与相对定位、绝对定位相结合，内容以无序列表ul为主。<br>
2.设计的最大亮点:设计全程贯彻“语义化”的原则，将“语义化”牢牢记在心中，不光关注css所带来的效果，更重视特定效果所能传达的内容内涵。<br>
（1）引入常用的reset.css重置默认样式，然后就可以随心设计了；<br>
（1）类名选择器、id选择器、伪元素选择器等命名严格按照规范；<br>
（2）利用cursor：pointer属性使鼠标焦点在图片上方呈现手形；<br>
（3）菜单栏和新闻链接等页面上所有可能被点击的地方都做了超链接，方便交付给后端或者js，超链接的样式也改为了焦点在上方时字体会变红，更贴近真实效果；<br>
（4）利用form表单包裹了搜索框和搜索按钮，便于传值。<br>

