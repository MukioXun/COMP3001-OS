# COMP3001 - 操作系统
<!-- TOML-META: repo_type="normal" -->
<!-- TOML-BADGES: source="grades_summary" -->

![成绩构成](https://img.shields.io/badge/成绩构成-gold)
![平时分10%](https://img.shields.io/badge/平时分-10%25-wheat)
![实验30%](https://img.shields.io/badge/实验-30%25-wheat)
![期末考试60%](https://img.shields.io/badge/期末考试-60%25-wheat)

两位授课老师风格迥异，但是并不影响考试的公平性——因为考试考得基本跟上课关系不太大。

## 授课教师

<!-- TOML-LECTURERS: part="items" -->
- 刘川意
  <!-- TOML-ITEM: id="review-刘川意-1" -->
  - 上课抽点回答问题。
  - PPT基本是《操作系统导论》的原版英文PPT。
  - 助教非常负责。
  - 不一定课前发PPT，基本随缘。
- 夏文
  <!-- TOML-ITEM: id="review-夏文-1" -->
  - 讲课很专业。中文PPT，内容多，总的参考《CSAPP》。
  - 但是，两位老师虽然风格迥异，但是并不影响考试的公平性——因为考试考得基本跟上课关系不太大（见考试部分）。
- [陈斌](http://ai.hitsz.edu.cn/info/1030/1076.htm)
  <!-- TOML-ITEM: id="review-[陈斌](http://ai.hitsz.edu.cn/info/1030/1076.htm)-1" -->
  - “大陈斌”，研究员，和这个[陈斌](https://homepage.hit.edu.cn/BinChen)是两个老师哦。
  - 人工智能班专属老师（存疑）。老师思路非常发散，讲究一个“想到什么讲什么”。有时老师语速快得听不懂，而且听不清，所以要往前坐（其实坐在后边老师也会来到你面前亲切询问）。老师会认真记住每一位同学的名字。
  - 老师随机来到某位同学面前，亲切问你：听懂了没？如果你没听懂，或者没听（无论是你表示出很迷茫的表情，或者眼神——老师看出来你没听懂），老师就会问你：哪里没听懂啊？然后选中另外一名同学继续亲切提问。
  - 如果你表示听懂了（或者没听：象征性地嗯了一下），老师会热情邀请你进行讲解：来，给大家讲一下。
  - 总之互动性很强，上课会很有趣；签到会提前在QQ群说。（可能是前一天晚上，也可能是上课前几分钟）PPT会在前几节课全发出来；作业交在HITSZ Grader2，DDL也很宽松（两周+），题目都很简单。

## 教材
<!-- TOML-SECTION: title="教材" -->

<!-- TOML-ITEM: id="item-教材-1" -->

- **Operating Systems: Three Easy Pieces (操作系统导论)**（Remzi H. Arpaci-Dusseau / Andrea C. Arpaci-Dusseau / Arpaci-Dusseau Books / textbook）
- **Computer Systems: A Programmer's Perspective (CSAPP)**（Randal E. Bryant / David R. O'Hallaron / Pearson / 3rd Edition / textbook）
- **王道考研系列：操作系统考研复习指导**（王道论坛 / 电子工业出版社 / textbook）

## 关于考试
<!-- TOML-SECTION: title="关于考试" -->

<!-- TOML-ITEM: id="item-关于考试-1" has_author="true" -->

可以参考《王道考研——操作系统》进行复习。

操作系统确实是 CS 的一门很重要的课程，好好学习必不会吃亏！
课程可能会设置「附加题」，保证平时分 + 实验分拉满。请审慎选择！

## 关于实验
<!-- TOML-SECTION: title="关于实验" -->

<!-- TOML-ITEM: id="item-关于实验-1" -->

[实验指导书链接](https://os-labs.p.cs-lab.top/index.html)

实验大多基于Linux，如果可能的话最好提前接触，学习一些简单的命令行操作与操作命令。**务必提前准备好实验平台！**

2018级的前四个实验选用了基于MIT6.828/6.S081（2019）课程的XV6作为实验平台，完成一些指定任务；最后一个实验需要设计一个文件系统。每年的实验都*不太一样*。

2026春：主要负责老师是仇老师，她已经迭代了N版实验框架（包含四个MIT的实验+一个基于FUSE的Ext2）。操作系统的实验难度呈指数级增大，多数同学都会直接vibe coding了Lab4（页表）。如果自己做的话，需要花费相当长的时间！

好在MIT的系列实验都有“巨人的肩膀”相助（CSDN）；最后的Ext2系统设计，确实需要考验一些功夫，包括硬盘结构整体设计与函数封装、指针使用、还有驱动接口调用等问题。而且在设计过程中，会出现各种运行时BUG，需要花一些时间。

最后一节实验课会进行课堂检查，会要求现场改代码、解读代码等等，所以需要做好应对之策。（尽量避免全AI写。因为真的会问你这是怎么实现的。）

可以多问老师和AI大人（尽量不要使用deepseek）。助教可能派不上太大用处。
