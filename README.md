## BurpSuitePro-2.1

**破解BurpSuitePro-2.1.02版本**

[补丁下载](http://pan.ximcx.cn/show/%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7/%E6%8A%93%E5%8C%85%E5%B7%A5%E5%85%B7%E9%9B%86%E5%90%88/Burp%20Suite%20Pro%E7%A0%B4%E8%A7%A3%E7%89%88%E9%9B%86%E5%90%88/2.1.x/BurpSuite_pro_v2.1%E7%A0%B4%E8%A7%A3%E7%89%88.rar)

- Win使用

  ```
  0-在Oracle官网下载Jre并安装;
  1-在BurpSuite官网，下载Community版本的安装包，并安装;
  2-把破解的pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar;
  3-把burp-loader-helper.jar移动到BurpSuite的安装目录里面
  4-双击启动burp-loader-helper.jar，如果提示找不到类函数，在cmd或powershell里面运行
  java -jar "C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar" -jar "C:\Program Files\BurpSuiteCommunity\burpsuite_community.jar"
  ```

  **我自己用的情况下，提示环境变量问题，找不到类函数，所以改了个简单的bat脚本**

  **bat_Code**

  `start "" "C:\ProgramData\Oracle\Java\javapath\java.exe" -jar "C:\Program Files\BurpSuiteCommunity\burp-loader-helper.jar"`

- Linux使用

  ```
  1-在BurpSuite官网，下载Community版本的sh文件;
  2-安装"sudo bash burpsuite_community_linux_v2.1.sh"
  3-把破解的2.1 pro版的jar包，改名为burpsuite_community.jar，并替换软件安装目录下的burpsuite_community.jar
  4-把burp-loader-helper.jar移动到BurpSuite的安装目录里面
  ```

  **直接java -jar加载即可**

  `java -jar burp-loader-helper.jar`

  **或者添加一个alias**

  `alias bs2.1="java -jar /opt/BurpSuiteCommunity/burp-loader-helper.jar"`

> 下载使用

**zip包拆分成了三个，所以如果在github下载的话，请把三个i_dont_know_this的包下载，并解压后缀为zip的压缩包**

> 长期更新地址

[西门吹雪](http://ximcx.cn/post-110.html)
