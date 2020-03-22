## 录屏：链接：https://pan.baidu.com/s/10xir-IvF7rAym-XYiB8voQ 提取码：rhzb
## 安装过程：
#### 1.安装unity：
点击安装包安装然后注册登录即可
#### 2.安装java：jdk-8u241-windows-x64
安装64位java后设置环境变量，创建JAVA_HOME，编辑path：在原变量值的最后面加上 "%JAVA_HOME%\bin"，后cmd命令符输入java -version得到java版本即为成功
#### 3.安装插件：UnitySetup-Android-Support-for-Editor-5.6.2f1
直接安装即可
#### 4.安装SDK
解压压缩包：android-sdk_r24.4.1-windows，后点击SDK Manager后更新，（大概需要40min）
#### 5.打开unity 
edit-Preferences 找到External Tools中，点击SDK、JDK中的点击Browse,并选择SDK（对应安卓开发平台的路径）与JDK（对应Java的路径）
#### 6.打开sd packet，build
点击下面素材“sss”后点击在“file”下找到 “build setting ”选项，点击Player settings修改Other Settings中的 package name，命名方式可自由修改，但是命名的格式必须为"xxx.xxx.xx",修改完成后，点击Build。生成apk
#### 7.打开夜神模拟器，解析apk


