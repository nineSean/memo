

### 2018/06/30

- Kernel&Shell

  - Kernel（核），操作系统的中心，分配时间和内存；处理文件存储和通讯以响应系统的调用。
  - Shell（壳），一种用户与kernel之间的接口。

- POSIX

  - Portable Operating System Interface 
  - 一种标准，定义了标准API用于兼容各种系统 

- REST

  - Representational State Transfer
  - 一种万维网软件架构风格
  - 目的是便于软件/程序在网络中传递数据
  - 基于HTTP之上而确定的一组约定和属性

- Snapchat

- http cache strategy

  - [https://segmentfault.com/a/1190000008956069](https://segmentfault.com/a/1190000008956069)

- shell scripting

  - [https://github.com/qinjx/30min_guides/blob/master/shell.md](https://github.com/qinjx/30min_guides/blob/master/shell.md)
  - [https://www.shellscript.sh/](https://www.shellscript.sh/)

- JavaScript design pattern

  - [http://wiki.jikexueyuan.com/project/javascript-design-patterns/mvc.html](http://wiki.jikexueyuan.com/project/javascript-design-patterns/mvc.html)
  - [https://addyosmani.com/resources/essentialjsdesignpatterns/book/#detailmvc](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#detailmvc)

### 2018/07/01

- Lisp系语言（函数式编程范式）

  - [http://www.ruanyifeng.com/blog/2010/10/why_lisp_is_superior.html](http://www.ruanyifeng.com/blog/2010/10/why_lisp_is_superior.html)

- 算法语言Scheme

  - [https://r6rs.mrliu.org/](https://r6rs.mrliu.org/)

- SICP课程/PPT/习题集

  - [http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/](http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/)
  - [http://www.math.pku.edu.cn/teachers/qiuzy/progtech/MIT_slides/](http://www.math.pku.edu.cn/teachers/qiuzy/progtech/MIT_slides/)
  - [http://sicp.readthedocs.io/en/latest/](http://sicp.readthedocs.io/en/latest/)
  - [http://numbbbbb.com/2016/03/28/20160328_%E6%88%91%E5%A6%82%E4%BD%95%E7%94%A8%E4%B8%A4%E5%91%A8%E6%97%B6%E9%97%B4%E5%88%B7%E5%AE%8C%20SICP/](http://numbbbbb.com/2016/03/28/20160328_%E6%88%91%E5%A6%82%E4%BD%95%E7%94%A8%E4%B8%A4%E5%91%A8%E6%97%B6%E9%97%B4%E5%88%B7%E5%AE%8C%20SICP/)

- Linked List

  - [https://codeburst.io/js-data-structures-linked-list-3ed4d63e6571](https://codeburst.io/js-data-structures-linked-list-3ed4d63e6571)

- 时间复杂度

  - [https://blog.csdn.net/zolalad/article/details/11848739](https://blog.csdn.net/zolalad/article/details/11848739)

- Generator

  - [https://gu.illau.me/posts/polyfilling-generators/](https://gu.illau.me/posts/polyfilling-generators/)

- Underscore 整体架构

  - [https://github.com/hanzichi/underscore-analysis/issues/27](https://github.com/hanzichi/underscore-analysis/issues/27)

### 2018/07/02

- Javascrit类型检查

  - [https://webbjocke.com/javascript-check-data-types/](https://webbjocke.com/javascript-check-data-types/)

```

//check Array

function isArray(value){

​	return typeof value === ‘object’ && value instaceof Array //用constructor来判断容易伪造

}

Array.isArray(value)

//check null

function isNull(value){

​	return value === null

}

//check NaN

isNaN(value)

```

- vim替换
  - [http://tanqisen.github.io/blog/2013/01/13/vim-search-replace-regex/](http://tanqisen.github.io/blog/2013/01/13/vim-search-replace-regex/)
  - [http://vimregex.com/](http://vimregex.com/)
- SDK
- DP(dynamic programming)

  - 把一个问题划分成若干子问题，相同的子问题只需解决一次进而减少了计算量。
- git flow

  - [https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/git-flow](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/git-flow)
- git cherry-pick

  - [https://www.jianshu.com/p/08c3f1804b36](https://www.jianshu.com/p/08c3f1804b36)
  - [https://juejin.im/post/5925a2d9a22b9d0058b0fd9b](https://juejin.im/post/5925a2d9a22b9d0058b0fd9b)
- jj

```

:imap jj <Esc>

```

### 2018/07/03

- why primitive type of string instanceof String is false but can inherit method from prototype chain

  - [https://javascriptrefined.io/the-wrapper-object-400311b29151](https://javascriptrefined.io/the-wrapper-object-400311b29151)
  - [https://hacks.mozilla.org/2012/12/performance-with-javascript-string-objects/](https://hacks.mozilla.org/2012/12/performance-with-javascript-string-objects/)

- requestAnimationFrame

  - [https://javascript.ruanyifeng.com/htmlapi/requestanimationframe.html](https://javascript.ruanyifeng.com/htmlapi/requestanimationframe.html)
  - [https://hacks.mozilla.org/2011/08/animating-with-javascript-from-setinterval-to-requestanimationframe/](https://hacks.mozilla.org/2011/08/animating-with-javascript-from-setinterval-to-requestanimationframe/)

### 2018/07/04

- how browsers work

  - [https://coolshell.cn/articles/9666.html](https://coolshell.cn/articles/9666.html)
  - [https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance-7b95553baeda](https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance-7b95553baeda)
  - [https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)

- 数组去重

  - [https://github.com/mqyqingfeng/Blog/issues/27](https://github.com/mqyqingfeng/Blog/issues/27)
  - [https://github.com/huangchucai/My-Note-Blog/issues/13](https://github.com/huangchucai/My-Note-Blog/issues/13)

- Persistence data

  - [https://www.datastax.com/dev/blog/what-persistence-and-why-does-it-matter](https://www.datastax.com/dev/blog/what-persistence-and-why-does-it-matter)

