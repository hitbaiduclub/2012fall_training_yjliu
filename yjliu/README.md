简明培训计划
------------

隋嘉楠与刘燊两位同学的培训计划

[ 公共练习 ]

* Github练习
* Python练习

[ 隋嘉楠同学个人部分 ]

* 隐马尔科夫模型的学习与实现

[ 刘燊同学个人部分 ]

* django环境的配置
* bootstrap CSS框架的使用

第一个任务的讲解
----------------

这个任务是这样：

> 请在这个项目中建立一个名为姓名缩写形式的文件夹，（例如：隋嘉南同学请建立jnsui）。在这个文件夹中新建一个README.md文件，填写你们最近一段时间的考试、课程设计的信息。在不影响大家正常学习的前提下进行项目。

#### 任务更详细的解释

Github是一个项目管理网站。

现在我们已经有一个项目了，这个项目是由一些代码、文件组成的。我们可以通过github管理这些__代码、文件__，比如新建文件，修改文件内容。项目管理系统的好处是我们的每次修改都会被记录，如果某次修改后，我们发现修改出错了，那么也有机会“回到过去”。

这个任务是希望大家在项目中建立一个文件夹，并在文件夹中建立一个文件。下面具体介绍如何来建立文件夹和文件。

#### 具体做法

1. 下载一个叫git的软件，它的下载链接是![Git - Downloads](http://git-scm.com/downloads)。这个软件可以看成是Github的客户端（虽然这种理解是错误的），下载后安装。

	* 对于Linux用户，安装git后等于给系统添加了一个命令。可以直接在shell中使用git命令使用。
	* 对于Windows用户，安装git后有一个git bash。git shell的操作和Linux下的shell一样，建议使用这个操作。

2. 安装好git后，需要配置ssh-key。具体的配置方法参考![Git与Github的使用(ubuntu)](http://www.pureweber.com/article/git-and-github/)或者![Set Up Git](https://help.github.com/articles/set-up-git)。

3. 在这些都配置好后，在shell或者git bash中用下面的命令：

```
git clone git@github.com:hitbaiduclub/2012fall_training_yjliu.git
```

就把远程项目拷贝到本地了。

然后用，
```
mkdir %yourname%
cd %yourname%
touch README.md
```
建立一个文件夹并且建立文件，同时修改一下文件内容。

这之后用下面命令将这个文件提交到远程服务器
```
git add README.md
git commit -m "finish task 1"
git push -u origin master
```

这些都做完后，浏览github上的这个repo，你会发现出现了你之前建立的文件
