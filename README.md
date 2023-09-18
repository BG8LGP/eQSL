# eQSL
基于GB/T 33190-2016 《电子文件存储与交换格式版式文档》实现的eQSL卡片方案

# 正在施工中...





## SM2公钥（测试用）
```
-----BEGIN PUBLIC KEY-----
MFkwEwYHKoZIzj0CAQYIKoEcz1UBgi0DQgAE4sLuaTJJjpeXidt0NpVC3Apd5Awx
rw1Y8+hqu7nSAf6Ye55Zhl/4kbT2Kf9gjBmCbAr2T158rfagtadZCyvwvw==
-----END PUBLIC KEY-----
```

PS: 以上公钥仅仅用于**此项目中的demo.ofd文件**,不会用于其他eQSL文件或者其它任何地方！！！

## Q&A

### 1. 这个玩意儿有什么用？
- 作为传统纸质QSL卡片的补充，在不方便或者经济条件不允许的情况下使用。
- 每张OFD格式的eQSL文件含有使用自己的数字证书私钥所签的电子签名，具有不可抵赖性，可以代表一条真正的QSO，在制度完善的未来可以据此申请奖状。

### 2. 为什么要用OFD格式？PDF格式不是更被广泛使用吗？
OFD格式用XML来描述版式，制作eQSL起来比PDF简单，而且本身就可以进行电子签名。是国家电子发票专用格式，干嘛不用？  
现在业余无线电申请奖状、申请证书、上传通联日志，都用的老美那一套玩意儿，近年来中美的情况看到了？什么时候老美不乐意了，不让你玩了怎么办？  
所以我们要有自己的一套东西，国家在各个领域推行国产自主，那业余无线电领域也要有。  

### 3. 我怎么打开OFD文件？
1. 用WPS打开
2. 下载第三方OFD阅读器打开
3. 在线打开：[OFDView](http://www.cnofd.cn/ofdview.html)
4. 自己搭建一个：[gitee.com/cnofd/ofdview](https://gitee.com/cnofd/ofdview)
