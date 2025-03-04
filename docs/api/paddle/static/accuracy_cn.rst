.. _cn_api_fluid_layers_accuracy:

accuracy
-------------------------------

.. py:function:: paddle.static.accuracy(input, label, k=1, correct=None, total=None)




accuracy layer。参考 https://en.wikipedia.org/wiki/Precision_and_recall

使用输入和标签计算准确率。如果正确的标签在topk个预测值里，则计算结果加1。注意：输出正确率的类型由input类型决定，input和lable的类型可以不一样。

参数
::::::::::::

    - **input** (Tensor|LoDTensor)-数据类型为float32,float64。输入为网络的预测值。shape为 ``[sample_number, class_dim]`` 。
    - **label** (Tensor|LoDTensor)-数据类型为int64，int32。输入为数据集的标签。shape为 ``[sample_number, 1]`` 。
    - **k** (int64|int32) - 取每个类别中k个预测值用于计算。
    - **correct** (int64|int32)-正确预测值的个数。
    - **total** (int64|int32)-总共的预测值。

返回
::::::::::::
 Tensor，计算出来的正确率，数据类型为float32。


代码示例
::::::::::::

COPY-FROM: paddle.static.accuracy