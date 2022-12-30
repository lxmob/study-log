# JS Study Log

## Schedule

<table>
    <thead align="center">
        <tr>
            <th>Date</th>
            <th width="80">Week</th>
            <th width="130">Learning time</th>
            <th width="80">How long time to learn</th>
            <th width="140">Learn what keywords</th>
            <th width="80">Completion / Mastery</th>
            <th>What you learned</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>2022.12.26</td>
            <td>星期一</td>
            <td>
              <span>19:30-21:00</span><br />
              <span>21:30-22:30</span>
            </td>
            <td>2.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/array/class.array.html">类数组</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/typeof.html">typeof增强实现</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、自定义类数组对象即可以是对象也可以是数组，通过继承数组原型对象上的方法，添加类数组对象length属性和对应下标属性</span><br />
              <span>2、常见的类数组有arguments，dom元素列表</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.27</td>
            <td>星期二</td>
            <td>
              <span>09:30-11:30</span><br />
              <span>14:00-16:30</span>
            </td>
            <td>4.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/array/array.unique.html">数组unique</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/js.syntax.error.html">Error类型</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/ECMA.html">严格模式</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/js.gc.html">JSGC</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、数组去重多种方式：for循环结合splice方法实现、使用对象属性不重复的特性结合hasOwnProperty方法实现、es6的Set数据集合实现</span><br />
              <span>2、js错误类型分为6种：引用错误、类型错误、取值范围错误、语法错误、uri解析错误、eval错误</span><br />
              <span>3、使用try catch语法可以捕获代码块内发生的错误，throw关键字来抛出错误</span><br />
              <span>4、严格模式下不能使用 with 表达式、arguments.callee、函数名.caller、函数内this指向undefined，函数参数不能重复、声明变量必须使用var关键字、eval作用域声明的变量严格模式下无法访问</span><br />
              <span>5、js垃圾回收机制分为两种方式，标记清除和引用计数，大多浏览器采用标记清除的方式，低版本ie6使用引用计数形式，引用计数方式会导致循环引用问题使变量无法被释放，导致内存泄露</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.28</td>
            <td>星期三</td>
            <td>
              <span>14:00-18:00</span>
            </td>
            <td>4h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/array/array.unique.html">数组flatten</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.html">dom初识</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.selector.html">dom元素选择器</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/js.gc.html">dom操作节点树属性和方法</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、js中的三种对象包含本地对象、内置对象、宿主对象</span><br />
              <span>2、dom是通过浏览器提供的一套方法表示或操作HTML和XML，它无法操作css样式，能改变元素的样式，是因为操作的是元素节点的属性style</span><br />
              <span>3、获取元素节点的方法包含get*一系列的方法还有html5新引入的web-api（querySelector、querySelectorAll）</span><br />
              <span>4、h5新引入的api相比较于get系列的优点是能够通过css选择器来获取对应的元素节点，缺点是性能差，不具备实时性存储的只是一块片段</span><br />
              <span>5、节点不等于元素，节点中包含元素节点，节点包含（元素、属性、文本、注释、document、fragement）</span>
            </td>
        </tr>
         <tr>
            <td>2022.12.29</td>
            <td>星期四</td>
            <td>
              <span>14:00-18:00</span>
            </td>
            <td>4h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.proto.html">dom结构树</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.operation.node.html">dom操作节点</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.operation.attr.html">dom属性</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/js.gc.html">dom操作节点树属性和方法</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.fragment.html">fragment文档碎片</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、dom结构树中存在多个构造函数，每个构造函数创建各个dom元素节点，通过原型链链接各个节点，最终都继承于Object.prototype</span><br />
              <span>2、getElementById和getElementsByName特殊的方法，仅存在于Document.prototype身上</span><br />
              <span>3、appendChild的特殊性，能够动态增加和剪切元素节点</span><br />
              <span>4、removeChild的特殊性，删除的是当前的节点，而内存中的dom对象将保留，如果想彻底删除通过调用元素身上remove方法释放内存</span><br />
              <span>5、HTML5给元素新增的自定义属性data-*属性，保存在当前元素节点下dataset对象中</span><br />
              <span>6、文档碎片它的创建不存在dom节点树当中，暂存于内存当中，通过它可以解决回流的问题提升性能</span>
            </td>
        </tr>
         <tr>
            <td>2022.12.30</td>
            <td>星期五</td>
            <td>
              <span>09:30-10:30</span><br />
              <span>14:00-17:00</span>
            </td>
            <td>4.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/other/date.html">Date</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/other/math.html">Math</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/other/settimeout.html">定时器</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、Date日期对象，实现电子时钟和倒计时功能</span><br />
              <span>2、getDay返回的是星期几（0-6的范围）getMonth返回的月份（0-11的范围）getYear会导致计算机千年虫的问题</span><br />
              <span>3、Math.round四舍五入方法（并非数学上的四舍五入，不精确）Math.ceil和Math.floor向上和向下取整</span><br />
              <span>4、setTimeout定时器和setInterval计时器，指定未来某段时间触发事件或循环触发事件，返回值是唯一标识id，通过clearTimeout或者clearInterval可以根据唯一标识id清除定时器</span>
            </td>
        </tr>
    </tbody>
</table>

## Learning details

- Total days: 5 d
- Total time: 19.5 h
- Issues list:
  - none
