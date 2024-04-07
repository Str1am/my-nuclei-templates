# my-nuclei-templates
自用的nuclei模板，尽量会不断更新。编写的过程中会和官方模板库进行对比，尽量避免出现重复的情况。在编写的过程中尽量是以2017年及以后出现的漏洞，太早的漏洞就没有进行编写了

# 23-8-24
更新hw poc

# 23-5-26

继续优化和添加了部分poc，这里部分使用了nuc的dnslog，因为官网的dnslog需要fq，也并未找到其他dnslog的使用方法，于是为了检测的准确性，可以服务器上搭建官方dnslog，然后调用即可使检测更加准确

https://github.com/projectdiscovery/interactsh/

下载相应的client端

<img width="407" alt="image" src="https://github.com/Str1am/my-nuclei-templates/assets/48739932/bf8076aa-93e1-4a28-bac1-de022ddc9a34">

然后服务器运行

<img width="419" alt="image" src="https://github.com/Str1am/my-nuclei-templates/assets/48739932/643d1b89-e8ac-4fef-8c1c-c3cec986f148">

在nuc中使用即可

<img width="1172" alt="image" src="https://github.com/Str1am/my-nuclei-templates/assets/48739932/28bc4e30-046f-433f-b53a-9b3988cf3661">

-iserver oast.pro -itoken you token

检测log4如下

<img width="880" alt="image" src="https://github.com/Str1am/my-nuclei-templates/assets/48739932/fcb62a64-a1a7-4616-8d41-f3a7b25e58eb">



# 关于使用
下载nuclei：
https://github.com/projectdiscovery/nuclei

放在nuclei-templates目录下即可使用

![image](https://user-images.githubusercontent.com/48739932/150737828-e759d340-788c-4311-80e4-39aa2a1cb385.png)


大部分poc已通过测试，主要以检测为主，不涉及攻击行为。

# 免责声明

此处提供的所有工具仅供授权状态下使用，且poc仅以检测作用为主，如发生违法犯罪行为,非授权攻击行为于本人无关


