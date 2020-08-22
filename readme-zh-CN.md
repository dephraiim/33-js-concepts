<h1 align="center">
<br>
  <a href="https://github.com/leonardomso/33"><img src="https://i.imgur.com/dsHmk6H.jpg" alt="33 Concepts Every JS Developer Should Know" width=200"></a>
  <br>
    <br>
  33 Concepts Every JavaScript Developer Should Know
  <br><br>
</h1>

[![Follow me](https://img.shields.io/twitter/follow/leonardomso.svg?style=for-the-badge)](https://twitter.com/leonardomso)

## 介绍

创建此存储库旨在帮助开发人员掌握JavaScript的概念。这不是必需的，而是未来研究的指南。它基于由[史蒂芬·斯提斯](https://twitter.com/stephenthecurt) and you can read it [这里](https://medium.com/@stephenthecurt/33-fundamentals-every-javascript-developer-should-know-13dd720a90d1).

**被GitHub视为其中之一[2018年顶级开源项目！](https://blog.github.com/2018-12-13-new-open-source-projects/)**

## Community

随时提交PR，并添加指向您自己的摘要或评论的链接。如果您想将软件库翻译成您的母语，请随时这样做。

此仓库的所有翻译将在下面列出：

-   [阿拉伯](https://github.com/amrsekilly/33-js-concepts)-Amr Elsekilly
-   [中文](https://github.com/stephentian/33-js-concepts)— ret Ian
-   [Portuguese-BR](https://github.com/tiagoboeing/33-js-concepts)—蒂亚戈·波音
-   [韩语](https://github.com/yjs03057/33-js-concepts.git)-李素恩
-   [西班牙文](https://github.com/adonismendozaperez/33-js-conceptos)-阿多尼斯·门多萨
-   [Turkish](https://github.com/ilker0/33-js-concepts)-伊尔克·德米尔
-   [Russian](https://github.com/gumennii/33-js-concepts)-Mihail Gumennii
-   [越南文](https://github.com/nguyentranchung/33-js-concepts)-阮陈忠
-   [抛光](https://github.com/lip3k/33-js-concepts) — Dawid Lipinski
-   [波斯语](https://github.com/majidalavizadeh/33-js-concepts) — Majid Alavizadeh
-   [Indonesian](https://github.com/rijdz/33-js-concepts) — Rijdzuan Sampoerna
-   [法文](https://github.com/robinmetral/33-concepts-js) — Robin Métral
-   [没有。](https://github.com/vikaschauhan/33-js-concepts)—维卡斯·乔汉（Vikas Chauhan）
-   [希腊语](https://github.com/DimitrisZx/33-js-concepts)-Dimitris Zarachanis
-   [日本](https://github.com/oimo23/33-js-concepts) — oimo23
-   [德语](https://github.com/burhannn/33-js-concepts)-布尔汉
-   [乌克兰](https://github.com/AndrewSavetchuk/33-js-concepts-ukrainian-translation)—安德鲁·萨维奇克（Andrew Savetchuk）
-   [僧伽罗语](https://github.com/ududsha/33-js-concepts)-Uday Shamendra
-   [义大利文](https://github.com/Donearm/33-js-concepts)-詹卢卡·菲奥雷（Gianluca Fiore）

* * *

## 目录

1.  **[Call Stack](#1-call-stack)**
2.  **[基本类型](#2-primitive-types)**
3.  **[值类型和引用类型](#3-value-types-and-reference-types)**
4.  **[隐式，显式，标称，结构化和鸭式打字](#4-implicit-explicit-nominal-structuring-and-duck-typing)**
5.  **[== vs === vs typeof](#5--vs--vs-typeof)**
6.  **[功能范围，块范围和词法范围](#6-function-scope-block-scope-and-lexical-scope)**
7.  **[Expression vs Statement](#7-expression-vs-statement)**
8.  **[IIFE，模块和命名空间](#8-iife-modules-and-namespaces)**
9.  **[消息队列和事件循环](#9-message-queue-and-event-loop)**
10. **[setTimeout，setInterval和requestAnimationFrame](#10-settimeout-setinterval-and-requestanimationframe)**
11. **[JavaScript Engines](#11-javascript-engines)**
12. **[按位运算符，类型数组和数组缓冲区](#12-bitwise-operators-type-arrays-and-array-buffers)**
13. **[DOM和布局树](#13-dom-and-layout-trees)**
14. **[工厂和阶级](#14-factories-and-classes)**
15. **[调用，应用和绑定](#15-this-call-apply-and-bind)**
16. **[new, Constructor, instanceof and Instances](#16-new-constructor-instanceof-and-instances)**
17. **[原型继承与原型链](#17-prototype-inheritance-and-prototype-chain)**
18. **[Object.create和Object.assign](#18-objectcreate-and-objectassign)**
19. **[映射，缩小，过滤](#19-map-reduce-filter)**
20. **[Pure Functions, Side Effects and State Mutation](#20-pure-functions-side-effects-and-state-mutation)**
21. **[关闭](#21-closures)**
22. **[高阶函数](#22-high-order-functions)**
23. **[Recursion](#23-recursion)**
24. **[集合和生成器](#24-collections-and-generators)**
25. **[承诺](#25-promises)**
26. **[异步/等待](#26-asyncawait)**
27. **[数据结构](#27-data-structures)**
28. **[昂贵的操作和大O符号](#28-expensive-operation-and-big-o-notation)**
29. **[演算法](#29-algorithms)**
30. **[继承，多态和代码重用](#30-inheritance-polymorphism-and-code-reuse)**
31. **[设计模式](#31-design-patterns)**
32. **[部分应用，固化，组成和管道](#32-partial-applications-currying-compose-and-pipe)**
33. **[清洁代码](#33-clean-code)**

* * *

## 1.调用堆栈

### 文章

-   📜[了解Javascript调用堆栈，事件循环— Gaurav Pandvia](https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec)
-   📜[Understanding the JavaScript Call Stack — Charles Freeborn](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
-   📜[Javascript: What Is The Execution Context? What Is The Call Stack? — Valentino Gagliardi](https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/)
-   📜[什么是JS事件循环和调用栈？ —杰西·特尔福德](https://gist.github.com/jesstelford/9a35d20a2aa044df8bf241e00d7bc2d0)
-   📜[呼叫堆栈-MDN](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)
-   📜[了解JavaScript中的执行上下文和执行堆栈— Sukhjinder Arora](https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0)
-   📜[JavaScript的工作原理：引擎，运行时和调用堆栈的概述— Alexander Zlatkov](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
-   📜[JavaScript执行上下文，提升，范围和闭包的终极指南— Tyler McGinnis](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)
-   📜[How JavaScript Works Under The Hood: An Overview of JavaScript Engine, Heap and, Call Stack — Bipin Rajbhar](https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o)

### 影片

-   🎥[Javascript: the Call Stack explained — Coding Blocks India](https://www.youtube.com/watch?v=w6QGEiQceOM)
-   🎥[JS调用堆栈在9分钟内得到解释— Colt Steele](https://www.youtube.com/watch?v=W8AeMrVtFLY)
-   🎥[JavaScript执行堆栈— Codecademy](https://www.youtube.com/watch?v=jT0USJeNFEA)
-   🎥[什么是调用栈？ —埃里克·特劳布（Eric Traub）](https://www.youtube.com/watch?v=w7QWQlkLY_s)
-   🎥[通话堆栈-凯文·德鲁姆](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
-   🎥[了解JavaScript执行-Codesmith](https://www.youtube.com/watch?v=Z6a1cLyq7Ac&list=PLWrQZnG8l0E4kd1T_nyuVoxQUaYEWFgcD)
-   🎥 [通话堆栈和事件循环—电影com](https://www.youtube.com/watch?v=mk0lu9MKBto)
-   🎥[JavaScript执行上下文，提升，范围和闭包的终极指南— Tyler McGinnis](https://www.youtube.com/watch?v=Nt-qa_LlUH0)
-   🎥[What the heck is the event loop anyway? — Philip Roberts](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
-   🎥[JavaScript调用堆栈-代码的厨房](https://www.youtube.com/watch?v=ygA5U7Wgsg8)

**[⬆回到顶部](#table-of-contents)**

* * *

## 2.基本类型

### 文章

-   📜[如何在JavaScript中编码数字-Axel Rauschmayer博士](http://2ality.com/2012/04/number-encoding.html)
-   📜[What You Need to Know About JavaScript Number Type — Max Wizard K](https://medium.com/dailyjs/javascripts-number-type-8d59199db1b6)
-   📜[每个JavaScript开发人员应了解的浮点数-Chewxy](https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/)
-   📜 [JavaScript基元的秘密生活-Angus Croll](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)
-   📜 [基本类型-流](https://flow.org/en/docs/types/primitives/)
-   📜[（不是）JavaScript中的所有东西都是对象— Daniel Li](http://blog.brew.com.hk/not-everything-in-javascript-is-an-object/)
-   📜[JavaScript data types and data structures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)
-   📜 [深入探讨JavaScript对象— Arfat Salman](https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12)
-   📜[The differences between Object.freeze() vs Const in JavaScript — Bolaji Ayodeji](https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c)

### 影片

-   🎥[JavaScript Reference vs Primitive Types — Academind](https://www.youtube.com/watch?v=9ooYYRLdg_g)
-   🎥[JavaScript基本类型— Simon Sez IT](https://www.youtube.com/watch?v=HsbWQsSCE5Y)
-   🎥[JavaScript中的值类型和引用类型—用Mosh编程](https://www.youtube.com/watch?v=e-_mDyqm2oU)
-   🎥[JavaScript基本数据类型— Avelx](https://www.youtube.com/watch?v=qw3j0A3DIzQ)
-   🎥[Everything you never wanted to know about JavaScript numbers — Bartek Szopka](https://www.youtube.com/watch?v=MqHDDtVYJRI)
-   🎥[什么是Javascript中的变量？ —所有人的JS](https://www.youtube.com/watch?v=B4Bbmei_thw)
-   🎥[JAVASCRIPT中的原始数据类型-代码的厨房](https://www.youtube.com/watch?v=cC65D2q5f8I)

**[⬆回到顶部](#table-of-contents)**

* * *

## 3. Value Types and Reference Types

### Articles

-   📜[用JavaScript解释价值与参考的关系— Arnav Aggarwal](https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0)
-   📜[理解JavaScript中的值和引用类型— Zsolt Nagy](https://www.zsoltnagy.eu/understand-value-and-reference-types-in-javascript/)
-   📜[JavaScript中的原始类型和引用类型-Bran van der Meer](https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
-   📜[Value Types, Reference Types and Scope in JavaScript — Ben Aston](https://medium.com/@benastontweet/lesson-1b-javascript-fundamentals-380f601ba851)
-   📜[Back to roots: JavaScript Value vs Reference — Miro Koczka](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)
-   📜[掌握JavaScript中的“按值”和“按引用” —LénaFaure](https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293)
-   📜[JavaScript参考和复制变量—VítorCapretz](https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0)
-   📜[JavaScript原始值与参考值](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
-   📜[JavaScript by Reference vs. by Value — nrabinowitz](https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value)
-   📜 [JavaScript面试准备：基本类型与参考类型— Mike Cronin](https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f)

### 影片

-   🎥[Javascript Pass by Value vs Pass by Reference — techsith](https://www.youtube.com/watch?v=E-dAnFdq8k8)
-   🎥 [JavaScript Value vs Reference Types — Programming with Mosh](https://www.youtube.com/watch?v=fD0t_DKREbE)
-   🎥[JAVASCRIPT中的值和参考-代码的厨房](https://www.youtube.com/watch?v=AvkyOrWkuQc)

**[⬆回到顶部](#table-of-contents)**

* * *

## 4.隐式，显式，标称，结构化和鸭式打字

### 文章

-   📜[您需要了解的有关Javascript隐式强制的信息-Promise Tochi](https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23)

-   📜[JavaScript类型强制解释— Alexey Samoshkin](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)

-   📜[Javascript强制解释— Ben Garrison](https://hackernoon.com/javascript-coercion-explained-545c895213d3)

-   📜[JavaScript中的类型强制到底是什么？ - 堆栈溢出](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)

-   📜[您不知道JS：类型和语法，第一版\[书籍\] —凯尔·辛普森（Kyle Simpson）](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed/types%20%26%20grammar)

-   📜[在JavaScript中键入Coercion，以及为什么每个人都会理解错误。](https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong)

    ### 影片

-   🎥[==？ === ??? ...＃@ ^％-屏蔽比勒费尔德](https://www.youtube.com/watch?v=qGyqzN0bjhc&t)

-   🎥[Javascript中的强制-Hitesh Choudhary](https://www.youtube.com/watch?v=b04Q_vyqEG8)

-   🎥[JavaScript问题：什么是强制性？ -史蒂文·汉考克](https://www.youtube.com/watch?v=z4-8wMSPJyI)

-   🎥[输入：静态与动态，弱与强-Codexpanse](https://www.youtube.com/watch?v=C5fr0LZLMAs)

-   🎥 [JAVASCRIPT类型系统-代码的厨房](https://www.youtube.com/watch?v=0ei4nb49GKo)

**[⬆ Back to Top](#table-of-contents)**

* * *

## 5. == vs === vs typeof

### Articles

-   📜[JavaScript Double Equals vs. Triple Equals — Brandon Morelli](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)
-   📜[我应该在JavaScript中使用===还是==相等比较运算符？ — Panu Pitkamaki](https://bytearcher.com/articles/equality-comparison-operator-javascript/)
-   📜[== vs === JavaScript：双重等于和强迫— AJ Meyghani](https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript)
-   📜[为什么在JavaScript中使用Triple-Equals运算符？ —路易·拉扎里斯（Louis Lazaris）](https://www.impressivewebs.com/why-use-triple-equals-javascipt/)
-   📜[What is the difference between == and === in JavaScript? — Craig Buckler](https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript)
-   📜 [为什么javascript的typeof总是返回“对象”？ - 堆栈溢出](https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object)
-   📜[检查Java语言中的类型— Toby Ho](http://tobyho.com/2011/01/28/checking-types-in-javascript/)
-   📜 [如何更好地检查JavaScript中的数据类型-Webbjocke](https://webbjocke.com/javascript-check-data-types/)
-   📜[检查JavaScript中是否缺少值-Tomer Aberbach](https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html)

### Videos

-   🎥[JavaScript - The typeof operator — Java Brains](https://www.youtube.com/watch?v=ol_su88I3kw)
-   🎥 [Javascript typeof operator — DevDelight](https://www.youtube.com/watch?v=qPYhTPt_SbQ)

**[⬆回到顶部](#table-of-contents)**

* * *

## 6.功能范围，块范围和词法范围

### Articles

-   📜[You Don't Know JS Yet: Scope & Closures, 2nd Edition \[Book\] — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures)
-   📜[JavaScript Functions — Understanding The Basics — Brandon Morelli](https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99)
-   📜 [功能范围与块范围之间的斗争— Marius Herring](http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/)
-   📜 [在JavaScript中模拟块作用域— Josh Clanton](http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html)
-   📜 [The Difference Between Function and Block Scope in JavaScript — Joseph Cardillo](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe)
-   📜[JavaScript中的函数作用域和块作用域— Samer Buna](https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7)
-   📜[了解JavaScript中的范围和上下文瑞安·莫尔（Ryan Morr）](http://ryanmorr.com/understanding-scope-and-context-in-javascript/)
-   📜[JavaScript范围和闭包-Zell Liew](https://css-tricks.com/javascript-scope-closures/)
-   📜[Understanding Scope in JavaScript — Wissam Abirached](https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/)
-   📜[会讲JavaScript-变量：范围，环境和闭包— Axel Rauschmayer博士](http://speakingjs.com/es5/ch16.html)
-   📜[了解JavaScript的作用域― Hammad Ahmed](https://scotch.io/tutorials/understanding-scope-in-javascript)
-   📜[When to use a function declaration vs. a function expression ― Amber Wilkie](https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0)
-   📜[JavaScript基础备忘单：范围，上下文和“ this”-Alexandra Fren](https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai)

### 影片

-   🎥[是什么使Javascript变得怪异...和Awesome pt。 4-LearnCode.academy](https://www.youtube.com/watch?v=SBwoFkRjZvE)
-   🎥[Variable Scope in JavaScript — Kirupa Chinnathambi](https://www.youtube.com/watch?v=dhp57T3p760)
-   🎥[JavaScript块范围和功能范围— mmtuts](https://www.youtube.com/watch?v=aK_nuUAdr8E)
-   🎥[词汇范围是什么？ — NWCalvank](https://www.youtube.com/watch?v=GhNA0r10MmA)

**[⬆回到顶部](#table-of-contents)**

* * *

## 7.表达与陈述

### 文章

-   📜[All you need to know about Javascript's Expressions, Statements and Expression Statements — Promise Tochi](https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-and-expression-statements-5k2)
-   📜[函数表达式与函数声明— Paul Wilkins](https://www.sitepoint.com/function-expressions-vs-declarations/)
-   📜 [JavaScript Function — Declaration vs Expression — Ravi Roshan](https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38)
-   📜 [函数声明与函数表达式— Mandeep Singh](https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052)
-   📜[Function Declarations vs. Function Expressions — Anguls Croll](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### Videos

-   🎥[Expressions vs. Statements in JavaScript — Hexlet](https://www.youtube.com/watch?v=WVyCrI1cHi8)
-   🎥[JavaScript-表达式与语句— WebTunings](https://www.youtube.com/watch?v=3jDpNGJkupA)
-   🎥 [Function Statements and Function Expressions — Codeacademy](https://www.youtube.com/watch?v=oB5rH_9bqAI)

**[⬆回到顶部](#table-of-contents)**

* * *

## 8. IIFE, Modules and Namespaces

### Articles

-   📜[Mastering Immediately-Invoked Function Expressions ― Chandra Gundamaraju](https://medium.com/@vvkchandra/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6)
-   📜[ES6模块是否过时了IIFE？](https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0)
-   📜[A 10 minute primer to JavaScript modules, module formats, module loaders and module bundlers ― Jurgen Van de Moere](https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/)
-   📜[模块―探索JS](http://exploringjs.com/es6/ch_modules.html)
-   📜 [ES模块：深入学习动画片— Lin Clark](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
-   📜[了解ES6模块-Craig Buckler](https://www.sitepoint.com/understanding-es6-modules/)
-   📜[An overview of ES6 Modules in JavaScript — Brent Graham](https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/)
-   📜[深入了解ES6模块-NicolásBevacqua](https://ponyfoo.com/articles/es6-modules-in-depth)
-   📜[ES6 modules, Node.js and the Michael Jackson Solution — Alberto Gimeno](https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b)
-   📜[JavaScript模块：新手指南-Preethi Kasireddy](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)
-   📜 [在网络上使用JavaScript模块](https://developers.google.com/web/fundamentals/primers/modules)
-   📜[JavaScript模块：从IIFE到CommonJS再到ES6模块— Tyler McGinnis](https://medium.freecodecamp.org/javascript-modules-from-iifes-to-commonjs-to-es6-modules-4d10c16f55d4)

### Videos

-   🎥[立即调用函数表达式-Beau教JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=3cbiZV4H22c)
-   🎥[了解JavaScript IIFE](https://www.youtube.com/watch?v=I5EntfMeIIQ)
-   🎥[JavaScript模块：ES6导入和导出— Kyle Robinson](https://www.youtube.com/watch?v=_3oSWwapPKQ)
-   🎥[ES6-模块-Ryan Christian](https://www.youtube.com/watch?v=aQr2bV1BPyE)
-   🎥[现实世界中的ES6模块— Sam Thorogood](https://www.youtube.com/watch?v=fIP4pjAqCtQ)
-   🎥 [ES6模块— TempleCoding](https://www.youtube.com/watch?v=5P04OK6KlXA)

**[⬆回到顶部](#table-of-contents)**

* * *

## 9.消息队列和事件循环

### 文章

-   📜 [JavaScript事件循环介绍-Anoop Raveendran](https://medium.com/front-end-hacking/javascript-event-loop-explained-4cd26af121d4)
-   📜[JavaScript事件循环：解释— Erin Sweson-Healey](https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
-   📜 [什么是Javascript中的事件循环-WP Tutor.io](https://www.wptutor.io/web/js/javascript-event-loop)
-   📜[了解JS：事件循环-亚历山大·康多夫（Alexander Kondov）](https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40)
-   📜[了解JavaScript事件循环-Ashish Gupta](https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop)
-   📜[Event Loop in Javascript — Manjula Dube](https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49)
-   📜[JavaScript事件循环-Flavio Copes](https://flaviocopes.com/javascript-event-loop/)
-   📜 [JavaScript的工作原理：事件循环-Alexander Zlatkov](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
-   📜[任务，微任务，队列和时间表—杰克·阿奇博尔德](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
-   📜 [用比萨餐厅类比可视化JavaScript事件循环— Priyansh Jain](https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8)

### Videos

-   🎥[无论如何，事件循环到底是什么？ | JSConf欧盟-Philip Roberts](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
-   🎥[JavaScript事件循环-简化ComScience](https://www.youtube.com/watch?v=XzXIMZMN9k4)
-   🎥[我陷入了事件循环—菲利普·罗伯茨（Philip Roberts）](https://www.youtube.com/watch?v=6MXRNXXgP_0)
-   🎥[In The Loop - Jake Archibald | JSConf.Asia 2018](https://www.youtube.com/watch?v=cCOL7MC4Pl0)
-   🎥[Desmitificando el事件循环（西班牙语）](https://www.youtube.com/watch?v=Eqq2Rb7LzYE)

**[⬆回到顶部](#table-of-contents)**

* * *

## 10. setTimeout，setInterval和requestAnimationFrame

### 文章

-   📜[setTimeout and setInterval — JavaScript.Info](https://javascript.info/settimeout-setinterval)
-   📜[为什么不使用setInterval — Akanksha Sharma](https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9)
-   📜 [setTimeout VS setInterval — Develoger](https://develoger.com/settimeout-vs-setinterval-cff85142555b)
-   📜[使用requestAnimationFrame —克里斯·科耶尔](https://css-tricks.com/using-requestanimationframe/)
-   📜 [了解JavaScript的requestAnimationFrame（）-JavaScript套件](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml)
-   📜[Handling time intervals in JavaScript - Amit Merchant](https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/)

### 影片

-   🎥[Javascript：setTimeout和setInterval的工作原理-Coding Blocks India](https://www.youtube.com/watch?v=6bPKyl8WYWI)
-   🎥 [JavaScript中的setTimeout和setInterval — Techsith](https://www.youtube.com/watch?v=TbCgGWe8LN8)
-   🎥[JavaScript计时器-Steve Griffith](https://www.youtube.com/watch?v=0VVJSvlUgtg)
-   🎥[JavaScript setTimeOut和setInterval的解释— Theodore Anderson](https://www.youtube.com/watch?v=mVKfrWCOB60)

**[⬆回到顶部](#table-of-contents)**

* * *

## 11. JavaScript引擎

### 文章

-   📜[JavaScript引擎— Jen Looper](http://www.softwaremag.com/javascript-engines/)
-   📜[Understanding How the Chrome V8 Engine Translates JavaScript into Machine Code — DroidHead](https://medium.freecodecamp.org/understanding-the-core-of-nodejs-the-powerful-chrome-v8-engine-79e7eb8af964)
-   📜 [了解V8的字节码— Franziska Hinkelmann](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
-   📜[Google V8 Javascript引擎简史-Clair Smith](https://www.mediacurrent.com/blog/brief-history-googles-v8-javascript-engine/)
-   📜[JavaScript要点：为什么您应该知道引擎的工作原理-Rainer Hahnekamp](https://medium.freecodecamp.org/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553)
-   📜[JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
-   📜[JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes)
-   📜[V8如何优化阵列操作](https://v8.dev/blog/elements-kinds)

### 影片

-   🎥[JavaScript引擎：The Good Parts™— Mathias Bynens和Benedikt Meurer](https://www.youtube.com/watch?v=5nmpokoRaZI)

**[⬆回到顶部](#table-of-contents)**

* * *

## 12.按位运算符，类型数组和数组缓冲区

### 文章

-   📜[使用JS进行编程：按位操作— Alexander Kondov](https://hackernoon.com/programming-with-js-bitwise-operations-393eb0745dc4)

-   📜 [在现实生活中使用JavaScript的按位运算符-ian m](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)

-   📜[JavaScript按位运算符— w3resource](https://www.w3resource.com/javascript/operators/bitwise-operator.php)

-   📜 [Javascript中的按位运算符— Joe Cha](https://medium.com/bother7-blog/bitwise-operators-in-javascript-65c4c69be0d3)

-   📜 [关于Java中二进制计算和按位运算符的全面入门-Paul Brown](https://medium.com/techtrument/a-comprehensive-primer-on-binary-computation-and-bitwise-operators-in-javascript-81acf8341f04)

-   📜[如何理解JavaScript中的按位操作？](https://www.quora.com/How-can-I-understand-Bitwise-operation-in-JavaScript)

    ### 影片

-   🎥[JavaScript按位运算符—使用Mosh编程](https://www.youtube.com/watch?v=mesu75PTDC8)

**[⬆回到顶部](#table-of-contents)**

* * *

## 13. DOM and Layout Trees

### 文章

-   📜[如何在JavaScript中理解和修改DOM — Tania Rascia](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)

-   📜[什么是文档对象模型，以及为什么应该知道如何使用它— Leonardo Maldonado](https://medium.freecodecamp.org/whats-the-document-object-model-and-why-you-should-know-how-to-use-it-1a2d0bc5429d)

-   📜[JavaScript DOM范例教程— Guru99](https://www.guru99.com/how-to-use-dom-and-events-in-javascript.html)

-   📜[What is the DOM? — Chris Coyier](https://css-tricks.com/dom/)

-   📜 [使用JavaScript遍历DOM — Zell Liew](https://zellwk.com/blog/dom-traversals/)

-   📜[出色的JavaScript \[书\]-文档对象模型](https://eloquentjavascript.net/14_dom.html)

-   📜[DOM树](https://javascript.info/dom-nodes)

-   📜[如何遍历Java语言中的DOM-VojislavGrujić](https://medium.com/javascript-in-plain-english/how-to-traverse-the-dom-in-javascript-d6555c335b4e)

-   📜[渲染树构建— Ilya Grigorik](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)

-   📜[What exactly is the DOM?](https://bitsofco.de/what-exactly-is-the-dom/)

-   📜[精通DOM的Vanilla JS指南— Brian Pak](https://dev.to/bouhm/a-vanilla-js-guide-on-mastering-the-dom-3l9b)

    ### 影片

-   🎥[JavaScript DOM — The Net Ninja](https://www.youtube.com/watch?v=FIORjGvT0kk)

-   🎥[JavaScript DOM崩溃课程—遍历媒体](https://www.youtube.com/watch?v=0ik6X4DJKCc)

**[⬆回到顶部](#table-of-contents)**

* * *

## 14.工厂和阶级

### 文章

-   📜[如何在JavaScript中使用类-Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-classes-in-javascript)

-   📜[Javascript类-深入了解-Majid](https://medium.com/tech-tajawal/javascript-classes-under-the-hood-6b26d2667677)

-   📜[ES6课程—纳撒尼尔·福斯特（Nathaniel Foster）](https://www.javascriptjanuary.com/blog/es6-classes)

-   📜 [使用ES6，Pt更好的JavaScript。 II：深入学习班级– Peleke Sengstacke](https://scotch.io/tutorials/better-javascript-with-es6-pt-ii-a-deep-dive-into-classes)

-   📜[了解普通JavaScript中的工厂设计模式— Aditya Agarwal](https://medium.com/front-end-hacking/understand-the-factory-design-pattern-in-plain-javascript-20b348c832bd)

-   📜[JavaScript中的工厂函数— Josh Miller](https://atendesigngroup.com/blog/factory-functions-javascript)

-   📜[JS ES6中的工厂模式— SnstsDev](https://medium.com/@SntsDev/the-factory-pattern-in-js-es6-78f0afad17e9)

-   📜 [班级与工厂职能：探索未来之路— Cristi Salcescu](https://medium.freecodecamp.org/class-vs-factory-function-exploring-the-way-forward-73258b6a8d15)

-   📜[ES6类如何真正发挥作用以及如何构建自己的类-Robert Grosse](https://medium.com/@robertgrosse/how-es6-classes-really-work-and-how-to-build-your-own-fd6085eb326a)

-   📜[理解`super`在JavaScript中](https://jordankasper.com/understanding-super-in-javascript)

-   📜 [理解JavaScript中的类的简单指南](https://dev.to/lawrence_eagles/an-easy-guide-to-understanding-classes-in-javascript-3bcm)

    ### 影片

-   🎥[JavaScript Factory函数-使用Mosh编程](https://www.youtube.com/watch?v=jpegXpQpb3o)

-   🎥 [JavaScript中的工厂函数-Fun Fun函数](https://www.youtube.com/watch?v=ImwrezYhw4w)

-   🎥[Javascript教程功能工厂— Crypto Chan](https://www.youtube.com/watch?v=R7-IwpH80UE)

**[⬆回到顶部](#table-of-contents)**

* * *

## 15.这个，打电话，申请并绑定

### 文章

-   📜[在JavaScript中搜寻call（），apply（）和bind（）方法-Aniket Kudale](https://levelup.gitconnected.com/grokking-call-apply-and-bind-methods-in-javascript-392351a4be8b)

-   📜[How-to: call() , apply() and bind() in JavaScript — Niladri Sekhar Dutta](https://www.codementor.io/niladrisekhardutta/how-to-call-apply-and-bind-in-javascript-8i1jca6jp)

-   📜[JavaScript的Apply，Call和Bind方法对于JavaScript专业人员至关重要-Richard Bovell](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)

-   📜[WTF is this - Understanding the this keyword, call, apply, and bind in JavaScript — Tyler McGinnis](https://tylermcginnis.com/this-keyword-call-apply-bind-javascript/)

-   📜 [Javascript：call（），apply（）和bind（）— Omer Goldberg](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)

-   📜[The difference between call / apply / bind — Ivan Sifrim](https://medium.com/@ivansifrim/the-differences-between-call-apply-bind-276724bb825b)

-   📜[hack被称为，应用，绑定到JavaScript中的东西– Ritik](https://dev.to/ritik_dev_js/what-the-hack-is-call-apply-bind-in-javascript-11ce)

-   📜 [掌握JavaScript中的“ this”：回调和bind（），apply（），call（）— Michelle Gienow](https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/)

-   📜[JavaScript的应用，调用和绑定通过举办一次野餐来解释-Kevin Kononenko](https://dev.to/kbk0125/javascripts-apply-call-and-bind-explained-by-hosting-a-cookout-32jo)

-   📜[How AND When to use bind, call, and apply in Javascript — Eigen X](https://www.eigenx.com/blog/https/mediumcom/eigen-x/how-and-when-to-use-bind-call-and-apply-in-javascript-77b6f42898fb)

-   📜[JavaScript .bind（）与.apply（）和.call（）-Hack Sparrow](https://www.hacksparrow.com/javascript-bind-vs-apply-and-call.html)

-   📜 [call（）— MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)

-   📜[bind（）— MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)

-   📜[apply（）— MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)

-   📜[JavaScript中的“ this”是什么？ -李彦宏](http://blog.brew.com.hk/what-is-this-in-javascript/)

-   📜[我来给你解释一下`this`. (JavaScript) — Jason Y U](https://dev.to/ycmjason/let-me-explain-to-you-what-is-this-javascript-44ja)

-   📜[了解JavaScript中的“ this”关键字-Pavan](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)

-   📜 [如何在JavaScript中理解关键字this和context-LukasGisder-Dubé](https://medium.freecodecamp.org/how-to-understand-the-keyword-this-and-context-in-javascript-cd624c6b74b8)

-   📜[JavaScript到底是什么？ —赫里达耶斯·夏尔马](https://dev.to/_hridaysharma/what-the-heck-is-this-in-javascript-37n1)

-   📜[这与Java语言绑定— Brian Barbour](https://dev.to/steelvoltage/this-and-bind-in-javascript-2pam)

-   📜[3种在JavaScript中使用“ This”保持理智的技术-Carl](https://dev.to/canderson93/3-techniques-for-maintaining-your-sanity-using-this-in-javascript-3idf)

-   📜[掌握JavaScript“ this”关键字-Aakash Srivastav](https://dev.to/aakashsr/mastering-the-javascript-this-keyword-4pfa)

-   📜[JavaScript中的此绑定–4。新绑定– Spyros Argalias](https://dev.to/sargalias/this-binding-in-javascript-4-new-binding-2p1n)

    ### 影片

-   🎥 [JavaScript调用，应用和绑定— techsith](https://www.youtube.com/watch?v=c0mLRpw-9rI)

-   🎥[JavaScript的Call，Apply和Bind函数的实际应用-techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)

-   🎥 [JavaScript（调用，绑定，应用）—好奇的原子力](https://www.youtube.com/watch?v=Uy0NOXLBraE)

-   🎥[了解ES2017世界中的功能和“ this” — Bryan Hughes](https://www.youtube.com/watch?v=AOSYY1_np_4)

-   🎥[绑定和此-JavaScript中的对象创建-FunFunFunction](https://www.youtube.com/watch?v=GhbhD1HR5vk)

-   🎥 [JS Function Methods call(), apply(), and bind() — Steve Griffith](https://www.youtube.com/watch?v=uBdH0iB1VDM)

**[⬆回到顶部](#table-of-contents)**

* * *

## 16. new，Constructor，instanceof和Instances

### Articles

-   📜[JavaScript For Beginners: the ‘new’ operator — Brandon Morelli](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
-   📜 [让我们揭开JavaScript的“ new”关键字的神秘面纱-Cynthia Lee](https://medium.freecodecamp.org/demystifying-javascripts-new-keyword-874df126184c)
-   📜 [构造函数，运算符“新” — JavaScript.Info](https://javascript.info/constructor-new)
-   📜[了解JavaScript构造函数— Faraz Kelhini](https://css-tricks.com/understanding-javascript-constructors/)
-   📜[使用构造函数-Openclassrooms](https://openclassrooms.com/en/courses/3523231-learn-to-code-with-javascript/4379006-use-constructor-functions)
-   📜[超越`typeof`和`instanceof`：简化动态类型检查— Axel Rauschmayer博士](http://2ality.com/2017/08/type-right.html)
-   📜[What Is the Instanceof Operator in JavaScript — appendTo](https://appendto.com/2016/10/what-is-the-instanceof-operator-in-javascript/)
-   📜[功能和对象，彼此之间的实例— Kiro Risk](https://javascriptrefined.io/function-and-object-instances-of-each-other-1e1095d5faac)

**[⬆回到顶部](#table-of-contents)**

* * *

## 17.原型继承和原型链

### Articles

-   📜[Javascript：原型与类— Valentin PARSY](https://medium.com/@parsyval/javascript-prototype-vs-class-a7015d5473b)

-   📜[JavaScript engine fundamentals: optimizing prototypes — Mathias Bynens](https://mathiasbynens.be/notes/prototypes)

-   📜 [JavaScript Prototype — NC Patro](https://codeburst.io/javascript-prototype-cb29d82b8809)

-   📜 [Javascript中的原型— Sandeep Ranjan](https://www.codementor.io/sandeepranjan2007/prototype-in-javascipt-knbve0lqo)

-   📜[JavaScript中的原型— Rupesh Mishra](https://hackernoon.com/prototypes-in-javascript-5bba2990e04b)

-   📜[JavaScript中的原型：古怪，但这是它的工作原理-Pranav Jindal](https://medium.freecodecamp.org/prototype-in-js-busted-5547ec68872)

-   📜 [Inheritance and the prototype chain — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

-   📜[理解JavaScript：原型和继承-Alexander Kondov](https://hackernoon.com/understanding-javascript-prototype-and-inheritance-d55a9a23bde2)

-   📜[在JavaScript中理解类（ES5）和原型继承— Hridayesh Sharma](https://dev.to/_hridaysharma/understanding-classes-es5-and-prototypal-inheritance-in-javascript-n8d)

-   📜 [prototype, **因此**和JavaScript中的原型继承— Varun Dey](https://dev.to/varundey/prototype-proto-and-prototypal-inheritance-in-javascript-2inl)

-   📜 [原型继承— JavaScript.Info](https://javascript.info/prototype-inheritance)

-   📜 [如何在JavaScript中使用原型和继承— Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)

-   📜[精通JavaScript原型和继承— Arnav Aggarwal](https://codeburst.io/master-javascript-prototypes-inheritance-d0a9a5a75c4e)

-   📜[You Don't Know JS: this & Object Prototypes, 1st Edition \[Book\] — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/1st-ed/this%20%26%20object%20prototypes)

-   📜[CSS解释JavaScript的原型继承-Nash Vail](https://medium.freecodecamp.org/understanding-prototypal-inheritance-in-javascript-with-css-93b2fcda75e4)

-   📜[JavaScript的原型继承— Jannis Redmann](https://gist.github.com/derhuerst/a585c4916b1c361cc6f0)

-   📜 [JavaScript中的经典和原型继承— Danny Cornelisse](http://www.competa.com/blog/classical-prototypical-inheritance-javascript/)

-   📜[揭开ES6类的神秘面纱和原型继承-Neo Ighodaro](https://scotch.io/tutorials/demystifying-es6-classes-and-prototypal-inheritance)

-   📜[Intro To Prototypal Inheritance — Dharani Jayakanthan](https://dev.to/danny/intro-to-prototypal-inheritance---js-9di)

-   📜[Classes in JavaScript - Explained — Daniel Li](http://blog.brew.com.hk/classes-in-javascript-explained/)

-   📜[让我们用JS构建原型继承-var-che](https://dev.to/varche/let-s-build-prototypal-inheritance-in-js-56mm)

-   📜[JavaScript中的对象，原型和类— Atta](https://dev.to/attacomsian/objects-prototypes-and-classes-in-javascript-3i9b)

-   📜[JavaScript原型继承和对象创建— Nick Shoup](https://dev.to/shoupn/javascript-prototypes-and-object-creation-2onh)

-   📜[JavaScript原型的神奇世界—Belén](https://dev.to/ladybenko/the-magical-world-of-javascript-prototypes-1mhg)

-   📜[了解JavaScript中的原型继承-Lawrence Eagles](https://dev.to/lawrence_eagles/understanding-prototypal-inheritance-in-javascript-4f31#chp-4)

    ### Videos

-   🎥 [Javascript原型继承— Avelx](https://www.youtube.com/watch?v=sOrtAjyk4lQ)

-   🎥[JavaScript原型继承说明。我-techsith](https://www.youtube.com/watch?v=7oNWNlMrkpc)

-   🎥[JavaScript Prototype Inheritance Explained pt. II — techsith](https://www.youtube.com/watch?v=uIlj6_z_wL8)

-   🎥[JavaScript原型继承说明-Kyle Robinson](https://www.youtube.com/watch?v=qMO-LTOrJaE)

-   🎥[高级Javascript-1分钟内完成原型继承](https://www.youtube.com/watch?v=G6l5CHl67HQ)

-   🎥[经典Javascript类和原型继承概述— Pentacode](https://www.youtube.com/watch?v=phwzuiJJPpQ)

-   🎥[Object Oriented JavaScript - Prototype — The Net Ninja](https://www.youtube.com/watch?v=4jb4AYEyhRc)

-   🎥[JavaScript原型— kudvenkat](https://www.youtube.com/watch?v=2rkEbcptR64)

-   🎥 [使用原型的JavaScript — O'Reilly](https://www.youtube.com/watch?v=oCwCcNvaXAQ)

-   🎥 [Javascript原型初学者指南-Tyler Mcginnis](https://www.youtube.com/watch?v=XskMWBXNbp0)

-   🎥[Prototypes in Javascript - p5.js Tutorial — The Coding Train](https://www.youtube.com/watch?v=hS_WqkyUah8)

**[⬆ Back to Top](#table-of-contents)**

* * *

## 18. Object.create和Object.assign

### Articles

-   📜 [Object.create（）— MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)

-   📜[JavaScript中的Object.create — Rupesh Mishra](https://hackernoon.com/object-create-in-javascript-fa8674df6ed2)

-   📜 [Object.create（）：使用JavaScript创建对象的新方法— Rob Gravelle](https://www.htmlgoodies.com/beyond/javascript/object.create-the-new-way-to-create-objects-in-javascript.html)

-   📜 [Object.create的基本继承— Joshua Clanton](http://adripofjavascript.com/blog/drips/basic-inheritance-with-object-create.html)

-   📜[JavaScript中的Object.create（）— GeeksforGeeks](https://www.geeksforgeeks.org/object-create-javascript/)

-   📜[了解Object.create（）和新运算符—乔纳森·沃克斯兰德之间的区别](https://medium.com/@jonathanvox01/understanding-the-difference-between-object-create-and-the-new-operator-b2a2f4749358)

-   📜 [JavaScript对象创建：模式和最佳实践— Jeff Mott](https://www.sitepoint.com/javascript-object-creation-patterns-best-practises/)

-   📜[使用Object.assign，Object.keys和hasOwnProperty处理JavaScript中的对象](https://alligator.io/js/dealing-with-objects/)

-   📜[用JavaScript复制对象― Orinami Olatunji](https://scotch.io/bar-talk/copying-objects-in-javascript)

-   📜[Object.assign（）— MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)

-   📜[JavaScript：Object.assign（）-Thiago S. Adriano](https://codeburst.io/javascript-object-assign-bc9696dcbb6e)

-   📜[如何深度克隆JavaScript对象— Flavio Copes](https://flaviocopes.com/how-to-clone-javascript-object/)

-   📜[面向初学者的JavaScript中的对象分配与原始分配— Nick Scialli](https://dev.to/nas5w/object-assignment-vs-primitive-assignment-in-javascript-for-beginners-2moi)

    ### Videos

-   🎥[Object.assign（）的解释—亚伦编写代码](https://www.youtube.com/watch?v=aw7NfYhR5rc)

-   🎥[Object.assign（）方法— techsith](https://www.youtube.com/watch?v=9Ky4X6inpi4)

**[⬆回到顶部](#table-of-contents)**

* * *

## 19. map, reduce, filter

### 文章

-   📜 [JavaScript Functional Programming — map, filter and reduce — Bojan Gvozderac](https://medium.com/jsguru/javascript-functional-programming-map-filter-and-reduce-846ff9ba492d)

-   📜[使用Java学习地图，过滤和归约—JoãoMiguel Cunha](https://medium.com/@joomiguelcunha/learn-map-filter-and-reduce-in-javascript-ea59009593c4)

-   📜[JavaScript映射，缩减和过滤— Dan Martensen](https://danmartensen.svbtle.com/javascripts-map-reduce-and-filter)

-   📜[How to Use Map, Filter, & Reduce in JavaScript — Peleke Sengstacke](https://code.tutsplus.com/tutorials/how-to-use-map-filter-reduce-in-javascript--cms-26209)

-   📜[JavaScript —学习链接映射，过滤和缩减— Brandon Morelli](https://codeburst.io/javascript-learn-to-chain-map-filter-and-reduce-acd2d0562cd4)

-   📜 [具有map，reduce，filter和ES6的Javascript数据结构— Deepak Gupta](https://codeburst.io/write-beautiful-javascript-with-%CE%BB-fp-es6-350cd64ab5bf)

-   📜[理解Java中的映射，过滤和归约— Luuk Gruijs](https://hackernoon.com/understanding-map-filter-and-reduce-in-javascript-5df1c7eee464)

-   📜[JS中的函数式编程：映射，过滤器，归约（第5部分）— Omer Goldberg](https://hackernoon.com/functional-programming-in-js-map-filter-reduce-pt-5-308a205fdd5f)

-   📜 [JavaScript：地图，过滤器，缩小— William S. Vincent](https://wsvincent.com/functional-javascript-map-filter-reduce/)

-   📜[箭头函数：JavaScript中的简洁语法— Kyle Pennell](https://www.sitepoint.com/es6-arrow-functions-new-fat-concise-syntax-javascript/)

-   📜[JavaScript：初学者的箭头功能—布兰登·莫雷利](https://codeburst.io/javascript-arrow-functions-for-beginners-926947fc0cdc)

-   📜[什么时候（为什么）应该使用ES6箭头功能-什么时候不应该使用-Cynthia Lee](https://medium.freecodecamp.org/when-and-why-you-should-use-es6-arrow-functions-and-when-you-shouldnt-3d851d7f0b26)

-   📜[JavaScript —学习和理解箭头功能— Brandon Morelli](https://codeburst.io/javascript-learn-understand-arrow-functions-fe2083533946)

-   📜[（JavaScript）=>箭头函数-sigu](https://medium.com/podiihq/javascript-arrow-functions-27d4c3334b83)

-   📜[Javascript.reduce（）—保罗·安德森](https://medium.com/@panderson.dev/javascript-reduce-79aab078da23)

-   📜[为什么要用JavaScript中的地图和过滤器替换forEach — Roope Hakulinen](https://gofore.com/en/why-you-should-replace-foreach/)

-   📜[简化您的JavaScript –使用.map（）、. reduce（）和.filter（）-Etienne Talbot](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d)

-   📜[JavaScript’s Reduce Method Explained By Going On a Diet — Kevin Kononenko](https://blog.codeanalogies.com/2018/07/24/javascripts-reduce-method-explained-by-going-on-a-diet/)

-   📜[JavaScript中的映射，过滤和归约之间的区别— Amirata Khodaparast](https://medium.com/@amiratak88/difference-between-map-filter-and-reduce-in-javascript-822ff79d5160)

-   📜[Map⇄Filter⇄Reduce↻-ashay mandwarya](https://hackernoon.com/map-filter-reduce-ebbed4be4201)

-   📜[.map（）寻找方法—布兰登·沃兹涅维奇](https://medium.freecodecamp.org/finding-your-way-with-map-aecb8ca038f6)

-   📜[如何使用JavaScript编写自己的地图，过滤和归约函数— Hemand Nair](https://medium.freecodecamp.org/how-to-write-your-own-map-filter-and-reduce-functions-in-javascript-ab1e35679d26)

-   📜[如何在JavaScript中操作数组— Bolaji Ayodeji](https://www.freecodecamp.org/news/manipulating-arrays-in-javascript/)

-   📜[如何使用JavaScript中的map（），reduce（）和filter（）简化代码库— Alex Permyakov](https://itnext.io/15-useful-javascript-examples-of-map-reduce-and-filter-74cbbb5e0a1f)

-   📜[.map（）、. filter（）和.reduce（）— Andy Pickle](https://dev.to/pickleat/map-filter-and-reduce-2efb)

-   📜[映射/过滤/减少崩溃课程—克里斯·阿卡德](https://dev.to/chrisachard/map-filter-reduce-crash-course-5gan)

-   📜[映射，过滤和缩小–动画— JavaScript老师](https://medium.com/@js_tut/map-filter-and-reduce-animated-7fe391a35a47)

-   📜[映射，过滤，化简和其他要成为算法向导所必须知道的数组迭代器— Mauro Bono](https://dev.to/uptheirons78/map-filter-reduce-and-others-arrays-iterators-you-must-know-to-become-an-algorithms-wizard-4209)

-   📜[如何使用JavaScript .map，.filter和.reduce — Avery Duffin](https://medium.com/better-programming/how-to-javascripts-map-vs-filter-vs-reduce-80d87a5a0a24)

-   📜[Javascript性能测试-每个vs的vs（映射，缩小，过滤，查找）— Deepak Gupta](https://towardsdatascience.com/javascript-performance-test-for-vs-for-each-vs-map-reduce-filter-find-32c1113f19d7)

-   📜[正确使用.map（）、. filter（）和.reduce（）-Sasanka Kudagoda](https://medium.com/javascript-in-plain-english/using-map-filter-and-reduce-properly-50e07f80c8b2)

-   📜[掌握JavaScript Reduce方法✂️— sanderdebr](https://dev.to/sanderdebr/mastering-the-javascript-reduce-method-2foj)

    ### 影片

-   🎥[Map, Filter and Reduce — Lydia Hallie](https://www.youtube.com/watch?v=UXiYii0Y7Nw)

-   🎥 [功能性JavaScript：Map，forEach，Reduce，Filter — Theodore Anderson](https://www.youtube.com/watch?v=vytzLlY_wmU)

-   🎥[JavaScript数组超能力：地图，过滤器，缩小（第一部分）— Michael Rosata](https://www.youtube.com/watch?v=qTeeVd8hOFY)

-   🎥[JavaScript数组超能力：地图，过滤器，缩小（第2部分）— Michael Rosata](https://www.youtube.com/watch?v=gIm9xLYudL0)

-   🎥 [JavaScript高阶函数-过滤，映射，排序和归约— Epicop](https://www.youtube.com/watch?v=zYBeEPxNSbw)

-   🎥 [\[数组方法2/3\] .filter + .map + .reduce — CodeWithNick](https://www.youtube.com/watch?v=4qWlqD0yYTU)

-   🎥[Arrow functions in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=6sQDTgOqh-I)

-   🎥[使用JavaScript学习函数式编程— Anjana Vakil-JSUnconf](https://www.youtube.com/watch?v=e-5obm1G_FY&t=1521s)

-   🎥[地图-Parte 2 JavaScript-有趣功能](https://www.youtube.com/watch?v=bCqtb-Z5YGQ&t=17s)

-   🎥[减少基础知识-JavaScript中FP的第3部分-有趣功能](https://www.youtube.com/watch?v=Wl98eZpkp-c)

-   🎥 [减少高级-JavaScript中FP的第4部分-有趣功能](https://www.youtube.com/watch?v=1DMolJ2FrNY&t=621s)

-   🎥[减少数组方法JavaScript教程-Florin Pop](https://www.youtube.com/watch?v=IXp06KekEjM)

-   🎥[map数组方法| JavaScript教程-Florin Pop](https://www.youtube.com/watch?v=P4RAFdZDn3M)

**[⬆回到顶部](#table-of-contents)**

* * *

## 20. Pure Functions, Side Effects and State Mutation

### Articles

-   📜 [Javascript和函数式编程—纯函数— Omer Goldberg](https://hackernoon.com/javascript-and-functional-programming-pt-3-pure-functions-d572bb52e21c)

-   📜[掌握JavaScript面试：什么是纯函数？ —埃里克·埃利奥特（Eric Elliott）](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)

-   📜[JavaScript：什么是纯函数以及为什么要使用它们？ -詹姆斯·杰弗里（James Jeffery）](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)

-   📜[JavaScript中的纯函数— @nicoespeon](http://www.nicoespeon.com/en/2015/01/pure-functions-javascript/)

-   📜[函数式编程：纯函数— Arne Brasseur](https://www.sitepoint.com/functional-programming-pure-functions/)

-   📜[Javascript中的纯函数— Krunal](https://appdividend.com/2017/04/10/pure-functions-in-javascript/)

-   📜 [使您的JavaScript变得纯净—杰克·富兰克林](https://alistapart.com/article/making-your-javascript-pure)

-   📜[在JavaScript中进行更改或不进行更改](https://slemgrim.com/mutate-or-not-to-mutate/)

-   📜 [数组，对象和突变— FedericoKnüssel](https://medium.com/@fknussel/arrays-objects-and-mutations-6b23348b54aa)

-   📜[不变的状态-Maciej Sikora](https://medium.com/dailyjs/the-state-of-immutability-169d2cd11310)

-   📜[如何处理纯功能JavaScript中的肮脏副作用-James Sinclair](https://jrsinclair.com/articles/2018/how-to-deal-with-dirty-side-effects-in-your-pure-functional-javascript/)

-   📜[防止JavaScript产生副作用-David Walsh](https://davidwalsh.name/preventing-sideeffects-javascript)

-   📜[在JavaScript和函数组合中使用纯函数— Peleke Sengstacke](https://scotch.io/tutorials/wielding-pure-functions-in-javascript-and-function-composition)

-   📜[JavaScript：纯函数-William S. Vincent](https://wsvincent.com/javascript-pure-functions/)

-   📜 [现代JavaScript中的函数式编程范例：纯函数— Alexander Kondov](https://hackernoon.com/functional-programming-paradigms-in-modern-javascript-pure-functions-797d9abbee1)

-   📜[了解Javascript变异和纯函数-Chidume Nnamdi](https://blog.bitsrc.io/understanding-javascript-mutation-and-pure-functions-7231cc2180d3)

-   📜[类似于功能的JavaScript-Daniel Brain](https://medium.com/@bluepnume/functional-ish-javascript-205c05d0ed08)

    ### 影片

-   🎥[纯函数— Hexlet](https://www.youtube.com/watch?v=dZ41D6LDSBg)

-   🎥[Pure Functions - Functional Programming in JavaScript — Paul McBride](https://www.youtube.com/watch?v=Jh_Uzqzz_wM)

-   🎥 [JavaScript Pure Functions — Seth Alexander](https://www.youtube.com/watch?v=frT3H-eBmPc)

-   🎥[JavaScript纯与不纯函数的解释-Theodore Anderson](https://www.youtube.com/watch?v=AHbRVJzpB54)

-   🎥[纯函数-函数编程：第1部分-Fun Fun函数](https://www.youtube.com/watch?v=BMUiFMZr7vk)

**[⬆回到顶部](#table-of-contents)**

* * *

## 21. Closures

### 文章

-   📜[封包-MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

-   📜[我从不了解JavaScript闭包-Olivier De Meulder](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8)

-   📜[闭包— JavaScript.Info](https://javascript.info/closure)

-   📜 [轻松理解JavaScript闭包-Richard Bovell](http://javascriptissexy.com/understand-javascript-closures-with-ease/)

-   📜[了解JavaScript闭包-Codesmith](https://codeburst.io/understanding-javascript-closures-da6aab330302)

-   📜[Understand Closures in JavaScript — Brandon Morelli](https://codeburst.io/understand-closures-in-javascript-d07852fa51e7)

-   📜[一个简单的指南，可帮助您了解JavaScript中的闭包-Prashant Ram](https://medium.freecodecamp.org/javascript-closures-simplified-d0d23fa06ba4)

-   📜 [Understanding JavaScript Closures: A Practical Approach — Paul Upendo](https://scotch.io/tutorials/understanding-javascript-closures-a-practical-approach)

-   📜[理解JavaScript：闭包-Alexander Kondov](https://hackernoon.com/understanding-javascript-closures-4188edf5ea1b)

-   📜[How to use JavaScript closures with confidence — Léna Faure](https://hackernoon.com/how-to-use-javascript-closures-with-confidence-85cd1f841a6b)

-   📜[JavaScript闭包示例— tyler](https://howchoo.com/g/mge2mji2mtq/javascript-closures-by-example)

-   📜 [JavaScript —封闭和范围— Alex Aitken](https://codeburst.io/javascript-closures-and-scope-3784c75b9290)

-   📜[在JavaScript中发现封闭的强大功能Cristi Salcescu](https://medium.freecodecamp.org/discover-the-power-of-closures-in-javascript-5c472a7765d7)

-   📜[简化的JavaScript：闭包入门-像女孩一样的代码](https://code.likeagirl.io/simplified-javascript-getting-started-with-closures-f40f65317d00)

-   📜[JavaScript吊装，范围和封闭的终极指南—泰勒·麦金尼斯（Tyler McGinnis）](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)

-   📜[封闭-RealLifeJS](http://reallifejs.com/the-meat/getting-closure/)

-   📜[JavaScript中的闭包，咖喱和IIFE](https://dev.to/ritik_dev_js/what-the-hack-is-closure-currying-and-iife-in-javascript-32m9)

-   📜 [了解JavaScript中的闭包-Sukhjinder Arora](https://blog.bitsrc.io/a-beginners-guide-to-closures-in-javascript-97d372284dda)

-   📜[JavaScript中的闭包基本指南Parathan Thiyagalingam](https://medium.freecodecamp.org/a-basic-guide-to-closures-in-javascript-9fc8b7e3463e)

-   📜[闭幕：使用记忆法Brian Barbour](https://dev.to/steelvoltage/closures-using-memoization-3597)

-   📜[JavaScript中的闭包和词法作用域简介—Ashutosh K Singh](https://medium.com/better-programming/a-brief-introduction-to-closures-and-lexical-scoping-in-javascript-8a5866496232)

-   📜[Demystify Closures — stereobooster](https://dev.to/stereobooster/demystify-closures-5g42)

-   📜 [范围和闭包-JavaScript概念– Agney Menon](https://dev.to/boywithsilverwings/scopes-and-closures-javascript-concepts-4dfj)

-   📜[了解JavaScript中的闭包-Matt Popovich](https://dev.to/mattpopovich/understanding-closures-in-javascript-3k0d)

-   📜[whatthefuck.is·封闭-丹·阿布拉莫夫](https://whatthefuck.is/closure)

    ### 影片

-   🎥 [JavaScript的难点：封闭，作用域和执行上下文-Codesmith](https://www.youtube.com/watch?v=XTAzsODSCsM)

-   🎥[Javascript闭包— techsith](https://www.youtube.com/watch?v=71AtaJpJHw0)

-   🎥 [闭包-Fun Fun功能](https://www.youtube.com/watch?v=CQqwU2Ixu-U)

-   🎥[JavaScript中的闭包— techsith](https://www.youtube.com/watch?v=-xqJo5VRP4A)

-   🎥[JavaScript Closures 101: What is a closure? — JavaScript Tutorials](https://www.youtube.com/watch?v=yiEeiMN2Khs)

-   🎥[闭包— freeCodeCamp](https://www.youtube.com/watch?v=1JsJx1x35c0)

-   🎥[JavaScript闭包— CodeWorkr](https://www.youtube.com/watch?v=-rLrGAXK8WE)

**[⬆回到顶部](#table-of-contents)**

* * *

## 22.高阶函数

### Articles

-   📜[高阶函数—雄辩的JavaScript \[本书\]](https://eloquentjavascript.net/05_higher_order.html)

-   📜[JavaScript中的高阶函数-M. David Green](https://www.sitepoint.com/higher-order-functions-javascript/)

-   📜 [高阶函数：使用过滤器，映射和约简以获得更可维护的代码— Guido Schmitz](https://medium.freecodecamp.org/higher-order-functions-in-javascript-d9101f9cf528)

-   📜[一流和高阶函数：有效的功能JavaScript — Hugo Di Francesco](https://hackernoon.com/effective-functional-javascript-first-class-and-higher-order-functions-713fde8df50a)

-   📜[JavaScript中的高阶函数— John Hannah](https://www.lullabot.com/articles/higher-order-functions-in-javascript)

-   📜[高阶函数-Richard Bovell](http://javascriptissexy.com/tag/higher-order-functions/)

-   📜 [JavaScript中的高阶函数-Zsolt Nagy](http://www.zsoltnagy.eu/higher-order-functions-in-javascript/)

-   📜[使用JavaScript中的高阶函数的乐趣-Derick](https://derickbailey.com/2015/10/21/fun-with-higher-order-functions-in-javascript/)

-   📜[提醒您如何使用高阶函数— Pedro Filho](https://github.com/pedroapfilho/high-order-functions)

-   📜[了解JavaScript中的高阶函数-Sukhjinder Arora](https://blog.bitsrc.io/understanding-higher-order-functions-in-javascript-75461803bad)

-   📜[什么是高阶函数？ —尼克·塞西亚利（Nick Scialli）](https://dev.to/nas5w/what-is-a-higher-order-function-5gk9)

    ### 影片

-   🎥[JavaScript Higher Order Functions & Arrays — Traversy Media](https://www.youtube.com/watch?v=rRgD1yVwIvE)

-   🎥[高阶函数— Fun Fun函数](https://www.youtube.com/watch?v=BMUiFMZr7vk)

-   🎥 [Javascript中的高阶函数— Raja Yogan](https://www.youtube.com/watch?v=dTlpYnmBW9I)

-   🎥[JavaScript中的高阶迭代器-Fun Fun函数](https://www.youtube.com/watch?v=GYRMNp1SKXA)

-   🎥[JavaScript中的高阶函数—编码序列](https://www.youtube.com/watch?v=H4awPsyugS0)

-   🎥 [第1部分：回调和高阶函数简介-Codesmith](https://www.youtube.com/watch?v=7E8ctomPQJw)

-   🎥[第2部分：了解为什么我们需要高阶函数-Codesmith](https://www.youtube.com/watch?v=28MXziDZkE4)

**[⬆回到顶部](#table-of-contents)**

* * *

## 23.递归

### 文章

-   📜 [JavaScript中的递归— Kevin Ennis](https://medium.freecodecamp.org/recursion-in-javascript-1608032c7a1f)

-   📜[Understanding Recursion in JavaScript — Zak Frisch](https://medium.com/@zfrisch/understanding-recursion-in-javascript-992e96449e03)

-   📜[学习和理解JavaScript中的递归-Brandon Morelli](https://codeburst.io/learn-and-understand-recursion-in-javascript-b588218e87ea)

-   📜[函数式JavaScript中的递归— M. David Green](https://www.sitepoint.com/recursion-functional-javascript/)

-   📜[使用JS编程：递归— Alexander Kondov](https://hackernoon.com/programming-with-js-recursion-31371e2bf808)

-   📜 [JavaScript中的匿名递归— simo](https://dev.to/simov/anonymous-recursion-in-javascript)

-   📜[JS中的递归，迭代和尾调用— loverajoel](http://www.jstips.co/en/javascript/recursion-iteration-and-tail-calls-in-js/)

-   📜[自信地理解JavaScript中的递归-Jay](https://www.thecodingdelight.com/understanding-recursion-javascript/)

-   📜[Intro to Recursion — Brad Newman](https://medium.com/@newmanbradm/intro-to-recursion-984a8bd50f4b)

-   📜[Accio Recursion!: Your New Favorite JavaScript Spell — Leanne Cabey](https://medium.com/datadriveninvestor/accio-recursion-your-new-favorite-javascript-spell-7e10d3125fb3)

    ### 影片

-   🎥[Recursion In JavaScript — techsith](https://www.youtube.com/watch?v=VtG0WAUvq2w)

-   🎥 [Recursion — Fun Fun Function](https://www.youtube.com/watch?v=k7-N8R0-KY4)

-   🎥 [递归和递归函数— Hexlet](https://www.youtube.com/watch?v=vLhHyGTkjCs)

-   🎥[递归：Recursion（）— JS每月— Lucas da Costa](https://www.youtube.com/watch?v=kGXVsd8pBLw)

-   🎥[JavaScript中的递归函数— kudvenkat](https://www.youtube.com/watch?v=uyjsR9eNTIw)

-   🎥 [递归到底是什么？ — Computerphile](https://www.youtube.com/watch?v=Mv9NEXX1VHc)

-   🎥[Javascript教程34：递归简介-Codedamn](https://www.youtube.com/watch?v=9NO5dXSlbv8)

-   🎥 [递归，迭代和JavaScript：爱情故事| JSHeroes 2018 — Anjana Vakil](https://www.youtube.com/watch?v=FmiQr4nfoPQ)

**[⬆回到顶部](#table-of-contents)**

* * *

## 24.集合与生成器

### 文章

-   📜[ES6 In Depth: Collections — Jason Orendorff](https://hacks.mozilla.org/2015/06/es6-in-depth-collections/)
-   📜 [ES6 Collections: Using Map, Set, WeakMap, WeakSet — Kyle Pennell](https://www.sitepoint.com/es6-collections-map-set-weakmap-weakset/)
-   📜 [ES6 WeakMaps, Sets, and WeakSets in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-weakmaps-sets-and-weaksets-in-depth)
-   📜[JavaScript中的集合简介— Alligator.io](https://alligator.io/js/sets-introduction/)
-   📜[JavaScript中的地图简介— Alligator.io](https://alligator.io/js/maps-introduction/)
-   📜 [Map，Set，WeakMap和WeakSet — JavaScript.Info](https://javascript.info/map-set-weakmap-weakset)
-   📜[ES6中的地图-快速指南— Ben Mildren](https://dev.to/mildrenben/maps-in-es6---a-quick-guide-35pk)
-   📜[ES6 —设置与阵列—什么时候？ —玛雅·沙文（Maya Shavin）](https://medium.com/front-end-hacking/es6-set-vs-array-what-and-when-efc055655e1a)
-   📜[ES6 —地图与对象—什么时候？ —玛雅·沙文（Maya Shavin）](https://medium.com/front-end-hacking/es6-map-vs-object-what-and-when-b80621932373)
-   📜[ES6：使用JavaScript处理集合-无效代码上升](http://www.deadcoderising.com/es6-working-with-sets-in-javascript/)
-   📜 [数组VS集合VS映射VS对象-Javascript（ES6 / ES7）中的实时用例-Rajesh Babu](https://codeburst.io/array-vs-set-vs-map-vs-object-real-time-use-cases-in-javascript-es6-47ee3295329b)
-   📜[如何使用Sets在JavaScript中创建唯一值数组-Claire Parker-Jones](https://dev.to/claireparker/how-to-create-an-array-of-unique-values-in-javascript-using-sets-5dg6)
-   📜 [您应该了解的ES6地图-Just Chris](https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e)
-   📜[深度ES6地图-NicolásBevacqua](https://ponyfoo.com/articles/es6-maps-in-depth)
-   📜 [生成器— MDN Web文档](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
-   📜[什么是JavaScript生成器以及如何使用它们-Vladislav Stepanov](https://codeburst.io/what-are-javascript-generators-and-how-to-use-them-c6f2713fd12e)
-   📜[通过示例了解JavaScript生成器— Arfat Salman](https://codeburst.io/understanding-generators-in-es6-javascript-with-examples-6728834016d5)
-   📜[ES6生成器的基础知识— Kyle Simpson](https://davidwalsh.name/es6-generators)
-   📜[这是您想了解的有关ES2015 +生成器的所有信息— Lucas Chen](https://dev.to/parkroolucas/here-s-everything-you-d-want-to-know-about-es2015-generators-13an)
-   📜 [JavaScript生成器简介— Alice Kallaugher](https://dev.to/kallaugher/an-introduction-to-javascript-generators-1224)

### 影片

-   🎥[JavaScript ES6 / ES2015 Set, Map, WeakSet and WeakMap — Traversy Media](https://www.youtube.com/watch?v=ycohYSx5h9w)
-   🎥[ES6映射和集合之间的差异— Steve Griffith](https://www.youtube.com/watch?v=m4abICrldQI)
-   🎥[Javascript生成器-它们会改变一切-ES6生成器和声生成器— LearnCode.academy](https://www.youtube.com/watch?v=QO07THdLWQo)

**[⬆ Back to Top](#table-of-contents)**

* * *

## 25.承诺

### 文章

-   📜[承诺-MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
-   📜 [针对假人的JavaScript承诺-Jecelyn Yeen](https://scotch.io/tutorials/javascript-promises-for-dummies)
-   📜 [了解JavaScript中的承诺— Gokul N K](https://hackernoon.com/understanding-promises-in-javascript-13d99df067c1)
-   📜[掌握JavaScript面试：什么是诺言？ —埃里克·埃利奥特（Eric Elliott）](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
-   📜[JavaScript承诺概述-Sandeep Panda](https://www.sitepoint.com/overview-javascript-promises/)
-   📜[如何在JavaScript中使用Promises — Prashant Ram](https://medium.freecodecamp.org/promises-in-javascript-explained-277b98850de)
-   📜[Implementing Promises In JavaScript — Maciej Cieslar](https://medium.freecodecamp.org/how-to-implement-promises-in-javascript-1ce2680a7f51)
-   📜[JavaScript：用简单的现实类比来解释承诺-Shruti Kapoor](https://codeburst.io/javascript-promises-explained-with-simple-real-life-analogies-dd6908092138)
-   📜[Promises for Asynchronous Programming — Exploring JS](http://exploringjs.com/es6/ch_promises.html)
-   📜[在赌场赌博解释了JavaScript的承诺-Kevin Kononenko](https://blog.codeanalogies.com/2018/08/26/javascript-promises-explained-by-gambling-at-a-casino/)
-   📜[ES6的承诺：模式与反模式— Bobby Brennan](https://medium.com/datafire-io/es6-promises-patterns-and-anti-patterns-bbb21a5d0918)
-   📜[A Simple Guide to ES6 Promises — Brandon Morelli](https://codeburst.io/a-simple-guide-to-es6-promises-d71bacd2e13a)
-   📜[ES6的诺言– Manoj Singh Negi](https://codeburst.io/the-es6-promises-87a979ab27e4)
-   📜 [ES6深度承诺—NicolásBevacqua](https://ponyfoo.com/articles/es6-promises-in-depth)
-   📜[Playing with Javascript Promises: A Comprehensive Approach — Rajesh Babu](https://codeburst.io/playing-with-javascript-promises-a-comprehensive-approach-25ab752c78c3)
-   📜 [How to Write a JavaScript Promise — Brandon Wozniewicz](https://medium.freecodecamp.org/how-to-write-a-javascript-promise-4ed8d44292b8)
-   📜 [A Coding Writer’s Guide: An Introduction To ES6 Promises — Andrew Ly](https://medium.com/@andrewly07/a-coding-writers-guide-an-introduction-to-es6-promises-9ff9f9e88f6c)
-   📜[异步JavaScript |回调|封闭|承诺—全栈极客](https://dev.to/full_stackgeek/asynchronous-javascript-callbacks-closures-promises-353h)
-   📜[了解JavaScript中的承诺—克里斯·诺林](https://dev.to/itnext/reverse-engineering-understand-promises-1jfc)
-   📜[Converting callbacks to promises — Zell Liew](https://dev.to/zellwk/converting-callbacks-to-promises-nhn)
-   📜[JavaScript的承诺：英雄零备忘单-约书亚·桑德斯（Joshua Saunders）](https://medium.com/dailyjs/javascript-promises-zero-to-hero-plus-cheat-sheet-64d75051cffa)
-   📜[Promises - JavaScript concepts — Agney Menon](https://dev.to/boywithsilverwings/promises-javascript-concepts-293c)
-   📜[Java脚本`Promise`101-伊戈尔·伊里安托（Igor Irianto）](https://dev.to/iggredible/javascript-promise-101-3idl)
-   📜 [Simplify JavaScript Promises — Sunny Singh](https://dev.to/sunnysingh/simplify-javascript-promises-4djb)
-   📜[承诺的低谷— Aphinya Dechalert](https://medium.com/better-programming/the-low-down-on-promises-af4a96bbb95f)
-   📜[可视化的JavaScript：承诺和异步/等待-莉迪亚·哈莉（Lydia Hallie）](https://dev.to/lydiahallie/javascript-visualized-promises-async-await-5gke)

### 影片

-   🎥[让我们学习ES6-承诺-Ryan Christiani](https://www.youtube.com/watch?v=vQ3MoXnKfuQ)
-   🎥[JavaScript ES6 / ES2015承诺—遍历媒体](https://www.youtube.com/watch?v=XJEHuBZQ5dU)
-   🎥[承诺-娱乐功能](https://www.youtube.com/watch?v=2d7s3spWAzo)
-   🎥[JavaScript中的错误处理承诺-Fun Fun函数](https://www.youtube.com/watch?v=f8IgdnYIwOU)
-   🎥[承诺的第1部分-JavaScript / ES6的主题-编码火车](https://www.youtube.com/watch?v=QO4NXhWo_NM)

**[⬆回到顶部](#table-of-contents)**

* * *

## 26.异步/等待

### 文章

-   📜 [异步/等待-JavaScript.Info](https://javascript.info/async-await)

-   📜[了解Javascript中的异步/等待-Gokul N K](https://hackernoon.com/understanding-async-await-in-javascript-1d81bb079b2c)

-   📜 [异步编程-出色的JavaScript](https://eloquentjavascript.net/11_async.html)

-   📜[探索JavaScript中的异步/等待功能— Alligator.io](https://alligator.io/js/async-functions/)

-   📜[使用异步/等待的异步Javascript — Joy Warugu](https://scotch.io/tutorials/asynchronous-javascript-using-async-await)

-   📜 [具有异步/等待功能的现代异步JavaScript — Flavio Copes](https://flaviocopes.com/javascript-async-await/)

-   📜[异步JavaScript：从回调地狱到异步和等待-Demir Selmanovic](https://www.toptal.com/javascript/asynchronous-javascript-async-await-tutorial)

-   📜[Javascript — ES8引入异步/等待功能— Ben Garrison](https://medium.com/@_bengarrison/javascript-es8-introducing-async-await-functions-7a471ec7de8a)

-   📜[How to escape async/await hell — Aditya Agarwal](https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)

-   📜 [了解JavaScript的异步等待状态–NicolásBevacqua](https://ponyfoo.com/articles/understanding-javascript-async-await)

-   📜[JavaScript异步/等待：串行，并行和复杂流— TechBrij](https://techbrij.com/javascript-async-await-parallel-sequence)

-   📜[异步编程-探索JS](http://exploringjs.com/es6/ch_async.html)

-   📜[从JavaScript承诺到异步/等待：为什么要打扰？克里斯·恩旺巴](https://blog.pusher.com/promises-async-await/)

-   📜[Flow Control in Modern JS: Callbacks to Promises to Async/Await — Craig Buckler](https://www.sitepoint.com/flow-control-callbacks-promises-async-await/)

-   📜[JavaScript：承诺以及为何异步/等待赢得胜利—尼克·帕森斯](https://dzone.com/articles/javascript-promises-and-why-asyncawait-wins-the-ba)

-   📜[如何通过这个真实的例子来掌握异步/等待— Adrian Hajdin](https://medium.freecodecamp.org/how-to-master-async-await-with-this-real-world-example-19107e7558ad)

-   📜[如何使用async和await改进异步Javascript代码— Indrek Lasn](https://medium.freecodecamp.org/improve-your-asynchronous-javascript-code-with-async-and-await-c02fc3813eda)

-   📜[通过异步等待使获取变得容易— Mickey Sheridan](https://medium.com/@micksheridan.24/making-fetches-easy-with-async-await-8a1246efa1f6)

-   📜[JavaScript异步/等待优于普通承诺的7个原因-Mostafa Gaafar](https://dev.to/gafi/7-reasons-to-always-use-async-await-over-plain-promises-tutorial-4ej9)

-   📜 [Asynchronous Operations in JavaScript — Jscrambler](https://dev.to/jscrambler/asynchronous-operations-in-javascript-2p6b)

-   📜[异步/等待：轻微的设计缺陷。 —乔伊](https://dev.to/joeyhub/async-await-a-slight-design-flaw-2h2j)

-   📜[JavaScript：承诺或异步等待— Gokul N K](https://medium.com/better-programming/should-i-use-promises-or-async-await-126ab5c98789)

-   📜[异步/等待：从零到英雄-Zhi Yuan](https://dev.to/zhiyuanamos/async-await-from-zero-to-hero-a22)

-   📜[可视化的JavaScript：承诺和异步/等待-莉迪亚·哈莉（Lydia Hallie）](https://dev.to/lydiahallie/javascript-visualized-promises-async-await-5gke)

    ### 影片

-   🎥[异步+等待-Wes Bos](https://www.youtube.com/watch?v=9YkUCxvaLEk)

-   🎥[Asynchrony: Under the Hood — Shelley Vohr](https://www.youtube.com/watch?v=SrNQS8J67zc)

-   🎥[async/await in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=568g8hxJJp4&index=3&list=PL0zVEGEvSaeHJppaRLrqjeTPnCH6)

-   🎥[async / await第1部分-JavaScript / ES8主题-编码火车](https://www.youtube.com/watch?v=XO77Fib9tSI&index=3&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)

-   🎥[async / await第2部分-JavaScript / ES8主题-编码火车](https://www.youtube.com/watch?v=chavThlNz3s&index=4&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)

-   🎥[JS Async＆Await ES2017 / ES8完整指南— Colt Steele](https://www.youtube.com/watch?v=krAYA4rvbdA)

**[⬆回到顶部](#table-of-contents)**

* * *

## 27.数据结构

### 文章

-   📜[JavaScript中的数据结构— Thon Ly](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)

-   📜[Algorithms and Data Structures in JavaScript — Oleksii Trekhleb](https://itnext.io/algorithms-and-data-structures-in-javascript-a71548f902cb)

-   📜[数据结构：对象和数组― Chris Nwamba](https://scotch.io/courses/10-need-to-know-javascript-concepts/data-structures-objects-and-arrays)

-   📜[JavaScript中的数据结构— Benoit Vallon](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)

-   📜[使用Java脚本处理数据结构— Anish K.](https://blog.cloudboost.io/playing-with-data-structures-in-javascript-stack-a55ebe50f29d)

-   📜[JavaScript队列小指南—GermánCutraro](https://hackernoon.com/the-little-guide-of-queue-in-javascript-4f67e79260d9)

-   📜[《算法第四版》一书中所有使用JavaScript编写的算法](https://github.com/barretlee/algorithms)

-   📜[JavaScript中的经典计算机科学范例集合](https://github.com/nzakas/computer-science-in-javascript)

-   📜[有关数据结构的所有您不知道的知识](https://github.com/jamiebuilds/itsy-bitsy-data-structures)

-   📜[JavaScript数据结构：单链接列表：设置— miku86](https://dev.to/miku86/javascript-data-structures-singly-linked-list-setup-4950)

-   📜[JavaScript数据结构：单链接列表：插入— miku86](https://dev.to/miku86/javascript-data-structures-singly-linked-list-insert-3in4)

-   📜[JavaScript数据结构：单链接列表：删除— miku86](https://dev.to/miku86/javascript-data-structures-singly-linked-list-remove-fai)

-   📜[数据结构：理解图— Rachel Hawa](https://medium.com/javascript-in-plain-english/data-structures-understanding-graphs-82509d35e6b5)

    ### 影片

-   🎥[JavaScript中的算法—塞思·科赫（Seth Koch）](https://www.youtube.com/watch?v=PylQlISSH8U&list=PLujX4CIdBGCa-65N3uN8CDbUMrYsHBrz-)

-   🎥[Javascript中的算法面试中获得王牌— Eduonix学习解决方案](https://www.youtube.com/watch?v=H_EBPZgiAas&list=PLDmvslp_VR0zYUSth_8O69p4_cmvZEgLa)

-   🎥[JavaScript中的数据结构和算法— freeCodeCamp](https://www.youtube.com/watch?v=Gj5qBheGOEo&list=PLWKjhJtqVAbkso-IbgiiP48n-O-JQA9PJ)

-   🎥[学习JavaScript数据结构和算法：排序— Packt视频](https://www.youtube.com/watch?v=Ymh_AurrMbA)

**[⬆回到顶部](#table-of-contents)**

* * *

## 28.昂贵的操作和大O表示法

### 文章

-   📜[Java语言中的大O符号-CésarAntónDorantes](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)
-   📜[时间复杂度/大O表示法-蒂姆·罗伯茨](https://medium.com/javascript-scene/time-complexity-big-o-notation-1a4310c3ee4b)
-   📜[JavaScript中的大O — Gabriela Medina](https://medium.com/@gmedina229/big-o-in-javascript-36ff67766051)
-   📜[JavaScript中的大O搜索算法-Bradley Braithwaite](http://www.bradoncode.com/blog/2012/04/big-o-algorithm-examples-in-javascript.html)
-   📜[JavaScript中的时间复杂度分析—詹妮弗·布兰德（Jennifer Bland）](https://www.jenniferbland.com/time-complexity-analysis-in-javascript/)
-   📜[用简单的英语算法：时间复杂度和Big-O表示法— Michael Olorunnisola](https://medium.freecodecamp.org/time-is-complex-but-priceless-f0abd015063c)
-   📜[大O符号简介-Joseph Trettevik](https://dev.to/lofiandcode/an-introduction-to-big-o-notation-210o)

### 影片

-   🎥[JavaScript：大O符号和函数运行时简介— Eric Traub](https://www.youtube.com/watch?v=HgA5VOFan5E)
-   🎥[JavaScript开发人员必不可少的O — Dave Smith](https://www.youtube.com/watch?v=KatlvCFHPRo)
-   🎥[大O符号-时间复杂度分析— WebTunings](https://www.youtube.com/watch?v=ALl86xJiTD8)

**[⬆回到顶部](#table-of-contents)**

* * *

## 29.算法

### 文章

-   📜[使用ES6的数据结构和算法](https://github.com/Crizstian/data-structure-and-algorithms-with-ES6)
-   📜[用JavaScript实现的算法和数据结构，并带有解释和进一步阅读的链接](https://github.com/trekhleb/javascript-algorithms)
-   📜[JS：面试算法](http://www.thatjsdude.com/interview/js1.html)
-   📜[JavaScript中的算法— Thon Ly](https://medium.com/siliconwat/algorithms-in-javascript-b0bed68f4038)
-   📜[JavaScript对象，方括号和算法— Dmitri Grabov](https://medium.freecodecamp.org/javascript-objects-square-brackets-and-algorithms-e9a2916dc158)
-   📜[适用于CS101的阿特伍德定律-用JavaScript实现的经典算法和数据结构](https://github.com/felipernb/algorithms.js)
-   📜[JavaScript中的数据结构和算法库](https://github.com/yangshun/lago)
-   📜[用JavaScript编写的计算机科学算法和数据结构的集合](https://github.com/idosela/algorithms-in-javascript)
-   📜[JavaScript中的算法和数据结构— Oleksii Trekhleb](https://dev.to/trekhleb/algorithms-and-data-structures-in-javascript-49i3)

**[⬆回到顶部](#table-of-contents)**

* * *

## 30.继承，多态和代码重用

### 文章

-   📜[类继承，超级— JavaScript.Info](https://javascript.info/class-inheritance)

-   📜[JavaScript中的继承-MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)

-   📜[JavaScript中的继承— Rupesh Mishra](https://hackernoon.com/inheritance-in-javascript-21d2b82ffa6f)

-   📜[JavaScript的简单继承— David Catuhe](https://www.sitepoint.com/simple-inheritance-javascript/)

-   📜[JavaScript —继承，委托模式和对象链接— NC Patro](https://codeburst.io/javascript-inheritance-25fe61ab9f85)

-   📜[面向对象的JavaScript：多态性与示例— Knoldus博客](https://blog.knoldus.com/object-oriented-javascript-polymorphism-with-examples/)

-   📜[像Proteus这样的程序-Java多态性入门指南-Sam Galson](https://medium.com/yld-engineering-blog/program-like-proteus-a-beginners-guide-to-polymorphism-in-javascript-867bea7c8be2)

-   📜[面向对象的JavaScript：深入探讨ES6类— Jeff Mott](https://www.sitepoint.com/object-oriented-javascript-deep-dive-es6-classes/)

    ### 影片

-   🎥[JavaScript继承— kudvenkat](https://www.youtube.com/watch?v=yXlFR81tDBM)

-   🎥[JavaScript ES6类和继承-遍历媒体](https://www.youtube.com/watch?v=RBLIm5LMrmc)

-   🎥[JavaScript中的多态性— kudvenkat](https://www.youtube.com/watch?v=zdovG9cuEBA)

**[⬆回到顶部](#table-of-contents)**

* * *

## 31.设计模式

### 文章

-   📜[您应该知道的4种JavaScript设计模式-Devan Patel](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know)
-   📜[JavaScript设计模式–移动Web开发入门指南– Soumyajit Pathak](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15)
-   📜[JavaScript设计模式— Akash Pal](https://medium.com/front-end-hacking/javascript-design-patterns-ed9d4c144c81)
-   📜[Javascript设计模式：它们是什么以及如何使用它们-Patrick Simpson](https://seesparkbox.com/foundry/javascript_design_patterns)
-   📜[JavaScript设计模式：了解JavaScript中的设计模式-Sukhjinder Arora](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
-   📜[用Javascript实现的所有23（GoF）设计模式— Felipe Beline](https://github.com/fbeline/Design-Patterns-JS)
-   📜[JavaScript中模块模式的力量— jsmanifest](https://medium.com/better-programming/the-power-of-the-module-pattern-in-javascript-3c73f7cd10e8)
-   📜[学习JavaScript设计模式— Addy Osmani](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)
-   📜[使用JavaScript pt的开发人员设计模式。我-奥利弗·门萨（Oliver Mensah）](https://dev.to/omensah/design-patterns-for-developers-using-javascript----part-one--b3e)
-   📜[使用JavaScript pt的开发人员设计模式。 II —奥利弗·门萨（Oliver Mensah）](https://dev.to/omensah/design-patterns-for-developers-using-javascript---part-two--3p39)
-   📜[现代JavaScript开发中的设计模式](https://levelup.gitconnected.com/design-patterns-in-modern-javascript-development-ec84d8be06ca)
-   📜[了解设计模式：使用Dev.to和Medium社交网络的迭代器！ —卡洛斯·卡瓦列罗（Carlos Caballero）](https://dev.to/carlillo/understanding-design-patterns-iterator-using-dev-to-and-medium-social-networks-3bdd)
-   📜[JavaScript设计模式-工厂模式—KristijanFištrek](https://dev.to/kristijanfistrek/javascript-design-patterns-factory-pattern-562p)
-   📜[JavaScript设计模式-模块模式-工厂模式-月球](https://medium.com/javascript-in-plain-english/javascript-design-pattern-module-pattern-555737eccecd)
-   📜[设计模式：空对象-Carlos Caballero](https://medium.com/better-programming/design-patterns-null-object-5ee839e37892)
-   📜[策略模式-Francesco Ciulla](https://dev.to/francescoxx/strategy-pattern-5oh)
-   📜[适配器图案-Francesco Ciulla](https://dev.to/francescoxx/adapter-pattern-5bjk)
-   📜[JavaScript中复合模式的强大功能-jsmanifest](https://dev.to/jsmanifest/the-power-of-composite-pattern-in-javascript-2732)

### 影片

-   🎥[JavaScript设计模式— Udacity](https://www.udacity.com/course/javascript-design-patterns--ud989)
-   🎥[2017年的JavaScript模式-Scott Allen](https://www.youtube.com/watch?v=hO7mzO83N1Q)

    **[⬆回到顶部](#table-of-contents)**

* * *

## 32.部分应用程序，固化，组成和管道

### 文章

-   📜[在JavaScript中使用函数组合—Rémi](https://www.codementor.io/michelre/use-function-composition-in-javascript-gkmxos5mj)

-   📜[用JavaScript ES6编写库— Adam Bene](https://blog.benestudio.co/currying-in-javascript-es6-540d2ad09400)

-   📜[JavaScript中的合成和优雅处理— Pragyan Das](https://medium.com/@pragyan88/writing-middleware-composition-and-currying-elegance-in-javascript-8b15c98a541b)

-   📜[功能JavaScript：日常使用的功能组合— Joel Thoms](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)

-   📜[功能组成：compose（）和pipe（）— Anton Paras](https://medium.com/@acparas/what-i-learned-today-july-2-2017-ab9a46dbf85f)

-   📜[为什么赶时髦的人组成一切：使用JavaScript编写功能— A. Sharif](http://busypeoples.github.io/post/functional-composing-javascript/)

-   📜[功能JavaScript pt III简介：编写函数的函数— James Sinclair](https://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-functions/)

-   📜[Curry And Compose（为什么要在代码中使用ramda之类的东西）— jsanchesleao](https://jsleao.wordpress.com/2015/02/22/curry-and-compose-why-you-should-be-using-something-like-ramda-in-your-code/)

-   📜[带管道的JavaScript中的函数组合— Andy Van Slaars](https://vanslaars.io/post/create-pipe-function/)

-   📜[Ramda的实用功能JavaScript — Andrew D'Amelio，Yuri Takhteyev](https://developer.telerik.com/featured/practical-functional-javascript-ramda/)

-   📜[部分应用，咖喱和功能组成中的美— Joel Thoms](https://hackernoon.com/the-beauty-in-partial-application-currying-and-function-composition-d885bdf0d574)

-   📜[咖喱还是部分应用？ —埃里克·埃利奥特（Eric Elliott）](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8)

-   📜[JavaScript中的部分应用程序— Ben Alman](http://benalman.com/news/2012/09/partial-application-in-javascript/)

-   📜[功能的部分应用-功能性反应忍者](https://hackernoon.com/partial-application-of-functions-dbe7d9b80760)

-   📜[咖喱vs部分施用— Deepak Gupta](https://codeburst.io/javascript-currying-vs-partial-application-4db5b2442be8)

-   📜[ECMAScript 2015中的部分应用程序— Ragan Wald](http://raganwald.com/2015/04/01/partial-application.html)

-   📜[Javascript中的功能组合-Joe Cortopassi](https://joecortopassi.com/articles/functional-composition-in-javascript/)

-   📜[因此，您想成为一名功能程序员。我-查尔斯·斯卡法尼（Charles Scalfani）](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)

-   📜[因此，您想成为一名功能程序员。 II –查尔斯·斯卡法尼（Charles Scalfani）](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-2-7005682cec4a)

-   📜[因此，您想成为一名功能程序员。 III –查尔斯·斯卡法尼（Charles Scalfani）](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-3-1b0fd14eb1a7)

-   📜[因此，您想成为一名功能程序员。 IV-查尔斯·斯卡法尼（Charles Scalfani）](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-4-18fbe3ea9e49)

-   📜[因此，您想成为一名功能程序员。 V-查尔斯·斯卡法尼（Charles Scalfani）](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-5-c70adc9cf56a)

-   📜[功能轻的JavaScript第3章：管理函数输入-Kyle Simpson](https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch3.md)

-   📜[函数式编程的基本原理简介-TK](https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84)

-   📜[Javascript中的函数式编程的概念— TK](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

-   📜[JavaScript中的函数式编程风格简介— JavaScript老师](https://medium.freecodecamp.org/an-introduction-to-functional-programming-style-in-javascript-71fcc050f064)

-   📜[编写实用的JavaScript实用指南-Nadeesha Cabral](https://medium.freecodecamp.org/a-practical-guide-to-writing-more-functional-javascript-db49409f71)

-   📜[JavaScript中功能管道的简单说明— Ben Lesh](https://dev.to/benlesh/a-simple-explanation-of-functional-pipe-in-javascript-2hbj)

    ### 影片

-   🎥[Compose vs Pipe：JavaScript中的函数式编程— Chyld Studios](https://www.youtube.com/watch?v=Wl2ejJOqHUU)

-   🎥[JavaScript函数式编程：撰写-Theodore Anderson](https://www.youtube.com/watch?v=jigHxo9YR30)

-   🎥[函数组成-函数JavaScript — NWCalvank](https://www.youtube.com/watch?v=mth5WpEc4Qs)

-   🎥[JavaScript函数组成介绍— Theodore Anderson](https://www.youtube.com/watch?v=Uam37AlzPYw)

-   🎥[让我们编写具有函数组成的代码— Fun Fun Function](https://www.youtube.com/watch?v=VGB9HbL1GHk)

-   🎥[部分应用与咖喱— NWCalvank](https://www.youtube.com/watch?v=DzLkRsUN2vE)

-   🎥[JavaScript部分应用程序— Theodore Anderson](https://www.youtube.com/watch?v=jkebgHEcvac)

**[⬆回到顶部](#table-of-contents)**

* * *

## 33.清洁代码

### 文章

-   📜[适用于JavaScript的简洁代码概念— Ryan McDermott](https://github.com/ryanmcdermott/clean-code-javascript)
-   📜[JavaScript干净编码最佳做法—AndrásTóth](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)
-   📜[JavaScript Clean Code中的函数参数-Kevin Peters](https://medium.com/@kevin_peters/function-parameters-in-javascript-clean-code-4caac109159b)
-   📜[保持代码干净— Samuel James](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)
-   📜[使用现代JavaScript语法的最佳做法-M. David Green](https://www.sitepoint.com/modern-javascript-best-practices/)
-   📜[跨节点/ Web开发的最佳实践-JimmyWärting](https://github.com/cross-js/cross-js)
-   📜[编写干净的代码-Dylan Paulus](https://dev.to/ganderzz/on-writing-clean-code-57cm)
-   📜[编写干净的代码和编程实践-Nityesh Agarwal](https://dev.to/nityeshaga/writing-clean-code-and-the-practice-of-programming-actionable-advice-for-beginners-5f0k)
-   📜[干净代码，肮脏代码，人类代码-Daniel Irvine](https://dev.to/d_ir/clean-code-dirty-code-human-code-6nm)

### 影片

-   🎥[JavaScript Pro技巧-编写此代码，并非如此](https://www.youtube.com/watch?v=Mus_vwhTCq0)
-   🎥[干净代码：函数（第1部分）-Beau讲授](https://www.youtube.com/watch?v=RR_dQ4sBSBM)

    **[⬆回到顶部](#table-of-contents)**
