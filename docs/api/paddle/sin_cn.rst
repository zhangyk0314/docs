.. _cn_api_fluid_layers_sin:

sin
-------------------------------

.. py:function:: paddle.sin(x, name=None)




计算输入的正弦值。

参数
::::::::::::

    - **x** (Tensor) - 支持任意维度的Tensor。数据类型为float32，float64或float16。
    - **name** (str，可选) - 具体用法请参见 :ref:`api_guide_Name`，一般无需设置，默认值为 None。

返回
::::::::::::
返回类型为Tensor，数据类型同输入一致。

代码示例
::::::::::::

COPY-FROM: paddle.sin