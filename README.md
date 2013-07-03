## csscute-reset

重置样式是前端开发工程师在样式层叠表中可以控制的最底层基准样式，HTML文档中绝大部分标签都会继承重置样式中的样式定义，因而，重置样式将直接影响整个工程项目的样式层叠结构。

但目前常见的重置样式方案对于样式继承关系没有太多要求，并且部分样式定义与浏览器内部默认样式定义一致，造成一定的样式定义重叠冗余，csscute-reset项目的作用就是构建一个合理且高效的重置样式。

### 需要注意：

csscute-reset目前还处于实验阶段，实现过程并不完善，如果您愿意花点时间来研究并改进它，我们非常欢迎。

### 样式规则：

- 重置常见标签样式：html、body、p、pre、dl、dd、img、iframe、button、input、select、textarea、table、h1、h2、h3、h4、h5、h6、th、td、ol、ul、em
- (注意)当前版本并未包含对HTML5标签的重置定义
- 初始默认链接样式：默认链接样式及链接悬浮样式
- 常用样式定义：清除浮动、隐藏元素、省略号、人民币价格表示、文字适配
