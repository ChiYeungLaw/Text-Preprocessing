# SkipGramNS文件

实现了Word2Vec的SkipGram Negative Sampling模型，并基于文本数据集`ptb.train.txt`进行训练，得到词相似性结果为：

```python
get_similar_k('woman', 4, (net[0], net[1]))
```

    cosine similarity=0.411: her.
    cosine similarity=0.404: mother.
    cosine similarity=0.395: women.
    cosine similarity=0.388: pregnant.

# CBOW_NS文件

实现了Word2Vec的CBOW Negative Sampling模型，并基于文本数据集`ptb.train.txt`进行训练，得到词相似性结果为：

```python
get_similarity("mother", 4, (net[0], net[1]))
```

    cosine sim=0.426: husband.
    cosine sim=0.401: her.
    cosine sim=0.372: woman.
    cosine sim=0.349: respectable.
