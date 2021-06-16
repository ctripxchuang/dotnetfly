# 你好，我是一线码农，沪漂程序员，终生学习者。


.NET 发展至今已20多年，再回首时您是否发现所光顾的文章绝大多数都是在`编译器`之上聊 C# 各种特性和用法，很少看到有文章会沉到`编译器`之下来解读 C#，在国内真的很缺少这种深度文章，更没有为此话题聚焦的技术深度社区。


既然国内没人做，那我就来试一试，为此我打造了一个以 `内存泄漏，CPU爆高，死锁挂死` 为主题的 .NET 高级调试圈，目前圈子已聚集近 50 位资深工程师和架构师，毕竟能轻松搞定这些诡异又非常紧急的生产事故，对老板来说您绝对是压舱石，对团队来说您绝对是技术领袖。


独乐乐不如众乐乐，希望这个圈子能够不断的迭代壮大，孵化出一批`.NET高级调试`的技术高手，让原来需要数周才能解决的 内存泄漏，CPU爆高 问题缩短到分钟级。


为了圈子的纯粹度，一定要过滤掉`观光客`和`灌水客`，免费的圈子很难运营下去，毕竟调试真的是一场苦行之旅，没有真正的毅力和兴趣很难走下去，也没有随随便便的成功！好酒也怕巷子深，现年费：原价：**~~368元~~**，现价：**168**， 再送大家一张 **39元** 优惠券，你觉得值那就值。

![](https://huangxincheng.oss-cn-hangzhou.aliyuncs.com/img/qiu.jpg)


**dump不停，系列不止💪💪💪 ，感谢大家持续关注！**


### 真实案例一览

- 【2021年5月31日 周一】[记一次 .NET 某三甲医院HIS系统 内存暴涨分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247490175&idx=1&sn=6db917cd912e5585364aff57c9f4ceea&chksm=a698693291efe02474bbd52ce004c58d77cfda14663afb7ee00d490359c90df02d6fc46b5b5b&token=1861625626&lang=zh_CN#rd)

- 【2021年5月28日 周五】[记一次 .NET 某电商交易平台Web站 CPU爆高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247490153&idx=1&sn=8fcab265770b0daad9928f631e7d0dbf&chksm=a698692491efe03299075a17b950a5cf584be714aea7d73f3ffeb59b25252d97645504713042&token=796142711&lang=zh_CN#rd)

- 【2021年5月24日 周一】[记一次 .NET 某外贸Web站 内存泄漏分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247490027&idx=1&sn=235bbe529ec0e1a3431122de64502921&chksm=a6986aa691efe3b0dbfa5f4ddb7e21cfad4c875fc958844696e4f480d847b82c5556a3fb27bc&token=796142711&lang=zh_CN#rd)

- 【2021年5月21日 周五】[记一次 .NET 某HIS系统后端服务 内存泄漏分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489999&idx=1&sn=5090587e668d6095f6d1f17424ae0f1c&chksm=a6986a8291efe3940973783639f6ee26f31bbab6c08fa54d2687d35df3e0c9233fbe2918fc29&token=95934485&lang=zh_CN#rd)

- 【2021年5月19日 周三】[记一次 .NET 车联网云端服务 CPU爆高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489981&idx=1&sn=1445c1e6157542e6e1cc351481903d54&chksm=a6986af091efe3e6d493a8a966b8e18e3699c087e41359cd935d958208c12edfe4bbc2438466&token=749169776&lang=zh_CN#rd)

- 【2021年5月17日 周一】[记一次 .NET 某旅行社Web站 CPU爆高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489952&idx=1&sn=d062734cdc37ee0b8b6eb8b7abcc792d&chksm=a6986aed91efe3fb009112dc19a2c8a844201fa632c1a7fd1cc900c819fd80544f30caecc755&token=749169776&lang=zh_CN#rd)

- 【2021年5月14日 周五】[记一次 .NET 某医院HIS系统 CPU爆高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489931&idx=1&sn=4dc0b99b1abeb9eaa01ef8621a7a0c82&chksm=a6986ac691efe3d0332177fcf0ca382d2b24da0c80ba60e1166d754077cc6c62e3e8d99a111b&token=1711976643&lang=zh_CN#rd)

- 【2021年5月8日 周六】[记一次 .NET 医院CIS系统 内存溢出分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489873&idx=1&sn=91e2f6550adf263e51be407b413da4af&chksm=a6986a1c91efe30ac1501f8305fca75778063db703656883d0c6f8e34581f5c4f07bacb2c69f&token=164115488&lang=zh_CN#rd)

- 【2021年5月3日 周一】[记一次 .NET 某教育系统 异常崩溃分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489829&idx=1&sn=34e6169a43eb5ecc42a51761a894b7a3&chksm=a6986a6891efe37ea1720c0065cf942749d5ed24b2896189ec48974a3d4f28c0736ebd53a377&token=2092322748&lang=zh_CN#rd)

- 【2021年4月29日 周四】[记一次 .NET医疗布草API程序 内存暴涨分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489805&idx=1&sn=f3467d62ffd2909611255c0bd53cb469&chksm=a6986a4091efe356b1664013a1ffa614e1ae6cef8618b240adc97068ea6e6faf378f449e6494&token=1292573312&lang=zh_CN#rd)

- 【2021年4月27日 周二】[记一次 .NET WPF布草管理系统 挂死分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489772&idx=1&sn=a7781ada0ca36f126dead62c5daa6d47&chksm=a6986ba191efe2b7f9afae6788d5b976e0e4c1941c8f8bd21efef5ee844c7ba6355777e93e26&token=1292573312&lang=zh_CN#rd)

- 【2021年4月25日 周日】[记一次 .NET医院公众号程序 线程CPU双高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489751&idx=1&sn=8dc23fc83dd698887bc12bdae5eb5996&chksm=a6986b9a91efe28c69e3fadda0e878f8b047eb73b45bed188ff1b4036c5979d3631077b4ee23&token=430418757&lang=zh_CN#rd)

- 【2021年4月21日 周三】[记一次 .NET游戏站程序的 CPU 爆高分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489684&idx=1&sn=554f5194c3c83da43ca2fc81846aa260&chksm=a6986bd991efe2cfe9efc00a5ab1ff161e40994bfaac9b350a9c4d7bdfb8b3fed0fd14896a8c&token=1961578048&lang=zh_CN#rd)

- 【2021年4月19日 周一】[又一起.NET程序挂死, 用 Windbg 抽丝剥茧式的真实案例分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489632&idx=1&sn=b7946a760062edf6cf0df82fa0503169&chksm=a6986b2d91efe23b79aa9061a2f54b61fa5141e330e810e4b576bf4fa92fc2ef78d712bec896&token=1961578048&lang=zh_CN#rd)

- 【2021年2月8日 周一】[再记一次 应用服务器 CPU 暴高事故分析](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247488730&idx=1&sn=759c8b2bd1f01136a68b7659f926fa45&chksm=a698679791efee81392a6143f8f0f176d8c11fa399dd53eae164b215810d78d41fa5a7e45f3e&token=1961578048&lang=zh_CN#rd)

- 【2020年6月4日 周四】[字符串太占内存了，我想了各种奇思淫巧对它进行压缩](http://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247484069&idx=1&sn=9a0a2b700edc20294a5f280c39f8ad78&chksm=a69871e891eff8fe8ec369eab8fa480416ccce1cfe188ccb55409cdf42841dfa90281a16d816&token=1098575339&lang=zh_CN#rd)

- 【2020年5月26日 周二】[阿里短信回执.net sdk的bug导致生产服务cpu 100%排查](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483948&idx=1&sn=eed8e82f25da46340846194000d869cc&chksm=a698716191eff877b980dce7531436ffad3dbb7541275a4e8f625551616206ecc62466c182e1&token=430418757&lang=zh_CN#rd)

- 【2020年5月22日 周五】[BitArray虽好，但请不要滥用，又一次线上内存暴增排查](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483895&idx=1&sn=9df99be01677a20288b7d18ded113977&chksm=a69872ba91effbac65df26f3f0fcd46c5bd9a9ebd5f1528c213cdf621099439ba98e76720094&token=1260076125&lang=zh_CN#rd)

- 【2020年5月20日 周三】[记一次排查线上程序内存的忽高忽低，又是大集合惹祸了](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483887&idx=1&sn=3bfea65a9ccd58df5813face404de5c9&chksm=a69872a291effbb40554a72df4d34084dbce76c58ac66bc8af21cd606d7ddb4c6a0e4da7d8e9&token=1260076125&lang=zh_CN#rd)

- 【2020年5月4日 周一】[慎用ToLower和ToUpper，小心把你的系统给拖垮了](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483784&idx=1&sn=3ee4a0b58eb85895f2b5951dedc36974&chksm=a69872c591effbd3062ba57c78994e519235896f607f2d8e5052f8787d7e2fa84bd8c12d565e&token=1260076125&lang=zh_CN#rd)

- 【2020年4月27日 周一】[用long类型让我出了次生产事故，写代码还是要小心点](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483750&idx=1&sn=c407fe5eebc9cd64c65e46d843679f98&chksm=a698722b91effb3d49c9a01f06a9e8ceb05ca08ff6a9ed80a1b7db441ee954399ebea69f4d4a&token=1961578048&lang=zh_CN#rd)


### Windbg调试解惑一览


- [教你配置windows上的windbg,linux上的lldb，打入clr内部这一篇就够了](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483792&idx=1&sn=b2984c421787efa352678fcf9b50490f&chksm=a69872dd91effbcbedd264f1a59c1671f068b40303e7a190a52b7407196fe3b8bb3e533b9d05&token=1260076125&lang=zh_CN#rd)

- [如何在 .NET 程序万种死法中有效的生成 Dump (上)](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489260&idx=1&sn=ef89832e72b4beb354e64c527816a456&chksm=a69865a191efecb7378ba266391115b4d29ccfbd8dd70def90c625b2c4051231aae5c5ca2e24&token=763414529&lang=zh_CN#rd)

- [如何在 NET 程序万种死法中有效的生成 Dump (下)](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489377&idx=1&sn=8039f36fa688ff3575009de94d2ae026&chksm=a698642c91efed3a9f3e4f0d100c626ebb37c912557b48eb03a2830cd98145c25cb564e33f01&token=1961578048&lang=zh_CN#rd)

- [.NET程序崩溃了怎么抓 Dump ? 我总结了三种方案](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247490052&idx=1&sn=a4f948f0267698e42f7c5289383fa49d&chksm=a698694991efe05f6daac0f0c4f0bc30b1a3052d2de459ffdf8cc1e828d3df17d5ac746139dd&token=796142711&lang=zh_CN#rd)

- [如何从 dump 文件中提取出 C# 源代码？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489167&idx=1&sn=208edc764f9f88eaf3237d64946f3012&chksm=a69865c291efecd487a37dca0b7a38fafa0965a634893eaaa28c40f49b3827316d1dc4f280d6&token=763414529&lang=zh_CN#rd)

- [一句 Task.Result 就死锁, 这代码还怎么写？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489891&idx=1&sn=f7ca7786a498c0a27bd58339a97111ee&chksm=a6986a2e91efe338f270a7929456f76c63e9c7c2afa181835759ed439c45b8a9926029f81686&token=1711976643&lang=zh_CN#rd)

- [茫茫内存，我该如何用 windbg 找到你 ？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247489276&idx=1&sn=b5e15fb9c7b2fa7e74ed176a6e56502b&chksm=a69865b191efeca75b66287fd96c99b3a15334abbe7761c350adc4e8d4a8fcdd6ffbbc94b189&token=1961578048&lang=zh_CN#rd)

- [配置文件中的数据库连接串加密了，你以为我就挖不出来吗？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247485201&idx=1&sn=1ec4c336bf49f9cdceea14d2661f1d38&chksm=a698745c91effd4ad958c49e8def102fb5027a7139224d10c958a70f8ed69f1e4191a4f746e4&token=1961578048&lang=zh_CN#rd)

- [被 C# 的 ThreadStatic 标记的静态变量，都存放在哪里了？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487742&idx=1&sn=6c77fc2e5318eac5c91690ca451e43bd&chksm=a69863b391efeaa56ac0e7cbc2b443a1b098f05593eafea14849f3bd0bba6ce5b835275f0506&token=250896018&lang=zh_CN#rd)

- [对 精致码农大佬 说的 Task.Run 会存在 内存泄漏 的思考](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247488049&idx=1&sn=0b0e500c99822f482a7300e44351237f&chksm=a698617c91efe86a78001c6d68d1b1dea064b094641e6d6200276d6f818a10d76f0df322f785&token=250896018&lang=zh_CN#rd)

- [HashSet扩容机制在时间和空间上的浪费，远大于你的想象](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247484314&idx=1&sn=c827979c90a9b491b8f78b9f65f1d562&chksm=a69870d791eff9c164aeca6e9bfebaaaf414604d249198f03f3f3246da882a7fe62732b787c4&token=1961578048&lang=zh_CN#rd)

- [linq 查询的结果会开辟新的内存吗？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487799&idx=1&sn=a5dd0a46913dd832a17fb5ad2131abcf&chksm=a698627a91efeb6c99ff5455c4ab96229d97011ebb76765e1d6e148a1ced54fe92e6cbe25596&token=250896018&lang=zh_CN#rd)

- [用了这么多年的泛型，你对它到底有多了解？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483746&idx=1&sn=1a9ae1e942d12ce0ae184ebaddd96a3a&chksm=a698722f91effb394d008529ab311e97ae94651e76d36a2c70ceaf020faace687d91e067a0f5&token=1260076125&lang=zh_CN#rd)

- [对精致码农大佬的 [理解 volatile 关键字] 文章结论的思考和寻找真相](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487203&idx=6&sn=928571ed608091597892e909e64db0e8&chksm=a6987dae91eff4b8ac3c8ebc55316ad24fbe0801e903832ac57e9251366655bd7870a5c6bba7&token=2136785246&lang=zh_CN#rd)

- [一个static和面试官扯了一个小时，舌战加强版](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247484105&idx=1&sn=0e53cc1900421222a5eae65ee1cfd725&chksm=a698718491eff892a4e63d5cf62a0b1e2ee2f85ed7a1111cd889d4f97f9f6db0309e0d7ae096&token=1098575339&lang=zh_CN#rd)

- [一个lock锁就可以分出低中高水平的程序员对问题的处置方式](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483721&idx=1&sn=ae0af61c33fbd515943a8523acbddfe0&chksm=a698720491effb122e53f8308024c1218da04381f8106dc78ba738869d332b132e61c186e42b&token=1260076125&lang=zh_CN#rd)

- [C#8.0之后接口已经不再单纯了，我懵逼了！](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487047&idx=2&sn=4e37be491ae28676e36a55c7d5451a5d&chksm=a6987d0a91eff41c8d4fe891548aabd8c3c4b680195b4048fee4f30e09c06c54b22e50ef4a69&token=1961578048&lang=zh_CN#rd)

- [非常简单的string驻留池，你对它真的了解吗](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483754&idx=1&sn=b901fee371a4aeb799337520b35d9bfb&chksm=a698722791effb31c3806b95efe08c30dba630cd22bee6cd87761239b09e36295af488a7a994&token=1260076125&lang=zh_CN#rd)

- [从GC的SuppressFinalize方法带你深刻认识Finalize底层运行机制](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483758&idx=1&sn=415a5d4650e3363b0c9df8126aa529cc&chksm=a698722391effb35f068b09f137450f0084be57d44111540de71d4cc75463fc7c7b14789c667&token=1260076125&lang=zh_CN#rd)

- [面向接口编程，你考虑过性能吗？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483766&idx=1&sn=6b639499cf910587227bf8ed576f557c&chksm=a698723b91effb2d7925c6740eaccc347c42e7ec062ccbefce3620b6a2588e3aec380c1c7c8a&token=1260076125&lang=zh_CN#rd)

- [内存迟迟下不去，可能你就差一个GC.Collect](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483788&idx=1&sn=5643b128ef64168bdbd231a32d955c67&chksm=a69872c191effbd7513eaf65453d3305c2bc9a01f180ae99ed1fd512585911f4b4a805258bc8&token=1260076125&lang=zh_CN#rd)

- [不要把异常当做业务逻辑，这性能可能你无法承受](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483801&idx=1&sn=255f7b548a5c6b2a124c2adc9a7fff17&chksm=a69872d491effbc2d10ef4f684187144f4a7a2fdea79b17c554910d9e15d0dfaf1d48803d835&token=1260076125&lang=zh_CN#rd)

- [List的扩容机制，你真的明白吗？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483934&idx=1&sn=1e37bd686ba5b4e0e1a41a836258f126&chksm=a698715391eff845c79db6badfb45f63a926d5bfd0d450276661bd7e7cc67ffbdc81fe30fca9&token=1260076125&lang=zh_CN#rd)

- [追了多年的开发框架，你还认识指针吗？](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247483823&idx=1&sn=b1c6155b16283a99a9be855c57c13b8e&chksm=a69872e291effbf404f89ec538d28d5b1cf4ed2786f3feb43d17db985639b4ed24d7c5edd55f&token=1098575339&lang=zh_CN#rd)

- [自定义值类型一定不要忘了重写Equals，否则性能和空间双双堪忧](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247484027&idx=1&sn=5af5f193b594ef57468d3cb2e423c1cc&chksm=a698713691eff820939fc493dd619f000858a90d7c911583e0af052a517307d236f9eccd847c&token=1742856040&lang=zh_CN#rd)

- [C# 中的 ref 已经被放开，或许你已经不认识了](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487484&idx=1&sn=4644c2ce523ba8c40ae995bf2db3fbb5&chksm=a6987cb191eff5a7cd69b887188eb22e34fe1797e6e699d90078b1c8d2165014936a480b1492&token=2136785246&lang=zh_CN#rd)

- [C# Span 源码解读和应用实践](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487593&idx=1&sn=17a1244733c5f84ee7318b8de01ab919&chksm=a698632491efea32d731ccc51c84780bf1418778d5decbcb3d25f7eda5a1fe006088ea2db35f&token=1806526632&lang=zh_CN#rd)

- [用 Span 对 C# 进程中三大内存区域进行统一访问 ，太厉害了！](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487097&idx=2&sn=c06dd9c7b4aac9c397c988ebffbfd497&chksm=a6987d3491eff42224de36fd9d3933993fa7334ff2e987af4744fe0124911e8ae30123d84b7d&token=1961578048&lang=zh_CN#rd)

- [一个 Task 不够，又来一个 ValueTask ，真的学懵了！](https://mp.weixin.qq.com/s?__biz=MjM5MzI5Mzg1OA==&mid=2247487538&idx=2&sn=542088a51ee8da815828951a411694d5&chksm=a698637f91efea69ae36e9370d9bc7562fdfb63d34ddf4eb3b81d9c53499b889be2253e0553e&token=1806526632&lang=zh_CN#rd)




### 我的其他平台账号


* 博客园   https://www.cnblogs.com/huangxincheng

* 知乎    https://www.zhihu.com/people/ixchuang

* B站     https://space.bilibili.com/409524162

* 掘金   https://juejin.im/user/1380642337074718

* 思否   https://segmentfault.com/u/huangxincheng


**微信搜索： 一线码农聊技术  或 dotnetfly**

<a name="公众号"></a>


![](https://i.loli.net/2020/09/23/fgLUVn3YSIDWQpK.png)