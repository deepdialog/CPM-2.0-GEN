# 测试CPM-2.0的生成

悟道源代码：[https://github.com/TsinghuaAI/CPM-2-Finetune](https://github.com/TsinghuaAI/CPM-2-Finetune)

注意T5/mT5模型本身不太适合类似GPT-3的生成，应该更适合进行prompt-fintune/soft-prompt-finetune

模型下载：[https://wudaoai.cn/model/detail/CPM%E7%B3%BB%E5%88%97#download](https://wudaoai.cn/model/detail/CPM%E7%B3%BB%E5%88%97#download)

因为模型本身协议限制，这里不提供任何模型或者转换后模型下载，请自行申请下载

## 本REPO的食用方法：

建议主要参考[to_tensorflow.ipynb](to_tensorflow.ipynb)这个notebook，使用基于`transformers`的方法，读取、测试模型

至于用`transfomers`转换之后能干嘛，请参考关于[transformers mT5的相关文档](https://huggingface.co/transformers/model_doc/mt5.html)，以及其他文章
