划过岁月的沧桑,书香流年的旧梦

# 爱好
* Coding
* Reading {eg:《黑客与画家》or阮一峰的Blog:[🔗链接](http://www.ruanyifeng.com)}
* 桌游
* 网球🎾

# 学习经历

1.认识到命令行的重要性
   * 增 删 改 查
   * mkdir mv cd touch 
   * rm
   * cat echo cp mv 
   * ls head tail less pwd clear
   * 脚本文件Bash

2.学习Git本地仓库
   * git 六行配置
   * 'git init' 初始化
   * `git add .`
   * `git commit -v`
   * `it status`
   * `git log` / `git reflog`
   * `git branch` / `git checkout`
   
3.学习Git远程仓库
   * SSH Key 验证身份、如何生成SSH Key
   * 测试SSH Key是否配对成功 `ssh -T git@github.com`
   * git remote add origin git@XXXXXXX
   * git push -u origin master
   * `git pull` / `git push` / `git clone`
   * git高级操作
   * `git rebase --abort` / `git rebase --continue`
   * `git stash` / `git stash pop`

4.学习HTML
   * WWW=URL+HTTP+HTML
   * HTML语法、HTML标签
   * 标签的全局属性
   * HTML内容标签
   * a标签
   * form标签
   * input标签
   * table标签
   * 其他标签
   ```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>标题</title>
  </head>
  <body>
    <header>
      <div class="logo">logo</div>
      <nav>
        <ul>
          <li><a href="javascript:;">导航</a></li>
          <li><a href="javascript:;">导航</a></li>
          <li><a href="javascript:;">导航</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <p contenteditable>可编辑标签</p>
      <p hidden>隐藏的标签</p>
      <h1>标题</h1>
      <h2>标题</h2>
      <h3>标题</h3>
      <h4>标题</h4>
      <a href="#">链接</a>
      <p>内容</p>
      <input type="text" name="" id="" />
      <button>button的type=submit</button>
      <table>
        <caption>
          标题
        </caption>
        <tfoot>
          <tr>
            <td>表尾</td>
            <td>表尾</td>
          </tr>
        </tfoot>
        <thead>
          <tr>
            <th>表头</th>
            <th>表头</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>表格数据</td>
            <td>表格数据</td>
          </tr>
        </tbody>
      </table>
    </main>
    <footer>页尾</footer>
  </body>
</html>
   ```
   
5.学习CSS
```CSS
@charset "utf-8";
@namespace svg url(http://www.w3.org/2000/svg);

* {
  margin: 0;
  padding: 0;
}
*::after,
*::before {
  box-sizing: border-box;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: normal;
}
a {
  color: inherit;
  text-decoration: none;
}
ul,
ol {
  list-style: none;
}
pre {
  font: inherit;
}
table {
  border-collapse: collapse;
  border-spacing: 0; /*for ie*/
}
textarea {
  font: inherit;
  resize: none; /*no zooming*/
}

```
   * 进行中……

6.学习JavaScript
   * 进行中……
