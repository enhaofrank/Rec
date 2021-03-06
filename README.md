# 推荐系统  


### wide&deep
《Wide & Deep Learning for Recommender Systems》是Google 2016年发布的推荐框架，wide&deep设计了一种融合浅层（wide）模型和深层（deep）模型进行联合训练的框架，综合利用浅层模型的记忆能力和深层模型的泛化能力，实现单模型对推荐系统准确性和扩展性的兼顾。从推荐效果和服务性能两方面进行评价：效果上，在Google Play 进行线上A/B实验，wide&deep模型相比高度优化的Wide浅层模型，app下载率+3.9%。相比deep模型也有一定提升。性能上，通过切分一次请求需要处理的app 的Batch size为更小的size，并利用多线程并行请求达到提高处理效率的目的。单次响应耗时从31ms下降到14ms。

https://github.com/PaddlePaddle/PaddleRec/tree/master/models/rank/wide_deep    

1.[看Google如何实现Wide & Deep模型(1)](https://zhuanlan.zhihu.com/p/47293765?utm_source=wechat_session)  
2.[看Google如何实现Wide & Deep模型（2.1）](https://zhuanlan.zhihu.com/p/47965313)  
3.[看Google如何实现Wide & Deep模型（2.2）](https://zhuanlan.zhihu.com/p/47970601)  
4.[看Google如何实现Wide & Deep模型(3)](https://zhuanlan.zhihu.com/p/48251812)  
5.[Wide&Deep模型原理与实现](https://zhuanlan.zhihu.com/p/132708525)  
6.[WIDE & DEEP模型的理解及实战(TENSORFLOW)](https://www.freesion.com/article/2681421296/)  
7.[Wide&Deep模型的8个实战细节](http://www.360doc.com/content/20/1125/22/7673502_947841455.shtml)  
8.[wide&deep 在贝壳推荐场景的实践](https://mp.weixin.qq.com/s?__biz=MzI2ODA3NjcwMw==&mid=2247483659&idx=1&sn=deb9c5e22eabd3c52d2418150a40c68a&chksm=eaf452fbdd83dbed0d6de5e847e8569bdc0a75ef6aa23fcaa9c5586a2572cd0e216f499a529b&scene=21#wechat_redirect)  
9.[WIDE & DEEP模型的理解及实战(TENSORFLOW)](https://www.freesion.com/article/2681421296/)  

### DeepFM  
1.[推荐算法不可不看的DeepFM模型](https://blog.51cto.com/15023245/2558681)  
2.[DeepFM实践](https://zhuanlan.zhihu.com/p/137894818)  

https://github.com/PaddlePaddle/PaddleRec/tree/master/models/rank/deepfm

### 协同过滤  
1.[协同过滤推荐算法总结](https://www.cnblogs.com/pinard/p/6349233.html)  
2.[基于协同过滤（CF）算法的推荐系统](https://cloud.tencent.com/developer/article/1604197)  
3.[协同过滤推荐算法（一）原理与实现](https://blog.csdn.net/likeyou1314918273/article/details/89607596)  
4.[协同过滤推荐算法总结](https://www.cnblogs.com/pinard/p/6349233.html)  

### din  
1.[推荐系统中的注意力机制——阿里深度兴趣网络（DIN）](https://zhuanlan.zhihu.com/p/51623339)  
2.[推荐系统---深度兴趣网络DIN&DIEN](https://www.cnblogs.com/zhaoweiblog/p/10268763.html)  
3.[注意力机制在深度推荐算法中的应用之DIN模型](https://zhuanlan.zhihu.com/p/139417423)  
4.[捕捉用户兴趣演化--DIEN论文解读](https://www.msedt.com/infoflow/details/1067)  
5.[基于用户兴趣的商品推荐算法--DIN论文解读](https://blog.csdn.net/qzh459927216/article/details/111382916)  
   
### 总结类文章  
1.[推荐算法相关](https://www.cnblogs.com/code2one/p/10366238.html)  
2.[推荐系统遇上深度学习](http://ddrv.cn/a/40050)  
3.[常用召回和排序技术](https://dy.163.com/article/fa48umia0532e0uf.html)  
4.[推荐引擎：召回和排序常见算法模型](http://www.bdata-cap.com/newsinfo/1854875.html)  
5.[推荐算法总结（召回+排序+工程化）](https://blog.csdn.net/qq_34219959/article/details/104495432)  

### embedding  
1.[关于embedding-深度学习基本操作](https://www.cnblogs.com/ljygoodgoodstudydaydayup/p/10839983.html)  
2.[生动详解deepwalk算法（graph embedding）](https://zhuanlan.zhihu.com/p/58105731)  
3.[万物皆可Embedding之Deepwalk算法解读](http://bbs.cnaiplus.com/thread-73263-1-1.html)

### Item2Vec  
1.[推荐算法商品相似度-Item2Vec](https://zhuanlan.zhihu.com/p/177031008)  

### FM算法  
1.[FM算法解析](https://zhuanlan.zhihu.com/p/37963267)  
2.[FM系列算法解读(FM+FFM+DeepFM)](https://blog.csdn.net/hiwallace/article/details/81333604)  
3.[FFM算法原理及Bi-FFM算法实现](https://zhuanlan.zhihu.com/p/145928996?utm_source=wechat_session)  
4.[深入FFM原理与实践](https://tech.meituan.com/2016/03/03/deep-understanding-of-ffm-principles-and-practices.html)  
5.[FM：推荐算法中的瑞士军刀](https://mp.weixin.qq.com/s?__biz=MjM5ODkzMzMwMQ==&mid=2650419793&idx=2&sn=50541c9e82190092175d03c292911cb7&chksm=becdb40b89ba3d1d0f35559926befc4fe5bacf6fada807a1b4ccf402a873d0e3c5ac65bc25d2&mpshare=1&scene=1&srcid=0113fPtZNSLxnatnE3fpw2nP&sharer_sharetime=1610494034534&sharer_shareid=546bd079429f4880a353b991a015fc00&key=3f904187a8d5ad8ce426adfb518640d40aa18f047193da8f16c2ec02ed6c7096d00e740d0b8a2647284bb10cf55d5dcbd2d8cc3c7841263f0adcaf8fb4614efd1676a59bc05c38e9fb92561a5fd2a20124efaa903f11969a5d502d587f1bccfa09f2578865c4b19634b07ae99f6345dfad3517458de7597e9ab893bbe1f922a6&ascene=1&uin=NjQ3MTEwMDA1&devicetype=Windows+10+x64&version=6209007b&lang=zh_CN&exportkey=AV2hmHxDzwF4BLL84%2BVRiig%3D&pass_ticket=lw0hW878LUMPybL6%2BpSFWryA6LlW3eYuIT%2FepYyfYcwQ%2FpVw6fmXAMwc0ixd6WKo&wx_header=0)  

### 用户画像
1.[从0-1构建用户画像体系](https://zhuanlan.zhihu.com/p/138203827)  

参考资料：  
https://github.com/PaddlePaddle/PaddleRec  
https://www.jianshu.com/u/c5df9e229a67
