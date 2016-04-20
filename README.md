### tab
>网页常用的tab实现方法,几行简单易懂的代码即可实现tab切换，并且多tab之间不存在冲突
使用jQuery完成的tab，代码量小，易重用与维护

### JQ轮播
>简易的轮播实现方法,重在理解轮播原理

### 图片无缝滚动
>老旧的特效，有些网站还需要这样的效果，提供四种方向的特效方案,效果在 “Gundong” 文件夹内

### 下拉菜单
>网页常用的鼠标事件后显示下拉子菜单栏目的效果

### JQ生成DOM元素并关联按钮
>一些网页需要点击按钮（或元素）来生成一个新的DOM元素，并且实现关联

###页面锚点
>点击固定导航，对应内容元素跳转

###头部导航悬停
>滚动到一定距离后，头部导航悬停在顶端，向上推动到一定距离后回归正常文档定位


####↑以上效果的 [点击预览页面](http://htmlpreview.github.io)(将效果页面的链接粘贴到下面页面的输入框中)

<script src="http://apps.bdimg.com/libs/jquery/2.1.4/jquery.min.js" charset="utf-8"></script>
<script type="text/javascript">  
    $(document).ready(function() {  
        //为超链接加上target='_blank'属性  
        $('a[href^="http"]').each(function() {  
            $(this).attr('target', '_blank');  
        });  
    });  
</script>  
