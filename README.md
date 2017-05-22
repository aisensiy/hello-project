这是一个用于演示 Real Topper Project Based Learning 的项目。这个项目要求创建一个基本的 HTML 网页。

# 前提

想要完成这个项目，你需要知道一个基本的 HTML 语法：

* 知道什么是 HTML 标签
* 知道一些基本的标签，比如 `title` `h1` `ul` `li`

并且，你需要知道一些 `git` 的基本使用方式：

* 知道如何 `clone` 远端的 `git` 仓库
* 知道如何将添加或者修改后的文件提交到本地 `git` 仓库
* 知道如何将本地的仓库提交到远端的仓库

还有，你可能需要知道一些 `nodejs` 以及 `npm` 的知识，**不过在目前这个项目，这些不是必须的**：

* 知道什么是 `nodejs`
* 知道如何利用 `npm` 对 HTML Javascript 的项目进行依赖管理


这里所需要你学习的基本知识都是在从事前端开发工作所必不可少的，它们在你以后慢慢的开发长路上一定会发挥作用，希望你在做这个项目之前，对这些概念有一些基本的了解。

# 环境

为了构建这个项目，你需要至少将下面加 `*` 的东西安装到你的电脑上：

1. [`git`](https://git-scm.com/) `*`
2. `nodejs` 
3. `npm`

# 构建

在你开始这个项目之后（在项目的介绍页面应该有一个按钮），项目会为你准备一个远端的仓库，里面包含了该项目的基本结构，你将要按照下面的要求去修改 `index.html` 文件。

## 1. 添加 title

为网页添加一个 `title` 标签。

## 2. 添加一个 header

添加一个包含 "Hello, Code School!" 的 `h1` 标签。

## 3. 创建一个无序列表

创建一个 `ul` 标签，并且其中包含至少两个 `li` 标签。

## 4. 罗列你想要学习的技术

在 `li` 标签中添加你想要学习的技术。

# 提交你的成果

如果你完成了上面的所有任务，将这个项目用 `git push origin master` 命令提交。在提交的过程中会需要你输入账号密码，你应该会在练习页面中看到。

## 在本地执行测试

首先，这一步不是必须的。

但是，还是非常建议你学习这个步骤。

你需要在本地安装 [node.js](https://nodejs.org/en/)，然后你需要在这个项目目录下执行以下的命令：

```
$ npm install
$ npm test
```

如果你所编写的页面是没有问题的，就会出现类似下面的提示信息：

```
HelloCodeSchoolProject (answer) $ npm test

> hello-codeschool-project@1.0.0 test /Users/adam/code/projects/HelloCodeSchoolProject
> mocha test/



  Your HTML Page
    ✓ should have a different title
    ✓ should have a different h1
    ✓ should have a ul
    ✓ should have at least 2 li elements


  4 passing (306ms)
```

# 其他问题

如果你还是不了解如何使用这个项目，请联系作者 aisensiy[AT]163.com。