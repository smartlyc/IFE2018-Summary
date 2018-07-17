### 日期，今天的学习总用时，今天学习的目标是什么，是否达成
20187.16-2018.7.17 两小时 目标完成第一天学习任务 达成
阅读资料：
[Web 建站技术中，HTML、HTML5、XHTML、CSS、SQL、JavaScript、PHP、ASP.NET、Web Services 是什么？](https://www.zhihu.com/question/22689579)
### 哪些东西今天了解得比较透彻，说说自己的理解

### 哪些东西今天了解到了一些，还有哪些点需要后续继续深入阅读

### 哪些东西今天学了之后还有很多疑问没有被解答，把问题记录下来，以待后续解决

### Code
#### 代码简洁：
保证body内内容尽可能少，将操作相关的代码放在js内，方便阅读。
原来：
```
  <button id="btn" onclick="btn()"></button>
  <script>
    function btn() {
      // 点按钮后弹出一个文字，你可以尝试改变文字内容
      alert("你好啊，欢迎来到百度前端技术学院");
    }
  </script>

```
现在：
```
  <button id="btn"></button>
  <script>
    document.getElementById("btn").onclick = function () {
      // 点按钮后弹出一个文字，你可以尝试改变文字内容
      alert("你好啊，欢迎来到百度前端技术学院");
    }
  </script>
```


