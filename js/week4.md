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
            <td>2023.01.03</td>
            <td>星期二</td>
            <td>
              <span>16:00-20:00</span>
            </td>
            <td>4h</td>
            <td>
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">事件绑定</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">冒泡与捕获</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">阻止默认事件</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">阻止冒泡</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">事件对象</a><br />
              <a href="https://github.com/lxmob/blog/blob/main/js%2B%2B/dom/dom.event.html">事件代理</a>
            </td>
            <td>100%/100%</td>
            <td>
              <span>1、dom事件绑定有三种形式，onclick优点兼容性好缺点无法绑定多个事件处理函数、addEventListener优点可以绑定多个事件处理函数缺点兼容性差IE9以下不支持、attachEvent是兼容IE8及以下的方法</span><br />
              <span>2、事件流的三个阶段：事件捕获、目标、事件冒泡，冒泡机制通过由内向外接收事件，捕获机制通过由外向内接收事件</span><br />
              <span>3、阻止冒泡事件触发e.stopPropagation和IE支持的e.cancelBubbling = true</span><br />
              <span>4、阻止默认事件：在句柄中使用的方式return false、w3c标准不兼容IE9及以下event.preventDefault、IE9以下使用event.returnValue = false</span><br />
              <span>5、事件对象通过发生的事件源来获取e.target、e.srcElement</span><br />
              <span>6、事件代理就是事件源通过冒泡的形式来触发祖父级身上绑定的相同事件处理函数</span>
            </td>
        </tr>
    </tbody>
</table>

## Learning details

- Total days: 1 d
- Total time: 4 h
- Issues list:
  - none
