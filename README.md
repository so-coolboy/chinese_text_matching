# chinese_text_matching
使用colab运行了一些文本匹配的模型代码。这里主要是做相似度匹配,也就是对sentences1和sentences2，如果是相似的，就是1，如果是不相似的，就是0，转化成了分类问题。

# 参考
主要参考了以下三个github
- https://github.com/wangle1218/deep_text_matching
- matchZoo:https://github.com/NTMC-Community/MatchZoo  
- https://github.com/terrifyzhao/text_matching

# 模型
- 基于表示的模型：DSSM模型、CDSSM模型
- 基于交互的模型：ARC-I模型、ATRC-II模型、MatchPyramid模型、mvlstm模型
- Attention有关的模型：BiMPM模型、ESIM模型
- Bert模型

# 数据
数据来源于https://github.com/terrifyzhao/text_matching  中使用的数据。因为是中文，因此输入的是子向量，嵌入使用keras的Embedding随机生成的，没有使用训练好的子向量。

# 模型
主要是为了学习模型的代码，因此没有进行相似的调参，有一些模型的实现与matchZoo不同，做了简化。
