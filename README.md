# Termux-install-java
## 在termux中安装java
  
这个项目只是一个随手方便做的，简单为主，以后如果有其他更简单的方法会收录。  
  
### 方法一
使用**when**进行安装  
**when**是大佬[nibazshab]( https://nibazshab.github.io/)做的一个termux插件  
安装指令：  
>echo "deb [trusted=yes] https://nibazshab.github.io/404/sourc/ termux extras" >> $PREFIX/etc/apt/sources.list; pkg in when  
  
进入配置环境中选择安装Java就行  
  
### 方法二
直接使用安装包进行安装。  
termux是基于Debian的，所以可以使用Debian的包进行安装。  
安装包来自于大佬when插件之中。  
安装指令：
>wget https://github.com/amlkiller/Termux-install-java/releases/download/java-8-jdk_1.8.0-151_aarch64/java-8-jdk_1.8.0-151_aarch64.deb  
>  
>dpkg -i java-8-jdk_1.8.0-151_aarch64.deb  
  
如果无法下载请手动来到发行页面将安装包下载并放入termux再进行第二条安装指令。  
