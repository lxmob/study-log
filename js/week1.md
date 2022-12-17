# JS Study Log

## Schedule

<table>
    <thead align="center">
        <tr>
            <th>Date</th>
            <th width="80">Week</th>
            <th width="120">Learning time</th>
            <th width="80">How long time to learn</th>
            <th width="140">Learn what keywords</th>
            <th width="80">Completion / Mastery</th>
            <th>What you learned</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>2022.12.15</td>
            <td>星期四</td>
            <td>
              <span>10:00-12:00</span>
              <span>14:00-15:30</span>
              <span>16:00-18:30</span>
            </td>
            <td>6h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/01_%E6%B5%8F%E8%A7%88%E5%99%A8%E5%8F%91%E5%B1%95%E5%8F%B2.md">浏览器发展史和内核</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/02_ECMA.md#ecma">ECMA</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/02_ECMA.md#js-%E5%BC%95%E6%93%8E">轮转时间片</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/03_%E5%8F%98%E9%87%8F%E5%92%8C%E5%80%BC.md#js-%E5%80%BC">变量堆栈</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/04_%E8%AF%AD%E6%B3%95%E8%A7%84%E8%8C%83.md">语法规范运算符</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、浏览器的历史发展过程</span><br />
              <span>2、五大主流浏览器的内核</span><br />
              <span>3、ecma组织标准</span><br />
              <span>4、编译型语言和解释型语言的区别</span><br />
              <span>5、js引擎是单线程，通过轮转时间片可以模拟多线程</span><br />
              <span>6、变量和基本数据类型引用数据类型，两者区别</span><br />
              <span>7、js语法规范运算符条件分支语句</span>
            </td>
        </tr>
         <tr>
            <td>2022.12.16</td>
            <td>星期五</td>
            <td>
              <span>14:00-17:30</span>
            </td>
            <td>3.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/05_%E5%BE%AA%E7%8E%AF%E3%80%81%E5%BC%95%E7%94%A8%E5%80%BC%E3%80%81%E6%98%BE%E9%9A%90%E8%BD%AC%E6%8D%A2.md#%E5%BE%AA%E7%8E%AF%E8%AF%AD%E5%8F%A5">循环语句</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/05_%E5%BE%AA%E7%8E%AF%E3%80%81%E5%BC%95%E7%94%A8%E5%80%BC%E3%80%81%E6%98%BE%E9%9A%90%E8%BD%AC%E6%8D%A2.md#%E6%98%BE%E9%9A%90%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2">显示类型和隐士类型转换</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、for循环求n的质数</span><br />
              <span>2、for循环求n的兔子数列</span><br />
              <span>3、for循环水仙花数</span><br />
              <span>4、for循环99乘法表</span><br />
              <span>5、显示类型转换和隐士类型转换</span>
            </td>
        </tr>
        <tr>
            <td>2022.12.17</td>
            <td>星期六</td>
            <td>
              <span>14:00-18:30</span>
            </td>
            <td>4.5h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/06_%E5%87%BD%E6%95%B0.md#%E5%87%BD%E6%95%B0">认识函数</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/06_%E5%87%BD%E6%95%B0.md#%E5%87%BD%E6%95%B0%E5%86%99%E6%B3%95">函数写法</a>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/06_%E5%87%BD%E6%95%B0.md#%E8%A1%8C%E5%8F%82%E5%92%8C%E5%AE%9E%E5%8F%82">函数行参和实参</a>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/06_%E5%87%BD%E6%95%B0.md#return">return关键字</a>
            </td>
            <td>100%/95%</td>
            <td>
              <span>1、函数用来封装一个固定功能的代码块或程序</span><br />
              <span>2、函数形参和实参的区别，堆栈内存以及映射关系，可通过arguments和函数名.length分别获取实参和形参列表</span><br />
              <span>3、使用函数实现一个数的阶乘</span><br />
              <span>4、使用函数实现接收一个n，算出斐波那契数列的第n位</span>
            </td>
        </tr>
    </tbody>
</table>

## Learning details

- Total days: 3 d
- Total time: 14 h
- Issues list:
  - for 循环不使用变量置换如何实现兔子数列？
  - 函数实现斐波那契数列为什么要用 (n-1)+(n-2) 的递归形式实现？
