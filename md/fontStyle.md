<link rel="stylesheet" type="text/css" href="../css/fontCss.css">
+ [描述](#description)
+ [字体演示](#font_perform)
+ [css代码样式](#css_style)
+ [本文源码](#content_source)
## <span id = "description"></span>描述
    如何修改MarkDwon 默认的字体格式：
    自己添加一个css文件,定义一个.markdown-body{},'{}'设置自己满意的css样式
    下面字体例子
--- 
### <span id = "font_perform"></span>字体演示：

1. <span class="xiaomi"> 小米官网字体！</span>
2. <span class="taobaotc"> 淘宝技术研发中心字体！</span>
3. <span class="jiawang"> 加网字体！</span>
4. <span class="taobaoued"> 淘宝UED字体！</span>
5. <span class="yitaoux"> 一淘UX字体！</span>
6. <span class="myself"> 本人 喜欢用的字体！</span>


#### <span id = "css_style"></span>css代码样式
```css
/*小米官网*/
.xiaomi{
    font-family: "Arial","Microsoft YaHei","黑体","宋体",sans-serif;
}
/*淘宝技术研发中心*/
.taobaotc{
    font: 12px/1.5 Tahoma,Helvetica,Arial,'宋体',sans-serif;
}
/*加网*/
.jiawang{
    font: 14px/1.5 'Microsoft YaHei',arial,tahoma,\5b8b\4f53,sans-serif;
}
/*淘宝UED*/
.taobaoued{
    font: 12px/1 Tahoma,Helvetica,Arial,"\5b8b\4f53",sans-serif;
}
/*一淘UX*/
.yitaoux{
    font-family: Helvetica, 'Hiragino Sans GB', 'Microsoft Yahei', '微软雅黑', Arial, sans-serif;
    font: 12px/1 Tahoma,Helvetica,Arial,"\5b8b\4f53",sans-serif;
}
.myself{
    font:16px/1 'FangSong','仿宋',sans-serif;
}
```

#### <span id = "content_source"></span>本文源码
```html
<link rel="stylesheet" type="text/css" href="fontCss.css">

### 字体演示：

1. <span class="xiaomi"> 小米官网字体！</span>
2. <span class="taobaotc"> 淘宝技术研发中心字体！</span>
3. <span class="jiawang"> 加网字体！</span>
4. <span class="taobaoued"> 淘宝UED字体！</span>
5. <span class="yitaoux"> 一淘UX字体！</span>
6. <span class="myself"> 本人 喜欢用的字体！</span>
```


<!-- 语言代码高亮js片段 -->
<link rel="stylesheet" href="../css/light.css">
<script src="../js/light.min.js"></script>  
<script >hljs.initHighlightingOnLoad();</script>

