# jqueryExtend

其中是一些jquery的扩展方法，jquery中尚无定义的，需要依赖jquery！

# 1.isChild
含义：判断一个节点是否为另一个节点的子元素，参数为子节点，可以字符串选择器，如＃a,.b，也可以是一个节点引用；
用法：$('body').isChild(node)。

# 2.textUnWrap
含义：去除一个包裹元素，但保留其中的内容，内容为纯文本形式，即不保留html标签；
用法：如('#a').textUnWrap()则为去除#a元素，但保留其中的文本。

# 3.htmlUnWrap
含义：去除一个包裹元素，但保留其中的内容，内容为html形式，即保留html标签。
用法：如('#a').textUnWrap()则为去除#a元素，但保留其中的html及文本。


#持续更新中...
