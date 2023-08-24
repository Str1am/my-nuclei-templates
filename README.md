# my-nuclei-templates
自用的nuclei模板，尽量会不断更新。编写的过程中会和官方模板库进行对比，尽量避免出现重复的情况。在编写的过程中尽量是以2017年及以后出现的漏洞，太早的漏洞就没有进行编写了

# 23-8-24
更新hw poc

# 23-5-26

继续优化和添加了部分poc，这里部分使用了nuc的dnslog，建议可以自定义以下dnslog使用，提高模版检测的正确率

如：iserver "https://oast.fun" -itoken "you token"


# 关于使用
下载nuclei：
https://github.com/projectdiscovery/nuclei

放在nuclei-templates目录下即可使用

![image](https://user-images.githubusercontent.com/48739932/150737828-e759d340-788c-4311-80e4-39aa2a1cb385.png)


大部分poc已通过测试，主要以检测为主，不涉及攻击行为。

# 免责声明

此处提供的所有工具仅供授权状态下使用，且poc仅以检测作用为主，如发生违法犯罪行为,非授权攻击行为于本人无关


