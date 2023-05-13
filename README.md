
JavaWeb开发初探

前端开发keepTrying
1.设计布局及方法
（1)版心960px
从上至下依次为：头部、菜单栏、主体（第一行高铁图片、第二行一行三块、第三行一行四块)、页脚（底部导航栏）均在demo.html中做了清晰的注释和封装。
（2）设计方法：深入理解盒模型，浮动与相对定位、绝对定位相结合，内容以无序列表ul为主。
2.设计的最大亮点:设计全程贯彻“语义化”的原则，将“语义化”牢牢记在心中，不光关注css所带来的效果，更重视特定效果所能传达的内容内涵。
（1）引入常用的reset.css重置默认样式，然后就可以随心设计了；
（1）类名选择器、id选择器、伪元素选择器等命名严格按照规范；
（2）利用cursor：pointer属性使鼠标焦点在图片上方呈现手形；
（3）菜单栏和新闻链接等页面上所有可能被点击的地方都做了超链接，方便交付给后端或者js，超链接的样式也改为了焦点在上方时字体会变红，更贴近真实效果；
（4）利用form表单包裹了搜索框和搜索按钮，便于传值。

