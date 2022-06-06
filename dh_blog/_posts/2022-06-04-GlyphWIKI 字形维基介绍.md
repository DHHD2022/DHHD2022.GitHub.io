---
layout: post
title:  "GlyphWiki 字形维基介绍"
info: 本文介绍GlyphWiki库。
keywords: "数据库，汉字，字形"
type: "BasIntro"
author: Jia
categories: dh_blog
---

▾ 名称：GlyphWiki

▾ 中文：字形维基

▾ 链接：[点击这里](http://zht.glyphwiki.org/)

## 简介

GlyphWiki是一个字形数据库，目的是提供汉字字形的录入和管理。其运营者为日本大东文化大学的副教授上地宏一。该网站模板为维基百科，用户可按照字头进行搜索，也可以注册登录并制作自己的字形数据。目前该站收录字形高达80万个，并且仍然在不断发展中。

## 字形与编码

汉字编码是一项非常繁琐的任务，因为汉字字形变体众多，各种异体、异形字的存在使这一领域更为错综复杂。

在Unicode的形成过程中，汉字的异体字形编码逻辑并不一致。有一些字形被视作单独的字，并被赋予码位；而有些字形则并未如此设置。比如，“青”和“靑”两个字形分别为“U+9752”和“U+9751”；然而“情”和“⿰忄靑”则共用“U+60C5”。这样的情况在Unicode中非常多见，使得汉字编码呈现出一定的混乱。

另外，Unicode虽然一直在扩大汉字包（Unicode 13.0已更新至CJK Unified Ideographs Extension G），但仍有不少汉字或字形未被收录。

而GlyphWiki的出现，对于Unicode的不足之处提供了很好的补充。

## 使用

GlyphWiki网站的结构简洁而清晰，用户在左侧搜索框内输入想要查询的汉字或其码位，即可进行搜索。

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/1.png)

如图，我们搜索“青”或“u9752”，打开了“青”字信息页面，此处可下载svg格式图像以及单个字的ttf字体文件。在“文字编码相关信息”栏目中，我们可以点击链接查看“青”字在CHISE和Unihan两个汉字数据库中的信息。此外，我们还可以看到各地区（大陆、港、台、日、韩等地）的标准字形。

在“关联字形”栏目中，我们可以根据“青”字的异体字来查看具体字形变体。

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/2.png)

如图，“青”（u9752）本字有众多字形变体，包括“⿱王月”、“⿺青丶”等。括号内为该字形的IDS描述方式对应的码位。如(u2ffa-u9752-u4e36)对应的三个字符即为：“⿺”“青”“丶”。关于IDS的知识，可参见上周“平安时代汉字字书”数据库介绍。

继续往下浏览，我们可以看到更多“青”的异体字的字形变体。

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/3.png)

左侧标明了异体字的码位，以及作为规范字的出处。

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/4.png)

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/5.png)

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/6.png)

如图，包括古字、二简字等字形也都收录其中。点击任一字，可以跳到以该字为字头的信息页。

搜索功能可以快速完成对汉字字形查询和研究的需求。但如果所想要查找的字形并未被收录，用户也有机会自行编辑字形。

![image](https://raw.githubusercontent.com/DHHD2022/DHHD2022.GitHub.io/main/pics/2022-06-06/7.png)

点击页面最上方的“编辑”功能，用户可以进入编辑页面。网站提供了基于HTML5的kage-editor，如图所示，可自由地对当前字形进行修改或重制。

此外，用户也可以在“讨论”页面与其他人进行交流；而在“历史”页面，则可查阅该字头信息页的修订历史。

## 评价

GlyphWiki作为一个大型的字形数据库，对研究汉字和汉字编码的人员提供了极大的便利。不仅数据开放获取，还给予了用户进行编辑的权限。从数字项目的评价标准来看，该数据库的数据质量和自由度都较好。

此外，该数据库用户界面适配多语言，有中、日、韩、英四种语言可供选择。其关于页、通知页及教程也以多语言写成，具有跨文化的特点。运营者（网站中ID为kamichi）本身熟练掌握日、英、中文，并且希望用户也能量化表明对中、日、韩、英语的掌握程度。这一定程度上能促进汉字圈范围内研究者的交流讨论。
