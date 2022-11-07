本文为周志华《机器学习》的学习笔记，记录了本人在学习这本书的过程中的理解思路以及一些有助于消化书内容的拓展知识，笔记中参考了许多网上的大牛经典博客以及李航《统计学习》的内容，向前辈们和知识致敬！

- 目录
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(1)--%E7%BB%AA%E8%AE%BA.md'>学习笔记(1)--绪论</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(2)--%E6%80%A7%E8%83%BD%E5%BA%A6%E9%87%8F.md'>学习笔记(2)--性能度量</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(3)--%E5%81%87%E8%AE%BE%E6%A3%80%E9%AA%8C%26%E6%96%B9%E5%B7%AE%26%E5%81%8F%E5%B7%AE.md'>学习笔记(3)--假设检验%26方差%26偏差</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(4)--%E7%BA%BF%E6%80%A7%E6%A8%A1%E5%9E%8B.md'>学习笔记(4)--线性模型</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(5)--%E5%86%B3%E7%AD%96%E6%A0%91.md'>学习笔记(5)--决策树</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(6)--%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C.md'>学习笔记(6)--神经网络</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(7)--%E6%94%AF%E6%8C%81%E5%90%91%E9%87%8F%E6%9C%BA.md'>学习笔记(7)--支持向量机</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(8)--%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%88%86%E7%B1%BB%E5%99%A8.md'>学习笔记(8)--贝叶斯分类器</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(10)--%E9%9B%86%E6%88%90%E5%AD%A6%E4%B9%A0.md'>学习笔记(10)--集成学习</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(11)--%E8%81%9A%E7%B1%BB.md'>学习笔记(11)--聚类</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(12)--%E9%99%8D%E7%BB%B4%E4%B8%8E%E5%BA%A6%E9%87%8F%E5%AD%A6%E4%B9%A0.md'>学习笔记(12)--降维与度量学习</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(13)--%E7%89%B9%E5%BE%81%E9%80%89%E6%8B%A9%E4%B8%8E%E7%A8%80%E7%96%8F%E5%AD%A6%E4%B9%A0.md'>学习笔记(13)--特征选择与稀疏学习</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(14)--%E8%AE%A1%E7%AE%97%E5%AD%A6%E4%B9%A0%E7%90%86%E8%AE%BA.md'>学习笔记(14)--计算学习理论</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(15)--%E5%8D%8A%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0.md'>学习笔记(15)--半监督学习</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(16)--%E6%A6%82%E7%8E%87%E5%9B%BE%E6%A8%A1%E5%9E%8B.md'>学习笔记(16)--概率图模型</a></i></small>
  * <small><i><a href='https://github.com/AronTian2018/Machine-learning-learning-notes/blob/master/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8AMachine%20Learning%E3%80%8B%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0(17)--%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0.md'>学习笔记(17)--强化学习</a></i></small>


