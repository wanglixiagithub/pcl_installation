在 安装pcl的过程中遇到了一个一直困扰我好久的问题，最后发现是因为anaconda的存在，所以一些需要链接的东西直接链接到anaconda里面了，解决办法有如下：
1.bashrc注释掉anaconda，并且source ~/.bashrc 或者是重新打开shell
2.uninstall anaconda
3.修改anaconda的名字为其他。

并且在安装的过程中，我用了sudo所以安装在了系统目录里，在usr/local/share里面有文件，并且在bin里面有可以直接运行的文件。