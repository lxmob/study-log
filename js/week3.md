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
    </tbody>
</table>

## Learning details

- Total days: 3 d
- Total time: 11 h
- Issues list:
  - none
