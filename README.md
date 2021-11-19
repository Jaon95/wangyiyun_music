# wangyiyun_music
网易云音乐爬虫学习

# 1 初衷
1.1  利用闲暇之余，学一门技术，于是就相中了python的爬虫技术

# 2 想法
2.1 使用edge自带的开发者工具，找到网易云歌曲搜索过程是如何处理和加密要检索的字符串的。地址：https://music.163.com/#/search/m/。<br/>
2.2 发现其对检索的数据进行了加密，发现的过程参考了：https://blog.csdn.net/weixin_43999566/article/details/87697962，也就是通过添加js代码的方式，学习了如何打印入参数据。<br/>
2.3 之后学习了aes、rsa算法的一般处理流程及数学原理，学习到了如何处理涉密数据。（整个过程很巧妙）<br/>
2.4 自己在代码实现过程当中，遇到了padding，需要使用base64等进行编码、解码的问题，目前没有搞清楚为何要用到base64.参考了：（github找不到项目的地址了，后面再补上）。

# 3 其他
上述代码仅限于我个人的爬虫学习，如您需要使用，情遵循：[MIT](https://github.com/darknessomi/musicbox/blob/master/LICENSE)
