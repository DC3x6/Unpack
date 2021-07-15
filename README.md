# 功能

批量反编译小程序源码

# 使用

## 安装nodejs

双击node-v14.16.1-x64.msi按照提示安装即可  

## 清空历史小程序

微信默认存储小程序位置为C:\Users\XXX\Documents\WeChat Files\Applet

![image-20210715172334174](readme.assets/image-20210715172334174.png)

每次操作前将该目录内所有文件清空，然后开启微信电脑版，搜索打开需要反编译的小程序。

![image-20210715172359880](readme.assets/image-20210715172359880.png)

将所有小程序打开后，直接在工具unpack目录下，执行python3 unpack.py即可。
最终结果保存在unpack\wxappUnpacker\wxapkg下

![image-20210715172547631](readme.assets/image-20210715172547631.png)

