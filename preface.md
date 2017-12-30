# 前言-Preface

> 本页为中英文对照，中文版可在[这里](http://www.importnew.com/16560.html)找到。

---

INTRODUCTION TO PROGRAMMING USING JAVA is a free introductory computer programming textbook that uses Java as the language of instruction. It is suitable for use in an introductory programming course and for people who are trying to learn programming on their own. There are no prerequisites beyond a general familiarity with the ideas of computers and programs. There is enough material for a full year of college-level programming. Chapters 1 through 7 can be used as a textbook in a one-semester college-level course or in a year-long high school course. The remaining chapters can be covered in a second course.

**《Java编程入门》** 是一本使用Java作为入门语言的免费计算机编程课本。可以用作编程入门课程教材，也可以用来自学编程。阅读本书只需要对计算机和编程有一般性了解。本书中包含了一整年大学编程课程内容。第1章至第7章可以满足大学一学期课程或者高中一学年课程的教学，余下的章节可以作为第2门课程。

The Seventh Edition of the book covers "Java 7." The most recent version of Java is 8, but this book has only a few very short mentions of the new features in Java 8.

本书的第七版涵盖了“Java 7”的所有内容。Java最新版本是Java8。在这本书中只有一部分内容涉及Java 8的新特性。

> (译注：本书时间写得早，所以当时Java最新版本是 Java 8。）

The home web site for this book is [http://math.hws.edu/javanotes/][1]. The page at that address contains links for downloading a copy of the web site and for downloading PDF versions of the book. The web site -- and the web site download -- includes source code for the sample programs that are discussed in the text, answers to end-of-chapter quizzes and a discussion and solution for each end-of-chapter exercises. Readers are encouraged to download the source code for the examples and to read and run the programs as they read the book. Readers are also strongly encouraged to read the exercise solutions if they want to get the most out of this book.

这本书的主页是 [http://math.hws.edu/javanotes/][1]，提供了下载整个网站和本书PDF版本的链接。下载的网站内容包含这本书中使用的示例源代码、每章课后测试的答案和结尾练习的解答。非常推荐读者下载这些示例代码，在阅读的同时读代码并且运行这些程序。要想从这本书中得到最大的收获，强烈推荐读完所有练习解答。

In style, this is a textbook rather than a tutorial. That is, it concentrates on explaining concepts rather than giving step-by-step how-to-do-it guides. I have tried to use a conversational writing style that might be closer to classroom lecture than to a typical textbook. This is certainly not a Java reference book, and it is not a comprehensive survey of all the features of Java. It is **not** written as a quick introduction to Java for people who already know another programming language. Instead, it is directed mainly towards people who are learning programming for the first time, and it is as much about general programming concepts as it is about Java in particular. I believe that Introduction to Programming using Java is fully competitive with the conventionally published, printed programming textbooks that are available on the market. (Well, all right, I'll confess that I think it's better.)

在内容风格上，这本书更偏向于课本而不是教程。换句话说，它更专注于概念的解释，而不是指导一步步如何去做。我试图采用一种对话风格进行写作，更贴近课堂教学而不是像传统的课本那样。当然，它不是Java参考书，更不是对Java所有功能的总结。这本书**不是**为那些已经了解某种其它编程语言的人所编写的Java快速入门。相反，它针对的是那些第一次学习编程的人，更多的以Java为例讲授一般编程概念。我相信，这本《Java编程入门》完全可以匹敌市面上那些传统出版社发行、印刷的编程课本。（好吧，我承认在我看来这本书会更胜一筹）

There are several approaches to teaching Java. One approach uses graphical user interface programming from the very beginning. Some people believe that object oriented programming should also be emphasized from the very beginning. This is not the approach that I take. The approach that I favor starts with the more basic building blocks of programming and builds from there. After an introductory chapter, I cover procedural programming in Chapters 2, 3, and 4. Object-oriented programming is introduced in Chapter 5. Chapter 6 covers the closely related topic of event-oriented programming and graphical user interfaces. Arrays are introduced in Chapter 3 with a full treatment in Chapter 7. Chapter 8 is a short chapter that marks a turning point in the book, moving beyond the fundamental ideas of programming to cover more advanced topics. Chapter 8 is about writing robust, correct, and efficient programs. Chapters 9 and 10 cover recursion and data structures, including the Java Collection Framework. Chapter 11 is about files and networking. Chapter 12 covers threads and parallel processing. Finally, Chapter 13 returns to the topic of graphical user interface programming to cover some of Java's more advanced capabilities.

教授Java有很多方法。一种是从一开始就是用图形化编程界面。一些人认为，应该从开始就强调面向对象编程。这不是我的方式。我钟爱的方式是从更基本的编程模块开始构建，然后从基本模块继续学习。在介绍章节之后的第2、3和4章，我讨论了面向过程的程序设计。在第5章介绍了面向对象编程。第6章讨论了面向事件编程的相关话题以及图形用户界面。第3章提到的数组在第7章进行了完整介绍。第8章是一个很短的章节，标志了本书的一个转折点。从编程基础概念的介绍转向了更高级的话题。第8章涉及了如何编写健壮、正确和高效的程序。第9章和第10章讨论了递归和数据结构，包括Java集合框架。第11章是关于文件和网络。第12章讨论了线程和并发处理。最后，第13章回到了图形用户界面编程，介绍了Java更加高级的功能。

---

The Seventh Edition of "Introduction to Programming using Java" is not a huge update from the sixth edition. In fact, my main motivation for the new version was to remove any use of applets or coverage of applets from the book. Applets are Java programs that run on a web page. When Java first came out, they were exciting, and it seemed like they would become a major way of creating active content for the Web. Up until the sixth edition, the web pages for this book included applets for running many of the sample programs. However, because of security issues and the emergence of other technologies, applets are no longer widely used. Furthermore, the most recent versions of Java made it fairly difficult and unpleasant to use the applets in the book. In place of applets, I have tried to make it as easy as possible for readers to download the sample programs and run them on their own computers.

第7版《Java编程入门》没有对第6版进行大幅更新。实际上，编写新版的主要动机是从书中移除applet部分和相关讨论。Applet是运行在网页中的Java程序。Java刚诞生时，看起来applet似乎会成为创建Web动态内容的主流方式。直到第6版，本书的主页还包含了示例applet程序。然而，由于安全因素和其它技术的出现，applet不再广泛使用。加之最近发布的Java版本让applet使用更加困难，因此决定不在书中介绍applet。移除applet后，我把精力投在了让读者们可以更方便地下载和运行示例程序。

Another significant change in the seventh edition is that arrays are now introduced in Chapter 3 in a basic form that is used throughout the next three chapters. Previously, arrays were not introduced until Chapter 7, after objects and GUI programming had already been covered. Much of the more advanced coverage of arrays is still in Chapter 7.

第7版的另一个显著改进是，在第3章加入了数组的简要介绍。在接下来的3个章节里会更详细地讨论数组。之前的版本中，数组在对象和GUI编程之后，到第7章才开始介绍。新版的第7章包含了数组高级用法的讨论。

Aside from that, there are many small improvements throughout, mostly related to features that were new in Java 7. Version 7.0.2 is the final release of the seventh edition.

除了上述变化，还有很多针对Java 7新功能的小改进。

---

The latest complete edition of *Introduction to Programming using Java* is available on line at [http://math.hws.edu/javanotes/][1]. The first version of the book was written in 1996, and there have been several editions since then. All editions are archived (at least until my retirement) at the following Web addresses:

* First edition: [http://math.hws.edu/eck/cs124/javanotes1/][2] (Covers Java 1.0.)
* Second edition: [http://math.hws.edu/eck/cs124/javanotes2/][3] (Covers Java 1.1.)
* Third edition: [http://math.hws.edu/eck/cs124/javanotes3/][4] (Covers Java 1.1.)
* Fourth edition: [http://math.hws.edu/eck/cs124/javanotes4/][5] (Covers Java 1.4.)
* Fifth edition: [http://math.hws.edu/eck/cs124/javanotes5/][6] (Covers Java 5.0.)
* Sixth edition: [http://math.hws.edu/eck/cs124/javanotes6/][7] (Covers Java 5.0, with a bit of 6.0.)
* Seventh edition: [http://math.hws.edu/eck/cs124/javanotes7/][8] (Covers Java 7.)

*《Java编程入门》的最新版*可以在线获得 [http://math.hws.edu/javanotes/][1]。该书的第1版写于1996年，自那以后有了很多版本。各个不同的版本可以在下列网址看到：

* 第1版：[http://math.hws.edu/eck/cs124/javanotes1/][2] （Java 1.0）
* 第2版： [http://math.hws.edu/eck/cs124/javanotes2/][3] （Java 1.1）
* 第3版：[http://math.hws.edu/eck/cs124/javanotes3/][4] （Java 1.1）
* 第4版： [http://math.hws.edu/eck/cs124/javanotes4/][5] （Java 1.4）
* 第5版： [http://math.hws.edu/eck/cs124/javanotes5/][6] （Java  5.0）
* 第6版： [http://math.hws.edu/eck/cs124/javanotes6/][7] （Java  5.0及更高版本）
* 第7版：[http://math.hws.edu/eck/cs124/javanotes7/][8] （Java 7）

Introduction to Programming using Java is free, but it is not in the public domain. Version 7 is published under the terms of the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-nc-sa/3.0/][9]. For example, you can:

* Post an unmodified copy of the on-line version on your own Web site (including the parts that list the author and state the license under which it is distributed!).
* Give away unmodified copies of this book or sell them at cost of production, as long as they meet the requirements of the license.
* Make modified copies of the complete book or parts of it and post them on the web or otherwise distribute them non-commercially, provided that attribution to the author is given, the modifications are clearly noted, and the modified copies are distributed under the same license as the original. This includes translations to other languages.

《Java编程入门》是免费的，不受版权限制。第7版基于“署名-非商业性使用-相同方式共享3.0”授权发布。要查看协议的副本，可以访问 [http://creativecommons.org/licenses/by-nc-sa/3.0/][9]。你可以：

* 在你自己的网站上发布未经修改的版本（包含作者署名和许可声明！）
* 在遵守协议的前提下，你可以分发或出售未经修改的版本。
* 对本书修改或部分修改可以在互联网上发布且用于非商业目的。要求版本归属作者、明确地标注修改内容并且修改版本遵循原协议发布，包括翻译成其它语言。

For uses of the book in ways not covered by the license, permission of the author is required.

协议中未注明的使用情况，需要征得原作者许可。

While it is not actually required by the license, I do appreciate hearing from people who are using or distributing my work.

虽然协议中没有明确对此进行要求，但我非常期待了解人们使用或传播我的工作。

---

**A technical note on production:** The on-line and PDF versions of this book are created from a single source, which is written largely in XML. To produce the PDF version, the XML is processed into a form that can be used by the TeX typesetting program. In addition to XML files, the source includes DTDs, XSLT transformations, Java source code files, image files, a TeX macro file, and a couple of scripts that are used in processing. The scripts work on Linux and on Mac OS.

**关于本书的技术说明：** 本书的在线和PDF版本来自同一份原稿，主要由XML编写。为了输出PDF版本，该XML文件被处理为可以被TeX排版程序使用的格式。除了XML文件，原稿还包含了DTD、XSLT转换、Java源代码文件、图片、TeX宏文件和一些用来处理的脚本。这些脚本可以在Linux和Mac OS上运行。

**I have made the complete source files available for download at the following address:**

**本书的源文件可以从下面网址获得：**

[http://math.hws.edu/eck/cs124/downloads/javanotes7-full-source.zip][10]

These files were not originally meant for publication, and therefore are not very cleanly written. Furthermore, it requires a fair amount of expertise to use them. However, I have had several requests for the sources and have made them available on an "as-is" basis. For more information about the sources and how they are used see the [README file][12] from the source download.

这些文件本意并不用来出版，因此没有非常仔细地编写，使用这些文件需要很多专业知识。然而，我收到了很多请求想要这些文件，因此就“原封不动”的提供出来。这些文件的详细信息及如何使用说明，请下载并参阅其中的[README][12]。

---

> Professor David J. Eck
> Department of Mathematics and Computer Science
> Hobart and William Smith Colleges
> 300 Pulteney Street
> Geneva, New York 14456, USA
> Email: eck@hws.edu 
> WWW: [http://math.hws.edu/eck/][11]
> 
> 大卫·j·艾克(David J. Eck)教授
> 数学和计算机科学系
> 霍巴特威廉史密斯学院
> 美国纽约州日内瓦区普尔特尼街300号
> 邮件：eck@hws.edu
> 网站：[http://math.hws.edu/eck/][11]

[1]: http://math.hws.edu/javanotes/
[2]: http://math.hws.edu/eck/cs124/javanotes1/
[3]: http://math.hws.edu/eck/cs124/javanotes2/
[4]: http://math.hws.edu/eck/cs124/javanotes3/
[5]: http://math.hws.edu/eck/cs124/javanotes4/
[6]: http://math.hws.edu/eck/cs124/javanotes5/
[7]: http://math.hws.edu/eck/cs124/javanotes6/
[8]: http://math.hws.edu/eck/cs124/javanotes7/
[9]: http://creativecommons.org/licenses/by-nc-sa/3.0/
[10]: http://math.hws.edu/eck/cs124/downloads/javanotes7-full-source.zip
[11]: http://math.hws.edu/eck/
[12]: http://math.hws.edu/javanotes/README-full-source.txt