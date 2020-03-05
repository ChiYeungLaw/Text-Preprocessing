基于Pytorch实现了GloVe模型，并基于文本数据集`ptb.train.txt`进行训练，得到词相似性结果为：

```python
get_similar("has", 3, glove.W1.weight + glove.W2.weight)
```

    cosine sim=0.646; had
    cosine sim=0.612; been
    cosine sim=0.584; have
