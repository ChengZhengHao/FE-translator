### 将你的Medium文章导出成Markdown格式

#### 原文链接：[Export your Medium posts to Markdown](https://medium.com/@macropus/export-your-medium-posts-to-markdown-b5ccc8cb0050)

这是一个避免复制、粘贴和重写你Medium文章的有效解决方案。

![](1*i-S80mDrkJQO2tJ_lhYwfA.png)

首先，你需要在你的电脑上安装node。

所有平台都有node安装程序, 只需下载并像安装其他程序一样安装即可:

* [https://nodejs.org/zh-cn/download/](https://nodejs.org/zh-cn/download/)

安装完成后, 你可以打开 **Windows** 上的命令提示符(cmd.exe) 或者 **MacOS** 上的终端 或者 **Linux** 去执行这条命令。

    npm install -g mediumexporter

安装 **mediumexporter**. 安装完毕后, 你就可以将Medium文章导出成Markdown格式。

移动到想要导出文件的目录。

***(Windows)***

    cd c:\Users(username)\Desktop 

***(Mac)***

    cd ~/Desktop 

执行下面一行:
 
    mediumexporter https://medium.com/p/export-your-medium-posts-to-markdown-b5ccc8cb0050 > medium_post.md

你可以看到名为的**medium_post.md**文件，其中文章内容已经被转换为Markdown语法。 你可能需要做一些微调, 不过大多数情况下格式和结构还不错。

如果你想直接复制到你的粘贴板 (OSX系统) 你可以添加如下内容 **(| pbcopy)** :

    mediumexporter https://medium.com/p/export-your-medium-posts-to-markdown-b5ccc8cb0050 | pbcopy

如果你不喜欢使用命令行操作，这还有 **Chrome 浏览器拓展**, 虽然它又快又好，但是部分结果需要自行编辑:

**https://chrome.google.com/webstore/detail/convert-medium-posts-to-m/aelnflnmpbjgipamcogpdoppjbebnjea?hl=en**

