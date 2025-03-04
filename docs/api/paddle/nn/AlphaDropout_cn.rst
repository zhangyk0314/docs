.. _cn_api_nn_AlphaDropout:

AlphaDropout
-------------------------------

.. py:function:: paddle.nn.AlphaDropout(p=0.5, name=None)

AlphaDropout是一种具有自归一化性质的dropout。均值为0，方差为1的输入，经过AlphaDropout计算之后，输出的均值和方差与输入保持一致。AlphaDropout通常与SELU激活函数组合使用。论文请参考：`Self-Normalizing Neural Networks <https://arxiv.org/abs/1706.02515>`_ 

在动态图模式下，请使用模型的 `eval()` 方法切换至测试阶段。

.. note::
   对应的 `functional方法` 请参考：:ref:`cn_api_nn_functional_alpha_dropout` 。

参数
:::::::::
 - **p** (float)：将输入节点置0的概率，即丢弃概率。默认：0.5。
 - **name** (str，可选) - 具体用法请参见 :ref:`api_guide_Name`，一般无需设置，默认值为 None。

返回
:::::::::
经过AlphaDropout之后的结果，与输入x形状相同的 `Tensor` 。

代码示例
:::::::::

COPY-FROM: paddle.nn.AlphaDropout