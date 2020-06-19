## 《千金良方--MySQL 性能优化金字塔法则》根目录
* 关于此书，也是我与另外两位同事（李春、董红禹）共同的处女作，在撰写过程中有不少心酸且有一些哭笑不得的小插曲。例如：
  * 由于经验不足，疏于和出版社的沟通，误将排版字数65W当做了统计字数65W，于是乎，我们写呀写，写到了45W统计字数，然后再也写不动了，才跟出版社联系，说无法凑足65W字怎么办？
  * 随后，出版社的编辑反馈了2条关键信息：
    * 我们稿酬是按照版税率结算，不是按照字数结算
    * 出版社是按排版计数，不是按照统计计数
  * 于是我们按照出版社的排版样式，一算，吓一大跳，总页数已经超过了1000页，综合评估一些因素之后，必须缩减到700页左右，于是，我们又陷入了需要缩减哪一部分内容的纠结中，经过一番纠结，我们决定将4个附录（附录ABCD）裁剪掉，做成电子版提供给大家免费下载，最后，就是大家看到的正文部分699页（印刷字数约108W字）
  * 历时将近2年，我们几位作者原本都快没啥知觉了，但当我们第一次看到书的封面时（如下图），心里还是忍不住窃喜（我想，写过书的朋友，懂我在说啥的，就好比怀胎9个月，马上就要做父母了一样）
  ![image](https://github.com/xiaoboluo768/qianjinliangfang/blob/master/image/%E5%8D%83%E9%87%91%E8%89%AF%E6%96%B9%E5%B0%81%E9%9D%A2.png)
  * 我们原计划将电子版的下载链接放进前言的末尾，不过，非常非常抱歉的是，由于前期我们检查疏忽，竟然遗漏了电子版的下载链接，导致很多朋友后来前来询问，并没有看到电子版附录的下载链接，甚至有些不明真相的朋友，直接吐槽说书中提到了那么多参数啥的，一丁点也不做介绍。不过，我们在本书第二次印刷时，将电子版的附录下载链接补充到了前言末尾。
  * 我们也在"知数堂"圈内推送过一次电子版的PDF文件，我也单独在朋友圈推送过通过我的百度网盘提供的下载链接。但我想来想去，电子版PDF终究不方便快速查阅，于是，我们决定将4个附录将近15W统计字数的内容开源出来，供大家随时实地方便快速地查阅所需的内容。
  * 另外，考虑到一些朋友前来咨询书中的代码段是否有提供下载，提到做实验的时候不方便（我猜可能想偷个小小的懒吧），所以我们决定将书中的加粗代码段和一些关键的配置代码段源码开源出来。还有，书中一些看起来不那么清晰的大图，我们也一并开源出来了。
  * 如有购书需求，请自行前往京东、当当等平台购买，快捷入口如下：
    * [京东自营购买入口](https://item.jd.com/12728070.html)
    * [当当自营购买入口](http://product.dangdang.com/28477018.html)
* 下面"蓝色"超链接，分别为代码段目录以及4个附录目录的入口，大家可以根据需要自行点击相应的超链接进入各自的目录，这里不再赘述。

### [1. 书中代码段以及高清大图目录](https://github.com/xiaoboluo768/qianjinliangfang/wiki/%E4%B9%A6%E4%B8%AD%E4%BB%A3%E7%A0%81%E6%AE%B5%E4%BB%A5%E5%8F%8A%E9%AB%98%E6%B8%85%E5%A4%A7%E5%9B%BE%E7%9B%AE%E5%BD%95)
  * 已上传完成

### 2. 附录完整版

#### [2.1. 附录A 线程状态信息详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95A-%E7%BA%BF%E7%A8%8B%E7%8A%B6%E6%80%81%E4%BF%A1%E6%81%AF%E8%AF%A6%E8%A7%A3)
 * 已上传完成

#### [2.2. 附录B show engine innodb status详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95B-show-engine-innodb-status%E8%AF%A6%E8%A7%A3)
 * 已上传完成

#### [2.3. 附录C MySQL常用配置变量和状态变量详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95C-MySQL%E5%B8%B8%E7%94%A8%E9%85%8D%E7%BD%AE%E5%8F%98%E9%87%8F%E5%92%8C%E7%8A%B6%E6%80%81%E5%8F%98%E9%87%8F%E8%AF%A6%E8%A7%A3)
  * 已上传完成

#### [2.4. 附录D explain 执行计划详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95D-explain-%E6%89%A7%E8%A1%8C%E8%AE%A1%E5%88%92%E8%AF%A6%E8%A7%A3)
  * 已上传完成

------

开始 | 下一篇：[书中代码段以及高清大图目录](https://github.com/xiaoboluo768/qianjinliangfang/wiki/%E4%B9%A6%E4%B8%AD%E4%BB%A3%E7%A0%81%E6%AE%B5%E4%BB%A5%E5%8F%8A%E9%AB%98%E6%B8%85%E5%A4%A7%E5%9B%BE%E7%9B%AE%E5%BD%95)

------

* 本 WIKI 包含了《千金良方--MySQL 性能优化金字塔法则》一书的代码段加粗命令行命令和SQL语句文本、以及4个附录内容，其中：
  * 代码段和高清图单独整理为一个系列文档，如下：
    * [书中代码段以及高清大图目录](https://github.com/xiaoboluo768/qianjinliangfang/wiki/%E4%B9%A6%E4%B8%AD%E4%BB%A3%E7%A0%81%E6%AE%B5%E4%BB%A5%E5%8F%8A%E9%AB%98%E6%B8%85%E5%A4%A7%E5%9B%BE%E7%9B%AE%E5%BD%95)
  * 每个附录都各自整理成了一个小系列文档，如下：
    * [附录 A 线程状态信息详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95A-%E7%BA%BF%E7%A8%8B%E7%8A%B6%E6%80%81%E4%BF%A1%E6%81%AF%E8%AF%A6%E8%A7%A3)
    * [附录 B show engine innodb status 详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95B-show-engine-innodb-status%E8%AF%A6%E8%A7%A3)
    * [附录 C MySQL 常用配置变量和状态变量详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95C-MySQL%E5%B8%B8%E7%94%A8%E9%85%8D%E7%BD%AE%E5%8F%98%E9%87%8F%E5%92%8C%E7%8A%B6%E6%80%81%E5%8F%98%E9%87%8F%E8%AF%A6%E8%A7%A3)
    * [附录 D explain 执行计划详解](https://github.com/xiaoboluo768/qianjinliangfang-The-appendix/wiki/%E9%99%84%E5%BD%95D-explain-%E6%89%A7%E8%A1%8C%E8%AE%A1%E5%88%92%E8%AF%A6%E8%A7%A3)

* 《千金良方--MySQL 性能优化金字塔法则》 一书的作者信息如下：
  * 李春、罗小波、董红禹
* 联系人QQ：309969177
* 提示：附录内容主要的翻译、验证、测试、整理工作由本人罗小波完成。鉴于本人精力和能力有限，难免出现一些纰漏，欢迎大家踊跃指正！
* 郑重声明：本WIKI仓库中的资料为电子工业出版社与本书的三位作者共同授权开源，为了在方便大家的同时，避免不必要的纠葛，任何商业与非商业的引用、转载，麻烦大家注明出处，谢谢配合！
