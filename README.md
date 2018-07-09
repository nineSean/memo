


### 2018/06/30

##### Kernel&Shell

- Kernel（核），操作系统的中心，分配时间和内存；处理文件存储和通讯以响应系统的调用。
  - Shell（壳），一种用户与kernel之间的接口。

##### POSIX

- Portable Operating System Interface 
  - 一种标准，定义了标准API用于兼容各种系统 

##### REST

- Representational State Transfer
  - 一种万维网软件架构风格
  - 目的是便于软件/程序在网络中传递数据
  - 基于HTTP之上而确定的一组约定和属性

##### Snapchat

##### http cache strategy

- [https://segmentfault.com/a/1190000008956069](https://segmentfault.com/a/1190000008956069)

##### shell scripting

- [https://github.com/qinjx/30min_guides/blob/master/shell.md](https://github.com/qinjx/30min_guides/blob/master/shell.md)
  - [https://www.shellscript.sh/](https://www.shellscript.sh/)

##### JavaScript design pattern

- [http://wiki.jikexueyuan.com/project/javascript-design-patterns/mvc.html](http://wiki.jikexueyuan.com/project/javascript-design-patterns/mvc.html)
  - [https://addyosmani.com/resources/essentialjsdesignpatterns/book/#detailmvc](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#detailmvc)

### 2018/07/01

##### Lisp系语言（函数式编程范式）

- [http://www.ruanyifeng.com/blog/2010/10/why_lisp_is_superior.html](http://www.ruanyifeng.com/blog/2010/10/why_lisp_is_superior.html)

##### 算法语言Scheme

- [https://r6rs.mrliu.org/](https://r6rs.mrliu.org/)

##### SICP课程/PPT/习题集

- [http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/](http://groups.csail.mit.edu/mac/classes/6.001/abelson-sussman-lectures/)
  - [http://www.math.pku.edu.cn/teachers/qiuzy/progtech/MIT_slides/](http://www.math.pku.edu.cn/teachers/qiuzy/progtech/MIT_slides/)
  - [http://sicp.readthedocs.io/en/latest/](http://sicp.readthedocs.io/en/latest/)
  - [http://numbbbbb.com/2016/03/28/20160328_%E6%88%91%E5%A6%82%E4%BD%95%E7%94%A8%E4%B8%A4%E5%91%A8%E6%97%B6%E9%97%B4%E5%88%B7%E5%AE%8C%20SICP/](http://numbbbbb.com/2016/03/28/20160328_%E6%88%91%E5%A6%82%E4%BD%95%E7%94%A8%E4%B8%A4%E5%91%A8%E6%97%B6%E9%97%B4%E5%88%B7%E5%AE%8C%20SICP/)

##### Linked List

- [https://codeburst.io/js-data-structures-linked-list-3ed4d63e6571](https://codeburst.io/js-data-structures-linked-list-3ed4d63e6571)

##### 时空复杂度

- [https://blog.csdn.net/zolalad/article/details/11848739](https://blog.csdn.net/zolalad/article/details/11848739)

##### Generator

- [https://gu.illau.me/posts/polyfilling-generators/](https://gu.illau.me/posts/polyfilling-generators/)

##### Underscore 整体架构

- [https://github.com/hanzichi/underscore-analysis/issues/27](https://github.com/hanzichi/underscore-analysis/issues/27)

### 2018/07/02

##### Javascrit类型检查

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

##### vim替换
- [http://tanqisen.github.io/blog/2013/01/13/vim-search-replace-regex/](http://tanqisen.github.io/blog/2013/01/13/vim-search-replace-regex/)
  - [http://vimregex.com/](http://vimregex.com/)
##### SDK
##### DP(dynamic programming)

- 把一个问题划分成若干子问题，相同的子问题只需解决一次进而减少了计算量。
##### git flow

- [https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/git-flow](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/git-flow)
##### git cherry-pick

- [https://www.jianshu.com/p/08c3f1804b36](https://www.jianshu.com/p/08c3f1804b36)
  - [https://juejin.im/post/5925a2d9a22b9d0058b0fd9b](https://juejin.im/post/5925a2d9a22b9d0058b0fd9b)
##### jj

```

:imap jj <Esc>

```

### 2018/07/03

##### why primitive type of string instanceof String is false but can inherit method from prototype chain

- [https://javascriptrefined.io/the-wrapper-object-400311b29151](https://javascriptrefined.io/the-wrapper-object-400311b29151)
  - [https://hacks.mozilla.org/2012/12/performance-with-javascript-string-objects/](https://hacks.mozilla.org/2012/12/performance-with-javascript-string-objects/)

##### requestAnimationFrame

- [https://javascript.ruanyifeng.com/htmlapi/requestanimationframe.html](https://javascript.ruanyifeng.com/htmlapi/requestanimationframe.html)
  - [https://hacks.mozilla.org/2011/08/animating-with-javascript-from-setinterval-to-requestanimationframe/](https://hacks.mozilla.org/2011/08/animating-with-javascript-from-setinterval-to-requestanimationframe/)

### 2018/07/04

##### how browsers work
- [https://medium.com/@ramsunvtech/behind-browser-basics-part-1-b733e9f3c0e6](https://medium.com/@ramsunvtech/behind-browser-basics-part-1-b733e9f3c0e6)
  - [https://coolshell.cn/articles/9666.html](https://coolshell.cn/articles/9666.html)
  - [https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance-7b95553baeda](https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance-7b95553baeda)
  - [https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)


##### 数组去重

-   [https://github.com/mqyqingfeng/Blog/issues/27](https://github.com/mqyqingfeng/Blog/issues/27)
  - [https://github.com/huangchucai/My-Note-Blog/issues/13](https://github.com/huangchucai/My-Note-Blog/issues/13)

  ****
##### Persistence data

- [https://www.datastax.com/dev/blog/what-persistence-and-why-does-it-matter](https://www.datastax.com/dev/blog/what-persistence-and-why-does-it-matter)




### 2018/07/05

##### <a href='./img/guide for learning computer language.png'>语言学习指南</a>

##### [项目结构目录](https://www.dropbox.com/s/7c2v7es1dg3c730/Screenshot%202018-07-05%2001.25.05.png?dl=0)

##### bindRight实现
-   https://code.h5jun.com/qig/edit?js,console

  ```
  Function.prototype.bindRight = function(thisObj, ...values){
    let fn = this, len = fn.length - values.length;
    return function(...args){
      let rest = [], rargs = values.reverse();
      
      if(len > 0){
        rest = args.slice(0, len);
      }

      return fn.apply(thisObj, rest.concat(rargs));
    }
  }

  console.log(["2","3","4"].map(parseInt));

  console.log(["2","3","4"].map(parseInt.bindRight(null, 10)));

  function add(x, y, z){
      return 100*x + 10 * y + z;
  }

  let add1 = add.bind(null, 1, 2);
  let add2 = add.bindRight(null, 1, 2);

  console.log(add1(3)); //123
  console.log(add2(3)); //321
  ```

  ​

##### 倒计时动画
- https://code.h5jun.com/vix/edit?js,output
  - https://code.w3ctech.com/detail/239

##### 月影code
- https://code.w3ctech.com/465?page=3
  - https://code.w3ctech.com/465?page=2
  - https://code.w3ctech.com/465?page=1

##### CSS水平、垂直居中
- https://sokrati.com/csswarriors/css-horizontal-vertical-centering/
  - http://louiszhai.github.io/2016/03/12/css-center/

##### eventloop
- https://itnext.io/how-javascript-works-in-browser-and-node-ab7d0d09ac2f
  - https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40



### 2018/07/06

##### CSS3 3D transforms

- https://3dtransforms.desandro.com/


##### Dymatic vs Static, Strong vs Weak

- Dymatic versus static is about when to check for types, strong versus weak is about how serious do you get while checking the types.
  - JS is dymatic and weak language.
  - Dymatic means checking the types and looking for type errors during runtime.On the contrary, statics does during compile time.
  - Weak means allowing implicit conversion. Strongs is opposite.
  - https://www.youtube.com/watch?v=C5fr0LZLMAs

##### 有趣的JS教程

- https://www.youtube.com/watch?v=muFql8Z4sCg&list=PL-xu4i_QDSxcoDNeh8rx5-pHCCTOg0XsI
  - https://en.hexlet.io/courses/intro_to_programming

##### 深入JS动态、弱类型特性

- https://dzone.com/articles/understanding-loose-typing-jav
  - [https://medium.com/@gaperton/typescript-static-or-dynamic-64bceb50b93e](https://medium.com/@gaperton/typescript-static-or-dynamic-64bceb50b93e)
  - https://softwareengineering.stackexchange.com/questions/122205/what-is-the-supposed-productivity-gain-of-dynamic-typing



### 2018/07/07

##### package-lock.josn

- https://medium.com/@Quigley_Ja/everything-you-wanted-to-know-about-package-lock-json-b81911aa8ab8

##### 柯里化

- 把多参函数转化为单参函数

```
function curryIt(fn) {
    let args = []
    let countDown = fn.length
    return function(){
        args.push(arguments[0])
        if(--countDown <= 0) return fn.apply(undefined, args)
        return arguments.callee
    }
}

// 测试用例
var fn = function (a, b, c) {return a + b + c}; 
curryIt(fn)(1)(2)(3); // 6
```

##### 获取数字 num 二进制形式第 bit 位的值

```
// 注意：
// 1、bit 从 1 开始
// 2、返回 0 或 1
// 3、举例：2 的二进制为 10，第 1 位为 0，第 2 位为 1

function valueAtBit(num, bit) {
    return +num.toString(2).split('').reverse().slice(bit - 1, bit)
}

// 测试用例
valueAtBit(128, 8) // 1
```

##### 求 a 和 b 相乘的值，a 和 b 可能是小数，需要注意结果的精度问题

```
function multiply(a, b) {
    return a * getMultiple(a) * b * getMultiple(b)/ getMultiple(a) / getMultiple(b)
}

function getMultiple(num){
    return Math.pow(10, ((num + '').length - 1 - ((num + '').indexOf('.'))))
}

// 测试用例
multiply(3, 0.0001) // 0.0003
```



### 2018/07/08

##### 给定字符串 str，检查其是否包含 连续3个数字 

```
// 1、如果包含，返回最新出现的 3 个数字的字符串
// 2、如果不包含，返回 false
// 注意：必须是三个连续数

function captureThreeNumbers(str) {
    let temp = ''
	let arr = str.split('')
	for(let i = 0; i < arr.length; i++){
		if(Math.abs(+arr[i] - +arr[i+1]) === 1){
			if(temp[1]){
				if(Math.abs(+temp[0] - +arr[i]) === 2) return temp += arr[i]
				temp = ''
			}else temp += arr[i]			
        }else temp = ''
	}
	return false
}

// 测试用例
captureThreeNumbers('9896543') // 654
```

##### Regexp railroad diagram

- https://regexper.com/

##### 给定字符串 str，检查其是否符合美元书写格式

```
// 1、以 $ 开始
// 2、整数部分，从个位起，满 3 个数字用 , 分隔
// 3、如果为小数，则小数部分长度为 2
// 4、正确的格式如：$1,023,032.03 或者 $2.03，错误的格式如：$3,432,12.12 或者 $34,344.3
// 小数点后两位是一定要写的

function isUSD(str) {
    return /^\$\d{1,3}(,\d{3})*\.\d{2}$/g.test(str)
}

// 测试用例
isUSD('$20,933,209.93') // true
```

##### Detect Pangram

- http://www.codewars.com/kata/545cedaa9943f7fe7b000048/solutions/javascript/all/clever

```
// A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).
// Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

function isPangram(string){
  string = string.toLowerCase()
  let hash = {}
  let count = 0
  for(let v of str){
    if(/[a-z]/.test(v)){
      count++
      if(hash[v]) count--
      hash[v] = true
    }
  }
  return count === 26
}

//clever
function isPangram(string){
// assertions => x(?=y)匹配x后面必须有y 与 x(?!y)匹配x后面不能有y
  return (string.match(/([a-z])(?!.*\1)/ig) || []).length === 26;
}
```

##### Contains Duplicate

-   https://leetcode.com/submissions/detail/162597934/

  ```
  // Given an array of integers, find if the array contains any duplicates.
  //	Your function should return true if any value appears at least twice in the array, and it should return false if every element is distinct.

  function containsDuplicate(nums){
    const visited = new Set()
    for(let num of nums){
      if(vistied.has(num))
        return true
      visitied.add(num)
    }
    return false
  }
  ```

##### Contains Duplicate II

-   https://leetcode.com/submissions/detail/162606600/

  ```
  // Given an array of integers and an integer k, find out whether there are two distinct indices i and j in the array such that nums[i] = nums[j] and the absolute difference between i and j is at most k.

  // example
  // Input: nums = [1,2,3,1], k = 3
  // Output: true
  // 
  // Input: nums = [1,2,3,1,2,3], k = 2
  // Output: false

  /**
   * @param {number[]} nums
   * @param {number} k
   * @return {boolean}
   */
  var containsNearbyDuplicate = function(nums, k) {
      if (!nums.length) return false
      if (nums.length == 1) return false
      
      var map = new Map()
      
      for (var i = 0; i < nums.length; i++) {
          if (map.has(nums[i])) {
              if (i - map.get(nums[i]) <= k) {
                  return true
              } else {
                  map.set(nums[i], i)
              }
          }
          else map.set(nums[i], i)
      }
      
      return false
  };
  ```

  ​

##### 封装类型检查函数

  ```
  function checkType(data){
    return Object.prototype.toString.call(data).match(/\b([a-z]+)\]/i)[1]
  }
  ```

##### Find the odd int

-   http://www.codewars.com/kata/54da5a58ea159efa38000836/solutions/javascript

  ```
  // Given an array, find the int that appears an odd number of times.
  // There will always be only one integer that appears an odd number of times.

  // clever
  const findOdd = (xs) => xs.reduce((a, b) => a ^ b);
  ```

##### Sort the odd

-   http://www.codewars.com/kata/578aa45ee9fd15ff4600090d/solutions/javascript

  ```
  // You have an array of numbers.
  // Your task is to sort ascending odd numbers but even numbers must be on their places.
  // Zero isn't an odd number and you don't need to move it. If you have an empty array, you need to return it.

  Example
  //sortArray([5, 3, 2, 8, 1, 4]) == [1, 3, 2, 8, 5, 4]

  //clever
  function sortArray(array) {
    const odd = array.filter((x) => x % 2).sort((a,b) => a - b);
    return array.map((x) => x % 2 ? odd.shift() : x);
  }
  ```

##### shortest word

-   https://www.codewars.com/kata/shortest-word/solutions/javascript

  ```
  // Simple, given a string of words, return the length of the shortest word(s).

  // String will never be empty and you do not need to account for different data types.

  //clever
  function findeShort(s){
    return Math.min.apply(null, s.split(' ').map(v => v.length))
  }
  ```

##### a chain adding function

-   https://www.codewars.com/kata/539a0e4d85e3425cb0000a88/solutions/javascript/all/clever

  - <a href='https://www.dropbox.com/s/hvguh7keer7t5u1/Screenshot%202018-07-08%2017.49.06.png?dl=0'>描述</a>

  ```
  //不够简洁，逻辑上要向clever靠
  function add(n){
    let sum = n
    function mid(m){
      sum += m
      return mid
    }
    mid.valueOf =  () => sum
    return mid
  }

  // clever
  function add(n) {
  // this | 0，当this转数字失败为NaN时，this | 0 === 0；而当this为数字时，this | 0 === this。bitwise or很巧妙的一种兼容方法
  // n += this | 0，执行一次add都把实参n加上之前的累加值this（通过bind把本次相加结果传入下次的this）
    var next = add.bind(n += this | 0);
    next.valueOf = function() { return n; };
    return next;
  }
  ```

### 2018/07/09
##### bitwise operation use case

- https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5

##### Contains Duplicate III

- https://leetcode.com/submissions/detail/162799953/

```
//Given an array of integers, find out whether there are two distinct indices i and j in the array such that the absolute difference between nums[i] and nums[j] is at most t and the absolute difference between i and j is at most k.
//example 1:
//Input: nums = [1,5,9,2,5,9], k = 2, t = 3
//Output: true
//example 2:
//Input: nums = [1,5,9,1,5,9], k = 2, t = 3
//Output: false


//292ms
var containsNearbyAlmostDuplicate = function(nums, k, t) {
    for(let i = 0; i < nums.length; i++){
      for(let j = i + 1; j < nums.length; j++){
        if(j - i <= k){
          if(Math.abs(nums[j] - nums[i]) <= t)
            return true
        }else break
      }
    }
    return false
};

//80ms
var containsNearbyAlmostDuplicate = function(nums, k, t) {
    const map = nums
    .map((val, idx) => ({ val, idx }))
    .sort((a, b) => a.val - b.val);

  let l = 0;
  let r = 1;

  while (r < map.length) {
    const diff = Math.abs(map[r].val - map[l].val);
    const range = Math.abs(map[r].idx - map[l].idx);

    if (diff <= t && range <= k) return true;
    else if (diff > t) l++;
    else if (range > k) r++;

    if (l === r) r++;
  }

  return false;
};
```

##### sum of pairs

- https://www.codewars.com/kata/sum-of-pairs/solutions/javascript?show-solutions=1

```
// Given a list of integers and a single sum value, return the first two values (parse from the left please) in order of appearance that add up to form the sum.
// 
// sum_pairs([11, 3, 7, 5],         10)
// #              ^--^      3 + 7 = 10
// == [3, 7]
// 
// sum_pairs([4, 3, 2, 3, 4],         6)
// #          ^-----^         4 + 2 = 6, indices: 0, 2 *
// #             ^-----^      3 + 3 = 6, indices: 1, 3
// #                ^-----^   2 + 4 = 6, indices: 2, 4
// #  * entire pair is earlier, and therefore is the correct answer
// == [4, 2]

// sum_pairs([0, 0, -2, 3], 2)
// #  there are no pairs of values that can be added to produce 2.
// == None/nil/undefined (Based on the language)
// 
// sum_pairs([10, 5, 2, 3, 7, 5],         10)
// #              ^-----------^   5 + 5 = 10, indices: 1, 5
// #                    ^--^      3 + 7 = 10, indices: 3, 4 *
// #  * entire pair is earlier, and therefore is the correct answer
// == [3, 7]
// 
// Negative numbers and duplicate numbers can and will appear.
// 
// NOTE: There will also be lists tested of lengths upwards of 10,000,000 elements. Be sure your code doesn't time out.

//数据量过大时超时，按照逻辑实现了，但是2个loop时间复杂度为O(n^2)
var sum_pairs=function(ints, s){
  let indexPairs = []
  for(let i = 0; i < (indexPairs[0] ? indexPairs[0][1] : ints.length); i++){
    for(let j = i + 1; j < (indexPairs[0] ? indexPairs[0][1] : ints.length); j++){
      if(ints[i] + ints[j] === s){
        indexPairs.push([i ,j])
        indexPairs.sort((a, b) => a[1] - b[1])
        break
      }
    }
  }
  return indexPairs[0] ? [ints[indexPairs[0][0]], ints[indexPairs[0][1]]] : undefined
}

//clever
var sum_pairs=function(ints, s){
  var seen = {}
  for (var i = 0; i < ints.length; ++i) {
    if (seen[s - ints[i]]) return [s - ints[i], ints[i]];
    seen[ints[i]] = true
  }
}

var sum_pairs=function(ints, s){
    let map = new Map();
    
    for (let i=0; i < ints.length; i++) {
      if (map.has(s - ints[i])) {
        return [ s - ints[i], ints[i] ];
      }
      map.set(ints[i], i);
    }
}
```

##### Your order, please

- https://www.codewars.com/kata/55c45be3b2079eccff00010f/solutions/javascript

```
// Your task is to sort a given string. Each word in the String will contain a single number. This number is the position the word should have in the result.
// 
// Note: Numbers can be from 1 to 9. So 1 will be the first word (not 0).
// 
// If the input String is empty, return an empty String. The words in the input String will only contain valid consecutive numbers.
// 
// For an input: "is2 Thi1s T4est 3a" the function should return "Thi1s is2 3a T4est"
// 
// your_order("is2 Thi1s T4est 3a")
// [1] "Thi1s is2 3a T4est"

// 思路和实现都和clever一样，算是有点提高吧
function order(words){
  let arr = words.split(' ')
  function pickNum(str){
    return +str.match(/\d/)[0]
  }
  arr.sort((a, b) => pickNum(a) - pickNum(b))
  return arr.join(' ')
}

// clever
function order(words){
  
  return words.split(' ').sort(function(a, b){
      return a.match(/\d/) - b.match(/\d/);
   }).join(' ');
}    
```

  

##### Duplicate Encoder

- https://www.codewars.com/kata/54b42f9314d9229fd6000d9c/solutions/javascript

```
// The goal of this exercise is to convert a string to a new string where each character in the new string is '(' if that character appears only once in the original string, or ')' if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.
// 
// Examples:
// 
// "din" => "((("
// 
// "recede" => "()()()"
// 
// "Success" => ")())())"
// 
// "(( @" => "))(("

// 时间复杂度为O(n^2)，clever利用正反索引来判断是否重复则为O(n)
function duplicateEncode(word){
  let hash = {}
  word.toLowerCase().split('').map(v => hash[v] ? hash[v]++ : hash[v] = 1)
  return word.toLowerCase().split('').map(v => hash[v] > 1 ? ')' : '(').join('')
}

//clever
function duplicateEncode(word){
  return word
    .toLowerCase()
    .split('')
    .map( function (a, i, w) {
      return w.indexOf(a) == w.lastIndexOf(a) ? '(' : ')'
    })
    .join('');
}
```



##### Counting Duplicates

- https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1/solutions/javascript

```
// Count the number of Duplicates
// Write a function that will return the count of distinct case-insensitive alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits.
// 
// Example
// "abcde" -> 0 # no characters repeats more than once
// "aabbcde" -> 2 # 'a' and 'b'
// "aabBcde" -> 2 # 'a' occurs twice and 'b' twice (bandB)
// "indivisibility" -> 1 # 'i' occurs six times
// "Indivisibilities" -> 2 # 'i' occurs seven times and 's' occurs twice
// "aA11" -> 2 # 'a' and '1'
// "ABBA" -> 2 # 'A' and 'B' each occur twice


//clever with regexp
function duplicateCount(text){
  return (text.toLowerCase().split('').sort().join('').match(/([^])\1+/g) || []).length;
}
//([^]) Capture any character, as . doesn't literally match every character.
//The . wildcard doesn't match newlines. The [^] expression matches everything.
//([^])为何return的array没有捕捉分组？ ===> flag中带了g，return的array中就不捕捉分组了，而且只返回匹配项的数组，不包括其它属性。认真看了遍MDN，description中有提到，汗...，以后得认真看description了。

//clever
function duplicateCount(text){
  return text.toLowerCase().split('').filter(function(val, i, arr){
    return arr.indexOf(val) !== i && arr.lastIndexOf(val) === i;
  }).length;
}
```



### 2018/07/10

##### who likes it?

- https://www.codewars.com/kata/5266876b8f4bf2da9b000362/solutions/javascript

```
// You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.

// Implement a function likes :: [String] -> String, which must take in input array, containing the names of people who like an item. It must return the display text as shown in the examples:
// 
// likes [] // must be "no one likes this"
// likes ["Peter"] // must be "Peter likes this"
// likes ["Jacob", "Alex"] // must be "Jacob and Alex like this"
// likes ["Max", "John", "Mark"] // must be "Max, John and Mark like this"
// likes ["Alex", "Jacob", "Mark", "Max"] // must be "Alex, Jacob and 2 others like this"

//MDN看了下template literals的tagged templates，想试下高级用法，发现更麻烦，switch只分4中情况，更简单
function likes(names){
  switch (names.length){
    case 0:
    return `no one likes this`
    case 1:
    return `${names[0]} likes this`
    case 2:
    return `${names[0]} and ${names[1]} like this`
    case 3:
    return `${names[0]}, ${names[1]} and ${names[2]} like this`
    default:
    return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`
  }
}


//function likes(names) {
//  function templ(str, names, len){
//    let like, comma, and, more
//    len > 1 ? like = 'like', and = 'and' : like = 'likes', and = ''
//    len > 2 ? comma = ',' : comma = ''
//    len > 3 ? more = '2 others'
//    return `${len >= 2
//    
//  }
//  return templ`${names}${names.length} this`
//}
```



##### Array.prototype.insert

- Chrome console支持，但是目前ES6不支持
- insert(val, index) => return 改变后的array

```
//自己写个polyfill
Array.prototype.insert = function(v, i){
  return Array.prototype.splice.call(this, i, 0, v)
}
```





##### Create Phone Number

- https://www.codewars.com/kata/525f50e3b73515a6db000b83/solutions/javascript/all/clever

```
// Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

// Example:
// createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"
// The returned format must be correct in order to complete this challenge. 
// Don't forget the space after the closing parentheses!

//spread真好用，不过感觉正则太强大了，查询替换的基本都能实现
function createPhoneNumber(numbers){
  return [...['('].concat(numbers.splice(0, 3).concat(') ')), ...numbers.splice(0, 3).concat('-'), ...numbers].join('')      
}

//clever with regexp
function createPhoneNumber(numbers){
  return numbers.join('').replace(/(...)(...)(.*)/, '($1) $2-$3');
}
```



##### TDD

- Test-Driven Development - 测试驱动开发
- https://coolshell.cn/articles/3649.html



##### Once

- https://www.codewars.com/kata/once/solutions?show-solutions=1

```
// You'll implement once, a function that takes another function as an argument, and returns a new version of that function that can only be called once.

// Subsequent calls to the resulting function should have no effect (and should return undefined).
// 
// For example:
// 
// logOnce = once(console.log)
// logOnce("foo") // -> "foo"
// logOnce("bar") // -> no effect

function once(fn){
  let called = false
  return function(){
    if(called) return
    called = true
    fn.apply(this, arguments)
  }
}

// clever
function once(fn) {
  return function() {
    try {
      return fn && fn.apply(this, arguments);
    } finally {
      fn = undefined;
    }
  };
}
```



##### Regex Password Validation

- https://www.codewars.com/kata/regex-password-validation/solutions/javascript

```
// You need to write regex that will validate a password to make sure it meets the following criteria:

// At least six characters long
// contains a lowercase letter
// contains an uppercase letter
// contains a number
// Valid passwords will only be alphanumeric characters.

function validate(password) {
  return  /^[A-Za-z0-9]{6,}$/.test(password) &&
          /[A-Z]+/           .test(password) &&
          /[a-z]+/           .test(password) &&
          /[0-9]+/           .test(password) ;
}

// clever
function validate(password) {
  return /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])[a-zA-Z0-9]{6,}$/.test(password);
}
```



##### persistent bugger

- https://www.codewars.com/kata/55bf01e5a717a0d57e0000ec/solutions/javascript

```
// Write a function, persistence, that takes in a positive parameter num and returns its multiplicative persistence, which is the number of times you must multiply the digits in num until you reach a single digit.

// For example:
// 
//  persistence(39) === 3 // because 3*9 = 27, 2*7 = 14, 1*4=4
//                        // and 4 has only one digit
// 
//  persistence(999) === 4 // because 9*9*9 = 729, 7*2*9 = 126,
//                         // 1*2*6 = 12, and finally 1*2 = 2
// 
//  persistence(4) === 0 // because 4 is already a one-digit number

//clever巧妙运用递归，再简单的题目总是有很灵巧的思维
function persistence(num) {
  let time = 0
  while(String(num).length > 1){
    num = String(num).split('').reduce( (a, c) => a * +c, 1)
    time++
  }
  return time
}

//clever
const persistence = num => {
  return `${num}`.length > 1 
    ? 1 + persistence(`${num}`.split('').reduce((a, b) => a * +b)) 
    : 0;
}
```

