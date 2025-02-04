# P2常见问题汇总

**1. “数据分析过程”一章XX代码运行报错。**

本章代码报错一般只会有两种可能：

- 一个Cell重复运行多次；
- 代码和课程答案不一致。

因此，排错过程十分简单。首先，确定没有对一个cell重复运行多次。如果不确定，可以在Jupyter Notebook页面的Kernel选项中选择“Restart”，重启Kernel。

在排除此类问题后，请在设置中将语言更改为“英文”，进入“数据分析过程(Data Analysis Process)”一章第31节Quiz Solution查看本章所有答案代码。请务必保证自己的代码和答案**完全一致**。

在完成上面两个步骤后仍然存在该情况，请在群内@助教并直接发送notebook文件，助教会帮忙查看代码。

**2. Conda更新很慢/包下载很慢**

用以下任一种方法可以解决：

- 翻墙（自行搜索软件下载，或者和助教联系）；
- 使用清华大学提供的镜像源，具体操作方式见[此链接](https://mirror.tuna.tsinghua.edu.cn/help/anaconda/)

**3. 如何同时安装Python3和Python2？**

Conda支持安装多个Python环境，具体操作方式见[此链接](https://conda.io/docs/py2or3.html)

**4. 为什么装了多个环境，Jupyter Notebook还是只能使用一个版本的Python？**

请检查你是否在所有环境中安装了Jupyter Notebook，具体方式如下：

1. 打开Anaconda Navigator
 ![](https://i.imgur.com/xHULooG.png)

2. 在Navigator中做如下操作
 ![](https://i.imgur.com/6vi81LS.png)

3. 重新打开Notebook，即可使用两个版本的环境


**5. 命令行是什么？如何在命令行转换目录？**

由于命令行不是本课程的教学内容，所有命令行相关的疑问均请参见[此链接](https://blog.henix.info/blog/windows-cmdbasic/_.html)

**6. Titanic数据集各字段的含义。**

请参阅此[数据字典链接](https://www.kaggle.com/c/titanic/data)

**7. 在命令行和Anaconda Prompt中都无法使用Conda命令的所有解决方案。**

- 检查系统版本。Anaconda已经不支持Windows XP；同时查看自己电脑是32位还是64位（本页面视频有说明），不要装错了；
- 检查自己是否原来安装过Python，如果安装过请彻底删除Python（同时要删除环境变量）后重装Anaconda；
- 检查自己是否将Conda命令添加到了环境变量，操作方法见[本页面](https://stackoverflow.com/questions/28612500/why-anaconda-does-not-recognize-conda-command)；
- 确保你的Anaconda安装路径不包含中文或其他非英语常用字符；
- 经过以上步骤还是没有任何改善，请卸载Anaconda重装一遍；
- 重装一遍后还是没有改善，说明助教也不知道原因，无法帮助你，所以不用在群里@助教了，直接使用微软出品的[Azure Notebook](https://notebooks.azure.com/)作为替代方案完成课程和项目。

**8. Mac系统下无法安装matplotlib，提示“Failed building wheel for subprocess32”**

安装[Xcode](https://developer.apple.com/xcode/)

**9. 安装Anaconda时显示UnicodeDecodeError。**

- 如果Python是2.7版本的，请确保安装路径没有中文或者其他非英语常用字符；
- 如果安装路径不存在上述问题，请参考[此链接](http://www.cnblogs.com/kangronghu/p/6154919.html)解决。

**10. 如何正确下载Notebook？**

1. 右键另存为，将文件存入任一文件夹；
2. 更改文件夹后缀名为.ipynb。如果无法修改，请在文件管理器中勾选下图的“文件扩展名”，再对文件重命名，直接修改后缀。最终你的文件名为“xxxx.ipynb”
![](https://i.imgur.com/IYUCKqb.png)




