# 推荐系统  


### wide&deep
《Wide & Deep Learning for Recommender Systems》是Google 2016年发布的推荐框架，wide&deep设计了一种融合浅层（wide）模型和深层（deep）模型进行联合训练的框架，综合利用浅层模型的记忆能力和深层模型的泛化能力，实现单模型对推荐系统准确性和扩展性的兼顾。从推荐效果和服务性能两方面进行评价：

效果上，在Google Play 进行线上A/B实验，wide&deep模型相比高度优化的Wide浅层模型，app下载率+3.9%。相比deep模型也有一定提升。
性能上，通过切分一次请求需要处理的app 的Batch size为更小的size，并利用多线程并行请求达到提高处理效率的目的。单次响应耗时从31ms下降到14ms。

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


https://github.com/PaddlePaddle/PaddleRec/tree/master/models/rank/deepfm


### din

   
   
   
      




参考资料：  
https://github.com/PaddlePaddle/PaddleRec  
https://www.jianshu.com/u/c5df9e229a67
