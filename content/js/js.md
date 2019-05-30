# [返回主页](../../README.md)

<b><details><summary>1. JavaScript 中如何检测一个变量是一个 String 类型？请写出函数实现</summary></b>

typeof(obj) === "string"
typeof obj === "string"
obj.constructor === String

</details>

<b><details><summary>2.请用 js 去除字符串空格？</summary></b>

方法一：使用 replace 正则匹配的方法
方法二：使用 str.trim()方法
方法三：使用 jquery,\$.trim(str)方法

</details>

<b><details><summary>4.怎样添加、移除、移动、复制、创建和查找节点？</summary></b>

1）创建新节点

createDocumentFragment() //创建一个 DOM 片段
　　 createElement() //创建一个具体的元素
　　 createTextNode() //创建一个文本节点

2）添加、移除、替换、插入
　　 appendChild() //添加
　　 removeChild() //移除
　　 replaceChild() //替换
　　 insertBefore() //插入

3）查找
　　 getElementsByTagName() //通过标签名称
　　 getElementsByName() //通过元素的 Name 属性的值
　　 getElementById() //通过元素 Id，唯一性

</details>

<b><details><summary>5.事件委托是什么</summary></b>

让利用事件冒泡的原理，让自己的所触发的事件，让他的父元素代替执行！

<summary>阻止事件冒泡</summary>
  event.stopPropagation() || e.cancelBubble = true || return false

</details>

<b><details><summary>6.你对闭包的理解？</summary></b> 1.闭包就是能够读取其他函数内部变量的函数。由于在 ECMA2015 中，只有函数才能分割作用域，函数内部可以访问当前作用域的变量，但是外部无法访问函数内部的变量，所以闭包可以理解成“定义在一个函数内部的函数，外部可以通过内部返回的函数访问内部函数的变量“。在本质上，闭包是将函数内部和函数外部连接起来的桥梁。

</details>

<b><details><summary>7.require 与 import 的区别</summary></b>

第一、两者的加载方式不同，require 是在运行时加载，而 import 是在编译时加载

require('./a')(); // a 模块是一个函数，立即执行 a 模块函数

var data = require('./a').data; // a 模块导出的是一个对象

var a = require('./a')[0]; // a 模块导出的是一个数组 ======> 哪都行

import \$ from 'jquery';

import \* as _ from '_';

import {a,b,c} from './a';

import {default as alias, a as a_a, b, c} from './a'; ======>用在开头

第二、规范不同，require 是 CommonJS/AMD 规范，import 是 ESMAScript6+规范

第三、require 特点：社区方案，提供了服务器/浏览器的模块加载方案。非语言层面的标准。只能在运行时确定模块的依赖关系及输入/输出的变量，无法进行静态优化。

import 特点：语言规格层面支持模块功能。支持编译时静态分析，便于 JS 引入宏和类型检验。动态绑定。

</details>

<b><details><summary>8.javascript 对象的几种创建方式</summary></b>

1，工厂模式

2，构造函数模式

3，原型模式

4，混合构造函数和原型模式

5，动态原型模式

6，寄生构造函数模式

7，稳妥构造函数模式

</details>

<b><details><summary>9.javascript 继承的 6 种方法</summary></b>

1，原型链继承

2，借用构造函数继承

3，组合继承(原型+借用构造)

4，原型式继承

5，寄生式继承

6，寄生组合式继承

详情：JavaScript 继承方式详解

</details>

<b><details><summary>13.变量提升</summary></b>

[变量提升概念]()
[变量提升面试题]()

</details>

<b><details><summary>14.this 和 apply 的应用</summary></b>

</details>

<b><details><summary>15.sort 排序原理</summary></b>

</details>

<b><details><summary>16. jsonp 优缺点？ 事件委托怎么取索引</summary></b>

</details>

<b><details><summary>17.如何判断 NaN</summary></b>

</details>

<b><details><summary>18. null/undefined 的区别</summary></b>

</details>

<b><details><summary>20. 如何判断 JS 变量的一个类型（至少三种方式）</summary></b>

</details>

<b><details><summary>21. for/in、Object.keys 和 Object.getOwnPropertyNames 对属性遍历有什么区别？</summary></b>

</details>

<b><details><summary>22.在子 iframe 中调用外层页面的接口，传入一个对象，外层页面如何判断该对象是否为数组？</summary></b>

</details>

<b><details><summary>23.请简要描述 webview 中通过 js bridge 和 native 通信的技术实现</summary></b>

</details>

<b><details><summary>24.如何判断一个对象是否为数组</summary></b>

</details>

<b><details><summary>25.`<script>` 标签的 defer 和 asnyc 属性的作用以及二者的区别？</summary></b>

</details>

<b><details><summary>26.Object.prototype.toString.call() 和 instanceOf 和 Array.isArray() 区别好坏</summary></b>

</details>

<b><details><summary>27.ES6 都有什么 iterater 遍历器</summary></b>

</details>

</details>

<b><details><summary>28.松散类型的数组</summary></b>

</details>

<b><details><summary>29.JS 严格模式和正常模式</summary></b>

</details>

<b><details><summary>30.移动端 tap 点击事件和 click 的区别</summary></b>

</details>

<b><details><summary>31.JS 单线程还是多线程，如何显示异步操作</summary></b>

</details>

</details>

<b><details><summary>32. JavaScript 数组的函数 map/forEach/reduce/filter</summary></b>

</details>

<b><details><summary>33. JS 块级作用域、变量提升</summary></b>

</details>

<b><details><summary>35. JS 哪些操作会造成内存泄露</summary></b>

</details>

</details>

<b><details><summary>36.重排与重绘的区别，什么情况下会触发？</summary></b>

</details>

<b><details><summary>37.发布订阅设计模式</summary></b>

</details>

<b><details><summary>38.防抖，节流</summary></b>

</details>

<b><details><summary>39.兼容各种浏览器版本的事件绑定</summary></b>

</details>

</details>

<b><details><summary>40.typescript 遇到过什么坑</summary></b>

</details>

<b><details><summary>ES6 的动态加载，如何动态 import</summary></b>

</details>

<b><details><summary>JavaScript 的基本数据类型</summary></b>

</details>

<b><details><summary>如何判断一个对象是否属于某个类？</summary></b>

</details>

<b><details><summary>new 操作符具体干了什么呢?</summary></b>

</details>

<b><details><summary>.call() 和 .apply() 的含义和区别？</summary></b>

</details>

<b><details><summary>那些操作会造成内存泄漏？</summary></b>

</details>

<b><details><summary>Zepto 的点透问题如何解决？</summary></b>

</details>

<b><details><summary>如何判断当前脚本运行在浏览器还是 node 环境中？</summary></b>

</details>

<b><details><summary>移动端最小触控区域是多大？</summary></b>

</details>

<b><details><summary>移动端的点击事件的有延迟，时间是多久，为什么会有？ 怎么解决这个延时？</summary></b>

</details>

<b><details><summary>解释 JavaScript 中的作用域与变量声明提升？</summary></b>

</details>

<b><details><summary>Node.js 的适用场景？</summary></b>

</details>

<b><details><summary>什么是“前端路由”?什么时候适合使用“前端路由”? “前端路由”有哪些优点和缺点?</summary></b>

</details>

<b><details><summary>使用构造函数的注意点</summary></b>

    *  1 一般情况下构造函数的首字母需要大写，因为我们在看到一个函数首字母
    *  大写的情况，就认定这是一个构造函数，需要跟new关键字进行搭配使用，创建一个新的
    *  实例（对象）
    *  2 构造函数在被调用的时候需要跟new关键字搭配使用。
    *  3 在构造函数内部通过this+属性名的形式为实例添加一些属性和方法。
    *  4 构造函数一般不需要返回值，如果有返回值
    *  4.1 如果返回值是一个基本数据类型，那么调用构造函数，返回值仍旧是那么创建出来的
    *  对象。
    *  4.2 如果返回值是一个复杂数据类型，那么调用构造函数的时候，返回值就是这个return之后的
    *  那个复杂数据类型。

</details>

<b><details><summary>如何获取浏览器版本信息</summary></b>

window.navigator.userAgent

</details>

<b><details><summary>调试工具的使用</summary></b>

调试模式中的按钮作用
F8 跳出断点调试模式
F10、F11 代码的逐行调试

进入断点调试模式的 方法
1 在浏览器当中打断点

2 直接在代码中加 debugger

</details>

<b><details><summary>如何解决数组塌陷问题</summary></b>

```

    // 1 使用i--
    for(var i=0;i<arr.length;i++){
        if(arr[i]===4){
            arr.splice(i,1);
            i--;
        }
    }
    console.log(arr)

    // 2 从数组的末尾一项开始遍历
    for(var i =arr.length;i>=0;i--){
        if(arr[i]===4){
            arr.splice(i,1);
        }
    }
    console.log(arr)

```

</details>

<b><details><summary>数组的常用方法</summary></b>

</details>

<b><details><summary>字符串常用操作</summary></b>

</details>

<b><details><summary></summary></b>

</details>

<b><details><summary></summary></b>

</details>

<b><details><summary></summary></b>

</details>

<b><details><summary></summary></b>

</details>