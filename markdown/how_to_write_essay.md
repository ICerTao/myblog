# 毕设论文写作的高效姿势

## 引言

之前从来没有写过论文，想要格式正确地完成本科毕业论文显得有些痛苦，在经历过几日的折磨之后，记录一些自以为的高效写作姿势。我写作的平台是 MacOS 上的 Typora 和 WPS，并未安装任何插件，其中 typora 用于内容写作，WPS 用于格式调整。

本文主要内容是 WPS 上调整格式的高效姿势，无论是苹果还是微软还是金山，技巧应该都是相通的。

本文格式适用于 2022 年西北工业大学本科生毕业论文

## 内容写作

首先根据个人的文本写作习惯，专注于论文文字、插图、表哥等的内容产生，先不需要拘泥于格式会使内容产出更加顺畅，我先是在 typora 软件上将内容都写在了 markdown 上，个人也比较推荐 markdown 的内容写作方式。



## 预设字体样式

频繁调字体很不优雅，即便用格式刷也不高效，因此先完成文字格式的预设，`菜单栏 - 开始`的字体预设位置处右击修改样式完成格式的预设，需要修改其中的字体和段落项

![截屏2022-05-31 19.06.17](how_to_write_essay.assets/截屏2022-05-31 19.06.17.png)

<img src="how_to_write_essay.assets/截屏2022-05-31 19.16.51.png" alt="截屏2022-05-31 19.16.51" style="zoom:50%;" />

 所设计的字体样式有以下几种，其中所有样式的段前段后需要设置成 0 行

- 正文：宋体小四，1.25 倍行距（mac 上的 wps 的标准宋体名称为中字正文）
- 一级标题：绪论、每一章、致谢、毕业设计小结、参看文献等。黑体三号
- 二级标题：每一章的子标题，四号黑体
- 三级标题：黑体小四号
- 图片表格标注：宋体五号居中

在向 word 中粘贴文字内容时，只要光标处于所在文字处，然后点击预设格式直接应用即可。

## 分页分节

为了更好地完成文章管理，需要打开`顶部菜单栏 - 视图- 显示段落标记`功能，此功能会标记出空格、回车、分页符等符号，并且有利于在从 pdf 文件中复制文字时删除空格。

<img src="how_to_write_essay.assets/截屏2022-05-31 19.20.52.png" alt="截屏2022-05-31 19.20.52" style="zoom:50%;" />

文章需要分为三节：

- 第一节：封面、中英文摘要、目录
- 第二节：正文章节
- 第三节：致谢、毕业设计小结

因此需要在每一节的末尾添加分节符，`菜单栏 - 插入 - 分页 - 下一页分节符`，对于每一章之间，可以添加分页符来完成分页，在论文写作时分页符分节符可以有效地辅助页面格式管理

<img src="how_to_write_essay.assets/截屏2022-05-31 19.25.18.png" alt="截屏2022-05-31 19.25.18" style="zoom:50%;" />

## 参考文献

在需要添加引用的正文内容后通过`菜单栏 - 引用 - 插入尾注`自动生成参考文献的标注，然后通过`脚注/尾注分割线右下角的直角`将位置设置为节的结尾，此时就会在上面所提到过的第二第三节之间自动生成参考文献序号。同时将编号格式的方括号样式进行勾选。



<img src="how_to_write_essay.assets/截屏2022-05-31 19.39.36.png" alt="截屏2022-05-31 19.39.36" style="zoom:50%;" />

此时文字后面与正文末尾的序号格式均为上标格式，需要对正文末尾的序号格式进行单独调整，取消上标格式，此操作可以通过格式刷实现。

## 数学公式

在 typora 上写内容时，所有的公式都是基于 latex 语法所写，因此可以直接复制代码内容，通过`菜单栏 - 插入 - LaTex公式`来产生公式图片，所产生的图片很大且位置奇特，行内公式因此需要设置图片布局格式为紧密型环绕后进行缩放与位置调整

<img src="how_to_write_essay.assets/截屏2022-05-31 19.50.40.png" alt="截屏2022-05-31 19.50.40" style="zoom:50%;" />

<img src="how_to_write_essay.assets/截屏2022-05-31 19.52.53.png" alt="截屏2022-05-31 19.52.53" style="zoom:50%;" />

> 据同学说，mathtype 插件配合 mathpix 非常好用，可以直接将公式图片识别为 latex 代码

## 目录

目录在完成全文的格式调整后，通过`菜单栏 - 引用 - 目录`来智能识别目录再手工调整。选择图示中的第三种生成三级目录。目录的字体也是通过[预设字体样式](#预设字体样式)的方式修改字体样式。

<img src="how_to_write_essay.assets/截屏2022-05-31 20.07.30.png" alt="截屏2022-05-31 20.07.30" style="zoom:50%;" />

> 也可以在大纲中设置好标题等级，再一键生成目录

## 页码

页码通过`菜单栏 - 插入 - 页码 - 页脚中间`来添加，此时页码应用于全文，而我们需要从第二节（即目录以后，第一章开始）重新编号，通过`修改页码`按照图中设置即可调整

<img src="how_to_write_essay.assets/截屏2022-05-31 20.14.10.png" alt="截屏2022-05-31 20.14.10" style="zoom:50%;" />

<img src="how_to_write_essay.assets/截屏2022-05-31 20.15.34.png" alt="截屏2022-05-31 20.15.34" style="zoom:50%;" />

> 别的好像也没啥了，早点写完早摆烂

## Tips

- 对于间隔不正确的字体，可以通过选中后右击`段落`选项更改
- 图片前后空行
- 从别处粘贴的文本要改为匹配当前格式