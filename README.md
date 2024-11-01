# Simple cryptography tools

这是一个简易的密码工具库。

这个库的代码复现了一些我本人因兴趣所了解的部分密码学知识，有各种极大的局限性（代码里有一大半都是UI和输入检查），若要使用密码学工具……本人更建议使用其他的在线密码工具和项目。
![image](https://github.com/LudwigIrisNebula/Simple-cryptography-tools/blob/main/images/background1.png)


## textual analysis
#### 文本频率分析工具

textual analysis tool实现了：词频分析，字母频率分析，连续字符统计分析，Algoritmy网站统计的字母频率展示

## CaesarCipher Tool
#### 凯撒密码

它是一种替换型的密码，明文中的所有字母都在字母表上向后（或向前）按照一个固定数目(shift)进行偏移后被替换成密文。例如，当偏移量为3时，字母A会被替换为D，字母B会被替换为E，以此类推。

CaesarCipher Tool实现了：加密与解密，一键暴力破解，一键去除标点符号与空格，窗口可固定在桌面最上层。

## VigenereCipher Tool
#### 维吉尼亚密码

一种使用多个凯撒密码根据密钥进行加密的方法。它的工作原理是将明文中的每个字母与密钥中的相应字母相加（模26），然后将结果作为新的字母。例如，如果密钥是"LEMON"，那么第一个字母'L'（在字母表中的位置12）加上'L'（位置12），结果是24，对应的字母是'Y'。

VigenereCipher Tool实现了：加密与解密，显示维吉尼亚图表

## FenceCipher Tool
#### 栅栏密码

一种古典加密技术，通过将文本字符按行排列成栅栏形状，然后按列读取字符来加密信息。如给定一个密钥（key），文本会被分成若干行，每行的字符数将由密钥决定。

FenceCipher Tool实现了：简单的加密与解密
