**NirCmd的简介**

NIrCMD是一个小命令行实用工具，允许您在不显示任何用户界面的情况下执行一些有用的任务。通过使用简单命令行选项运行NIMRCD，可以在注册表中写入和删除值和键，将值写入INI文件，拨号到Internet帐户或连接到VPN网络，重新启动Windows或关闭计算机，创建文件快捷方式，更改创建/修改日期。一个文件，改变你的显示设置，关闭你的显示器，打开你的CD-ROM驱动器的门，以及更多…

官网：http://www.nirsoft.net/utils/nircmd.html

**NirCmd的安装**

http://launcher.nirsoft.net/downloads/index.html 
你也可以直接git本项目的zip，32位/64位都有：  

**NirCmd的使用方法**

使用NirCmd：

这款软件是一个独立的可执行程序，不需要任何的安装过程或者额外的dll文件支持。只需要把exe文件复制到任何指定的文件夹，并且根据你的需要添加你需要的命令选项运行即可。推荐复制NirCmd.exe到Windows目录，或者复制到任何系统中path环境变量中所列出的路径下，这样你就不需要在每次运行时输入NirCmd的完整路径。

使用举例：https://jingyan.baidu.com/article/3c343ff7aee3470d377963fc.html

介绍nircmd命令博客地址： https://blog.csdn.net/hongkaihua1987/article/details/85050851


安装好nircmd之后，你就可以使用它的命令来控制windows了，当然，你也可以创建快捷方式来用快捷键启动这个命令：  
例如：你想要通过F10来控制电脑的声音是否静音？
创建一个快捷方式，命令如下：  
```
nircmd.exe mutesysvolume 2
```

右键属性，设置F10为快捷键，当年按下F10，就会启动这个命令，系统就会静音，再次按下，静音解除！

![cmd-markdown-logo](https://github.com/lianchua/windows-shortcuts/blob/main/images/demo.png)

![cmd-markdown-logo](https://github.com/lianchua/windows-shortcuts/blob/main/images/cmd.png)

![cmd-markdown-logo](https://github.com/lianchua/windows-shortcuts/blob/main/images/new.png)

![cmd-markdown-logo](https://github.com/lianchua/windows-shortcuts/blob/main/images/save.png)

cmd测试该命令可以控制声音的静音，然后新建快捷方式，输入上面代码框的的命令，然后取个名字，设置一个快捷键就可以快捷键执行了，当然，单击也能执行，cmd也能执行，不过我们肯定是要在任意界面按键执行！