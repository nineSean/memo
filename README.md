


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

```javascript

//check Array

function isArray(value){

	return typeof value === ‘object’ && value instaceof Array //用constructor来判断容易伪造

}

Array.isArray(value)

//check null

function isNull(value){

	return value === null

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

  ```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

  ```javascript
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

  ```javascript
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

  ```javascript
  function checkType(data){
    return Object.prototype.toString.call(data).match(/\b([a-z]+)\]/i)[1]
  }
  ```

##### Find the odd int

-   http://www.codewars.com/kata/54da5a58ea159efa38000836/solutions/javascript

  ```javascript
  // Given an array, find the int that appears an odd number of times.
  // There will always be only one integer that appears an odd number of times.

  // clever
  const findOdd = (xs) => xs.reduce((a, b) => a ^ b);
  ```

##### Sort the odd

-   http://www.codewars.com/kata/578aa45ee9fd15ff4600090d/solutions/javascript

  ```javascript
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

  ```javascript
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

  ```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
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

```javascript
//自己写个polyfill
Array.prototype.insert = function(v, i){
  return Array.prototype.splice.call(this, i, 0, v)
}
```



##### Create Phone Number

- https://www.codewars.com/kata/525f50e3b73515a6db000b83/solutions/javascript/all/clever

```javascript
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

```javascript
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

```javascript
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

```javascript
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



##### scrolling text

- https://www.codewars.com/kata/5a995c2aba1bb57f660001fd/solutions/javascript/all/clever

```javascript
// Let's create some scrolling text!

// Your task is to complete the function which takes a string, and returns an array with all possible rotations of the given string, in uppercase.
// 
// Example
// scrollingText("codewars") should return:
// 
// [ "CODEWARS",
//   "ODEWARSC",
//   "DEWARSCO",
//   "EWARSCOD",
//   "WARSCODE",
//   "ARSCODEW"
//   "RSCODEWA",
//   "SCODEWAR" ]

function scrollingText(text){
  let arr = []
  let n = 0
  text = text.toUpperCase()
  arr.push(text)
  while(n < text.length - 1){
    n++
    arr.push(text = text.replace(/^(.)(.*)$/, '$2$1'))
  }
  return arr
}

//clever
const scrollingText = s => [].map.call( s, (_,i) => ( s.slice(i) + s.slice(0,i) ).toUpperCase() )
```



##### Human Readable Time

- http://www.codewars.com/kata/52685f7382004e774f0001f7/solutions/javascript/all/clever

```javascript
// Write a function, which takes a non-negative integer (seconds) as input and returns the time in a human-readable format (HH:MM:SS)

// HH = hours, padded to 2 digits, range: 00 - 99
// MM = minutes, padded to 2 digits, range: 00 - 59
// SS = seconds, padded to 2 digits, range: 00 - 59
// The maximum time never exceeds 359999 (99:59:59)

function humanReadable(seconds) {
  function leftPad(n){
	return `0${n | 0}`.slice(-2)
  }
  let hours = parseInt(seconds / 3600)
  let minutes = parseInt( seconds / 60 % 60) 
  seconds = seconds % 60
  return `${leftPad(hours)}:${leftPad(minutes)}:${leftPad(seconds)}`
}

//clever
p=n=>`0${n}`.slice(-2),humanReadable=(s)=>(m=s/60|0,p(m/60|0)+':'+p(m%60)+':'+p(s%60))
```



##### Get the Middle Character

- https://www.codewars.com/kata/56747fd5cb988479af000028/solutions/javascript

```javascript
// You are going to be given a word. Your job is to return the middle character of the word. If the word's length is odd, return the middle character. If the word's length is even, return the middle 2 characters.

// #Examples:
// 
// Kata.getMiddle("test") should return "es"
// 
// Kata.getMiddle("testing") should return "t"
// 
// Kata.getMiddle("middle") should return "dd"
// 
// Kata.getMiddle("A") should return "A"
// #Input
// 
// A word (string) of length 0 < str < 1000 (In javascript you may get slightly more than 1000 in some test cases due to an error in the test cases). You do not need to test for this. This is only here to tell you that you do not need to worry about your solution timing out.
// 
// #Output

// The middle character(s) of the word represented as a string.

function getMiddle(s)
{
  return s.substr(Math.ceil(s.length / 2 - 1), s.length % 2 === 0 ? 2 : 1);
}
```



##### Unique In Order

- https://www.codewars.com/kata/54e6533c92449cc251001667/solutions/javascript

```javascript
// Implement the function unique_in_order which takes as argument a sequence and returns a list of items without any elements with the same value next to each other and preserving the original order of elements.

// For example:
// 
// uniqueInOrder('AAAABBBCCDAABBB') == ['A', 'B', 'C', 'D', 'A', 'B']
// uniqueInOrder('ABBCcAD')         == ['A', 'B', 'C', 'c', 'A', 'D']
// uniqueInOrder([1,2,2,3,3])       == [1,2,3]


// with regexp
// 有个不严谨的地方，或者说特殊情况，array里包含相邻且不严格相等的字符串和数字(而且array有类似'1'与2同时出现时区别处理也很麻烦)。不过考虑到真实情况在收集的同一个array里数据，各项值的类型应该是一样的。
var uniqueInOrder=function(iterable){
  let str = Array.from(iterable).join('')
  let arr = str.replace(/(\S)\1+/g, '$1').split('')
  return arr.map(v => isNaN(+v) ? v : +v)
}

//clever
var uniqueInOrder = function (iterable)
{
  return [].filter.call(iterable, (function (a, i) { return iterable[i - 1] !== a }));
}
```



##### array.diff

- https://www.codewars.com/kata/523f5d21c841566fde000009/solutions/javascript

```javascript
// Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result.

// It should remove all values from list a, which are present in list b.
// 
// array_diff([1,2],[1]) == [2]
// If a value is present in b, all of its occurrences must be removed from the other:

array_diff([1,2,2,2,3],[2]) == [1,3]

// 刚开始会错意，以为a、b先diff，然后再concat，测试报错发现b只是用来diff的。
function array_diff(a, b) {
  let aStr = a.join(' ')
  b.map(v => aStr = aStr.replace(new RegExp(v , 'g'), ''))
  return aStr.split(' ').filter(v => v === '' ? false : true)
}

// with Set
function array_diff(a, b) {
  b = new Set(b)
  return a.filter(v => !b.has(v))
}

// clever
function array_diff(a, b) {
  return a.filter(function(x) { return b.indexOf(x) == -1; });
}
```



##### is it a number?

- https://www.codewars.com/kata/57126304cdbf63c6770012bd/solutions/javascript/all/clever

```javascript
// Given a string s, write a method (function) that will return true if its a valid single integer or floating number or false if its not.

// Valid examples, should return true:
// 
// isDigit("3")
// isDigit("  3  ")
// isDigit("-3.23")
// should return false:
// 
// isDigit("3-4")
// isDigit("  3   5")
// isDigit("3 5")
// isDigit("zero")

function isDigit(s) {
  return !isNaN(+s) && typeof +s === 'number' && !s.match(/^\s*$/g)                
}

// clever
function isDigit(s) {
 return s==parseFloat(s);
}

const isDigit = str => !!str.trim() && !isNaN(str)

function isDigit(s) {
console.log(s);
 return /(^(\-|\s)[0-9]{1,}$)|(^[0-9]{1,}\.[0-9]{1,}$)|(^\-[0-9]{1,}\.[0-9]{1,}$)/g.test(s)&&s!==-0;
}

// 先存后看
class Tokenizer {
  constructor(string) {
    this.str = string.trim();
  }

  isNumber() {
    const iterator = this[Symbol.iterator]();
    let dotFlag = false;
    let beginFlag = false;
    let tmp;
    if(Tokenizer.isPrefix(iterator.next().value)) {
      beginFlag = true;
      iterator.next('next');
    }
    while(!(tmp = iterator.next()).done) {
      const value = tmp.value;
      if(Tokenizer.isDot(value) && !dotFlag && beginFlag) {
        iterator.next('next');
        dotFlag = true;
      }
      else if(Tokenizer.isDigit(value)) {
        iterator.next('next');
        beginFlag = true;
      }
      else return false;
    }
    return this.str.length > 0;
  }

  * [Symbol.iterator]() {
    const string = this.str;
    let ptr = 0;

    while(ptr < string.length) {
      const readingType = yield string[ptr];
      if(readingType === 'next')
        ptr += 1;
    }
  }

  static isDot(char) {
    const checker = /\./;
    return checker.test(char);
  }

  static isPrefix(char) {
    const checker = /[-|\+]/;
    return checker.test(char);
  }

  static isDigit(char) {
    const checker = /\d/; // useless ^, $
    return checker.test(char);
  }
}

function isDigit(s) {
  const checker = new Tokenizer(s);
  return checker.isNumber();
}
```

 

### 2018/07/11

##### Visualizing  js runtime

- http://latentflip.com/loupe

##### Asynchrony: Under the Hood

- https://www.youtube.com/watch?v=SrNQS8J67zc

  - <img src='./img/async-mechanism.png' alt='async-mechanism' />

  - **current task** come off **event queue** and it’s location is stored in **memory** while relevant variables populate the **heap**

  - the **task queue** is populated by **task sources**, any one of which would be a particular chunk of code in an executing program

  - callback

    - 适合简单处理单个异步请求
    - 函数套函数的写法不直观，代码可读性太差
    - 多层嵌套而引发的回调地狱
    - 控制反转引发信任问题

  - promises

    - 异步处理的一种新的机制

    - 链式处理异步，线性、直观

    - 错误处理不够优雅，无法通过try catch捕捉错误，同步异步错误传播要分开捕获（与下面async比较）

      ```javascript
      const asyncFunction = () => {
        try{
          doSynchronousThings()
          return getSomeData()
          	.then(data => data.map(item => item.doSomething()))
          	.catch(e => console.error(e))
        }catch(err){
          console.error(err)
        }
      }
      ```

      ​

  - generators

    - `*`语法
    - 生成器返回可迭代对象
    - 可迭代对象通过`.next`获取`yield`出来的值
    - ​

  - async/await

    - 更简洁的异步处理方式

    - await calls operate sequentially（异步操作有序化）

    - 更优雅的错误处理try catch（与上promises比较）

      ```javascript
      const asyncFunction = async () => {
        try{
          doSynchronousThings()
          const data = await getSomeData()
          return data.map(item => item.doSomeThing())
        }catch(err){
          console.error(err)
        }
      }
      ```

      ​


##### directions reduction

- https://www.codewars.com/kata/directions-reduction/solutions/javascript

```javascript
// Once upon a time, on a way through the old wild west,…
… a man was given directions to go from one point to another. The directions were "NORTH", "SOUTH", "WEST", "EAST". Clearly "NORTH" and "SOUTH" are opposite, "WEST" and "EAST" too. Going to one direction and coming back the opposite direction is a needless effort. Since this is the wild west, with dreadfull weather and not much water, it's important to save yourself some energy, otherwise you might die of thirst!

// How I crossed the desert the smart way.
// The directions given to the man are, for example, the following:
// 
// ["NORTH", "SOUTH", "SOUTH", "EAST", "WEST", "NORTH", "WEST"].
// or
// 
// { "NORTH", "SOUTH", "SOUTH", "EAST", "WEST", "NORTH", "WEST" };
// or (haskell)
// 
// [North, South, South, East, West, North, West]
// You can immediatly see that going "NORTH" and then "SOUTH" is not reasonable, better stay to the same place! So the task is to give to the man a simplified version of the plan. A better plan in this case is simply:
// 
// ["WEST"]
// or
// 
// { "WEST" }
// or (haskell)
// 
// [West]
// or (rust)

// [WEST];
// Other examples:
// In ["NORTH", "SOUTH", "EAST", "WEST"], the direction "NORTH" + "SOUTH" is going north and coming back right away. What a waste of time! Better to do nothing.
// 
// The path becomes ["EAST", "WEST"], now "EAST" and "WEST" annihilate each other, therefore, the final result is [] (nil in Clojure).
// 
// In ["NORTH", "EAST", "WEST", "SOUTH", "WEST", "WEST"], "NORTH" and "SOUTH" are not directly opposite but they become directly opposite after the reduction of "EAST" and "WEST" so the whole path is reducible to ["WEST", "WEST"].
// 
// Task
// Write a function dirReduc which will take an array of strings and returns an array of strings with the needless directions removed (W<->E or S<->N side by side).
// 
// The Haskell version takes a list of directions with data Direction = North | East | West | South. The Clojure version returns nil when the path is reduced to nothing. The Rust version takes a slice of enum Direction {NORTH, SOUTH, EAST, WEST}.
// 
// Examples
// dirReduc(["NORTH", "SOUTH", "SOUTH", "EAST", "WEST", "NORTH", "WEST"]) => ["WEST"]
// dirReduc(["NORTH", "SOUTH", "SOUTH", "EAST", "WEST", "NORTH"]) => []
// See more examples in "Example Tests"
// Note
// Not all paths can be made simpler. The path ["NORTH", "WEST", "SOUTH", "EAST"] is not reducible. "NORTH" and "WEST", "WEST" and "SOUTH", "SOUTH" and "EAST" are not directly opposite of each other and can't become such. Hence the result path is itself : ["NORTH", "WEST", "SOUTH", "EAST"].

//用了递归，性能不佳
function dirReduc(arr){
  let len = arr.length
  let rule = {
    'NORTH': 'SOUTH',
    'SOUTH': 'NORTH',
    'WEST': 'EAST',
    'EAST': 'WEST'
  }
  for(let i = 0; i < arr.length; i++){
    rule[arr[i]] === arr[i+1] ? (arr.splice(i, 2), i--) : arr
  }
  return len !== arr.length ? dirReduc(arr) : arr
}

//clever with regexp
function dirReduc(arr) {
  var str = arr.join(''), pattern = /NORTHSOUTH|EASTWEST|SOUTHNORTH|WESTEAST/;
  while (pattern.test(str)) str = str.replace(pattern,'');
  return str.match(/(NORTH|SOUTH|EAST|WEST)/g)||[];
}

//clever reduce新建一个dirs数组，始终用dirs的最后一项按照规则比较plan每一项然后确定添加方向或者删除方向。
function dirReduc(plan) {
  var opposite = {
    'NORTH': 'SOUTH', 'EAST': 'WEST', 'SOUTH': 'NORTH', 'WEST': 'EAST'};
  return plan.reduce(function(dirs, dir){
      if (dirs[dirs.length - 1] === opposite[dir])
        dirs.pop();
      else
        dirs.push(dir);
      return dirs;
    }, []);
}
```



### 2018/07/12

##### 闭包

- Ecam-262标准中没有closure（闭包）的定义，因为闭包是计算机语言的一种特性吧，见维基百科


- MDN：A *closure* is the combination of a function and the lexical environment within which that function was declared
- WIKIPEDIA：In [programming languages](https://en.wikipedia.org/wiki/Programming_language), a **closure** (also **lexical closure** or **function closure**) is a technique for implementing [lexically scoped](https://en.wikipedia.org/wiki/Lexically_scoped) [name binding](https://en.wikipedia.org/wiki/Name_binding) in a language with [first-class functions](https://en.wikipedia.org/wiki/First-class_function). [Operationally](https://en.wikipedia.org/wiki/Operational_semantics), a closure is a [record](https://en.wikipedia.org/wiki/Record_(computer_science)) storing a [function](https://en.wikipedia.org/wiki/Function_(computer_science))[[a\]](https://en.wikipedia.org/wiki/Closure_(computer_programming)#cite_note-1) together with an environment.[[1\]](https://en.wikipedia.org/wiki/Closure_(computer_programming)#cite_note-2) The environment is a mapping associating each [free variable](https://en.wikipedia.org/wiki/Free_variable) of the function (variables that are used locally, but defined in an enclosing scope) with the [value](https://en.wikipedia.org/wiki/Value_(computer_science)) or [reference](https://en.wikipedia.org/wiki/Reference_(computer_science)) to which the name was bound when the closure was created.[[b\]](https://en.wikipedia.org/wiki/Closure_(computer_programming)#cite_note-3) A closure—unlike a plain function—allows the function to access those *captured variables* through the closure's copies of their values or references, even when the function is invoked outside their scope.
- EcmaScript 2015 - lexical environment


- 广义的闭包：函数与它的词法作用域
  - 所以任何函数都是一个闭包
  - 发想：只要在栈中/队列中的函数，它的词法环境就得保存，那么整条词法作用域链就得保存（GC如果清除链上任何一环的上下文变量，由于JS编译执行的特性只有当队列中的函数入栈时才会分析该函数上下文中变量有哪些引用，所以得保存整条作用域链的完整）
- 狭义的闭包（实际使用）
  - 函数在它声明的作用域外调用，且函数内部有外部变量的访问且是调用环境无法访问的变量
  - 原理：词法作用域
  - 目的：隐藏变量
  - 用途：模块化
- https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch5.md
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
- [closure wikipedia](https://en.wikipedia.org/wiki/Closure_(computer_programming))




##### 动态作用域

- 在函数调用时确定上下文，区别于在函数声明时确定上下文（词法作用域）
- this就是动态作用域的应用(非箭头函数中的this)

##### Maximum subarray sum

- https://www.codewars.com/kata/maximum-subarray-sum/solutions/javascript/all/clever
- https://en.wikipedia.org/wiki/Maximum_subarray_problem

```Javascript
// The maximum sum subarray problem consists in finding the maximum sum of a contiguous subsequence in an array or list of integers:

// maxSequence([-2, 1, -3, 4, -1, 2, 1, -5, 4])
// // should be 6: [4, -1, 2, 1]
// Easy case is when the list is made up of only positive numbers and the maximum sum is the sum of the whole array. If the list is made up of only negative numbers, return 0 instead.
// 
// Empty list is considered to have zero greatest sum. Note that the empty list or array is also a valid sublist/subarray.

// 看到题目觉得不可能对比所有和取最大吧？完全没有实现思路，心想：真好，能学到更多了。转换心态，不再纠结自己有多菜而自怨自艾，而在乎在旅途中获取更多

// clever
var maxSequence = function(arr){
  var min = 0, ans = 0, i, sum = 0;
  for (i = 0; i < arr.length; ++i) {
    sum += arr[i];
    min = Math.min(sum, min);
    ans = Math.max(ans, sum - min);
  }
  return ans;
}
// explanation
// Let's image a broken line chart presenting the sum.
// 
// http://i.imgur.com/HnEEx0Q.png
// 
// You could try climbing from most bottom valley to the most top peak.
// 
// The difference between them is the answer we want.
// 
// At the first glance, you may want to pick the most top and most bottom point to get the answer.
// 
// But you will notice the answer is wrong when the most bottom point come after the most top point.
// 
// As a result. 
// I'll try to keep the most bottom point so far,
// //min = Math.min(sum, min);
// and update the answer if the new difference is bigger than origin answer.
// //ans = Math.max(ans, sum - min);

var maxSequence = function(arr){
    var maxNow = 0, maxSoFar = 0;
    for(i = 0; i < arr.length; i++){
        //If adding the new number to our list
        //causes us to go negative, start over with 0
        maxSoFar = Math.max(0, maxSoFar + arr[i]);
        //Compare our new max, to our old and
        //assign highest value to our max holder
        maxNow = Math.max(maxSoFar, maxNow);
    }
    return maxNow;
}

const maxSequence = (a,sum=0) => a.reduce((max,v) => Math.max(sum = Math.max(sum + v, 0), max), 0);

```



### 2018/07/13

##### bind polyfill

```Javascript
if (!Function.prototype.bind) {
	Function.prototype.bind = function(oThis) {
		if (typeof this !== "function") {
			// closest thing possible to the ECMAScript 5
			// internal IsCallable function
			throw new TypeError( "Function.prototype.bind - what " +
				"is trying to be bound is not callable"
			);
		}

		var aArgs = Array.prototype.slice.call( arguments, 1 ),
			fToBind = this,
			fNOP = function(){},
			fBound = function(){
				return fToBind.apply(
					(
						this instanceof fNOP &&
						oThis ? this : oThis
					),
					aArgs.concat( Array.prototype.slice.call( arguments ) )
				);
			}
		;

		fNOP.prototype = this.prototype;
		fBound.prototype = new fNOP();

		return fBound;
	};
}
```



##### 软绑定

- https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch2.md

```Javascript
if (!Function.prototype.softBind) {
	Function.prototype.softBind = function(obj) {
		var fn = this,
			curried = [].slice.call( arguments, 1 ),
			bound = function bound() {
				return fn.apply(
					(!this ||
						(typeof window !== "undefined" &&
							this === window) ||
						(typeof global !== "undefined" &&
							this === global)
					) ? obj : this,
					curried.concat.apply( curried, arguments )
				);
			};
		bound.prototype = Object.create( fn.prototype );
		return bound;
	};
}

function foo() {
   console.log("name: " + this.name);
}

var obj = { name: "obj" },
    obj2 = { name: "obj2" },
    obj3 = { name: "obj3" };

var fooOBJ = foo.softBind( obj );

fooOBJ(); // name: obj

obj2.foo = foo.softBind(obj);
obj2.foo(); // name: obj2   <---- look!!!

fooOBJ.call( obj3 ); // name: obj3   <---- look!

setTimeout( obj2.foo, 10 ); // name: obj   <---- falls back to soft-binding
```



##### RPC



##### 红黑树



##### Behavior Delegation



##### OLOO(Objects Linked to Other Objects)



### 2018/07/14

##### 一刷《你不知道的javascript（上卷）》

- https://github.com/getify/You-Dont-Know-JS

##### OOP VS OLOO



##### class带来的隐患



##### JSON.stringify(target, replacer)



##### document.all

- 作为假值对象 — falsy value
- 老版本IE为真值对象，故用以区分







