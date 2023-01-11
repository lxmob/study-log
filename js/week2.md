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
            <td>2022.12.19</td>
            <td>星期一</td>
            <td>
              <span>12:30-14:00</span>
              <span>14:30-16:30</span>
              <span>17:30-19:00</span>
            </td>
            <td>5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/04_closure.html">闭包</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/05_IIFE.html">IIFE</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/03_js.syntax.html">逗号运算符</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/03_js.syntax.html">括号表达式</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、闭包形成的过程</span><br />
              <span>2、使用闭包改造立即执行函数</span><br />
              <span>3、逗号运算符的执行结果值</span><br />
              <span>4、重新认识括号表达式，括号表达式包裹函数时将忽略函数名</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.20</td>
            <td>星期二</td>
            <td>
              <span>14:00-18:00</span><br />
              <span>19:30-21:30</span>
            </td>
            <td>6h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/01_object.html">对象</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/01_object.html">构造函数</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/02_object.wrap.html">包装类</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/03_object.proto.html">原型</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、创建对象的方式</span><br />
              <span>2、构造函数创建对象默认return的是实例，如果指定return引用类型将覆盖默认返回值</span><br />
              <span>3、原始值没有自身的方法和属性，但是通过包装类可以实现，包装类包含三种Number、Boolean、String</span><br />
              <span>4、对象原型，通过构造函数创建对象身上会有一个__proto__属性指向它实例化时的prototype原型对象，原型对象身上有一个constructor属性指向的是构建时的构造函数</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.21</td>
            <td>星期三</td>
            <td>
              <span>10:00-11:30</span><br />
              <span>14:00-18:00</span><br />
              <span>20:30-23:30</span>
            </td>
            <td>8.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/03_object.proto.html">原型链</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/04_object.create.html">原型继承</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/11_pure.fn.html">纯函数</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/07_callback.html">回调函数</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/09_call.apply.bind.html">call/apply</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/05_object.proto.extend.grail.html">原型继承之圣杯模式</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、原型链是一个继承关系的链条，每个原型对象都有自己的原型 __proto__ 通过在原型对象身上查找属性和方法</span><br />
              <span>2、通过 Object.create 方法可以将一个原型对象作为参数创建实例的原型</span><br />
              <span>3、纯函数接收相同的输入产出相同的输出，不包含副作用</span><br />
              <span>4、回调函数作为参数传递的函数，可指定事件触发程序的绑定函数</span><br />
              <span>5、call和apply作为函数原型身上的方法，用来改变函数调用时的this指向</span><br />
              <span>6、原型继承之圣杯模式，通过作为中间件创建一个缓冲区域解决父子共用一个原型对象的问题</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.22</td>
            <td>星期四</td>
            <td>
              <span>10:00-12:00</span><br />
            </td>
            <td></td>
            <td>
              <a href="#"></a><br />
            </td>
            <td></td>
            <td>
              <span>忙工作，顺便整理笔记，回顾知识</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.23</td>
            <td>星期五</td>
            <td>
              <span>10:30-12:30</span><br />
              <span>14:00-18:30</span>
            </td>
            <td>6.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/07_hasOwnProperty.html">forin</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/06_instanceof.html">instanceof</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/base/06_global.this.html">this</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/10_arrow.fn.html">箭头函数</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/function/08_callee.caller.html">callee/caller</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、通过forin可以迭代对象身上可枚举的属性，包括继承的属性</span><br />
              <span>2、通过instanceof可以判断a对象是否在b构造函数的原型链上</span><br />
              <span>3、函数声明中的this指向的是window（非严格模式），对象中函数方法中的this指向的是该对象，构造函数中的this指向的是当前实例，iife中的this指向的是window（非严格模式）</span><br />
              <span>4、箭头函数中的this指向window，不具备原型对象不能够被new，没有arguments属性，箭头函数this是外部作用域的this指向</span><br />
              <span>5、arguments.callee指向就是函数本身，caller是谁调用该函数指向的就是调用者</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.24</td>
            <td>星期六</td>
            <td>
              <span>13:30-18:30</span>
            </td>
            <td>5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/09_object.clone.html">clone</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/object/09_object.clone.html">JSON序列化</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/array/02_method.change.html">array methods</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、对象拷贝，分为浅拷贝和深拷贝，浅拷贝拷贝引用类型时拷贝的只是引用地址，深拷贝可以拷贝多层引用类型嵌套的对象</span><br />
              <span>2、使用JSON序列化的形式也可以实现对象的深拷贝，但是不能拷贝方法、undefined、symbol类型，正则会转换成空对象</span><br />
              <span>3、数组增删改查的方法，改变数组类型的方法有push、pop、shift、unshift、splice、sort、reverse</span>
            </td>
        </tr>
    </tbody>
</table>

## Learning details

- Total days: 5 d
- Total time: 31 h
- Issues list:
  - none
