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

### embedding  
1.[关于embedding-深度学习基本操作](https://www.cnblogs.com/ljygoodgoodstudydaydayup/p/10839983.html)  

### Item2Vec  
1.[推荐算法商品相似度-Item2Vec](https://zhuanlan.zhihu.com/p/177031008)  




参考资料：  
https://github.com/PaddlePaddle/PaddleRec  
https://www.jianshu.com/u/c5df9e229a67
