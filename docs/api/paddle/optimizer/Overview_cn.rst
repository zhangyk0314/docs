.. _cn_overview_optimizer:

paddle.optimizer
---------------------

paddle.optimizer 目录下包含飞桨框架支持的优化器算法相关的API与学习率衰减相关的API。具体如下：

-  :ref:`优化器算法相关API <about_optimizer>`
-  :ref:`学习率下降相关API <about_lr>`



.. _about_optimizer:

优化器算法相关API
::::::::::::::::::::

.. csv-table::
    :header: "API名称", "API功能"
    :widths: 10, 30

    " :ref:`Adadelta <cn_api_paddle_optimizer_Adadelta>` ", "Adadelta优化器"
    " :ref:`Adagrad <cn_api_paddle_optimizer_Adagrad>` ", "Adagrad优化器"
    " :ref:`Adam <cn_api_paddle_optimizer_Adam>` ", "Adam优化器"
    " :ref:`Adamax <cn_api_paddle_optimizer_Adamax>` ", "Adamax优化器"
    " :ref:`AdamW <cn_api_paddle_optimizer_AdamW>` ", "AdamW优化器"
    " :ref:`Lamb <cn_api_paddle_optimizer_Lamb>` ", "Lamb优化器"
    " :ref:`Momentum <cn_api_paddle_optimizer_Momentum>` ", "Momentum优化器"
    " :ref:`Optimizer <cn_api_paddle_optimizer_Optimizer>` ", "飞桨框架优化器基类"
    " :ref:`RMSProp <cn_api_paddle_optimizer_RMSProp>` ", "RMSProp优化器"
    " :ref:`SGD <cn_api_paddle_optimizer_SGD>` ", "SGD优化器"
    
.. _about_lr:

学习率衰减相关API
:::::::::::::::::::::::

.. csv-table::
    :header: "API名称", "API功能"
    :widths: 10, 30

    " :ref:`CosineAnnealingDecay <cn_api_paddle_optimizer_lr_CosineAnnealingDecay>` ", "Cosine Annealing学习率衰减"
    " :ref:`ExponentialDecay <cn_api_paddle_optimizer_lr_ExponentialDecay>` ", "Exponential 学习率衰减"
    " :ref:`InverseTimeDecay <cn_api_paddle_optimizer_lr_InverseTimeDecay>` ", "Inverse Time 学习率衰减"
    " :ref:`LRScheduler <cn_api_paddle_optimizer_lr_LRScheduler>` ", "学习率衰减的基类"
    " :ref:`LambdaDecay <cn_api_paddle_optimizer_lr_LambdaDecay>` ", "Lambda 学习率衰减"
    " :ref:`LinearWarmup <cn_api_paddle_optimizer_lr_LinearWarmup>` ", "Linear Warmup 学习率衰减"
    " :ref:`MultiStepDecay <cn_api_paddle_optimizer_lr_MultiStepDecay>` ", "MultiStep 学习率衰减"
    " :ref:`NaturalExpDecay <cn_api_paddle_optimizer_lr_NaturalExpDecay>` ", "NatualExp 学习率衰减"
    " :ref:`NoamDecay <cn_api_paddle_optimizer_lr_NoamDecay>` ", "Norm学习率衰减"
    " :ref:`PiecewiseDecay <cn_api_paddle_optimizer_lr_PiecewiseDecay>` ", "分段设置学习率"
    " :ref:`PolynomialDecay <cn_api_paddle_optimizer_lr_scheduler_PolynomialDecay>` ", "多项式学习率衰减"
    " :ref:`ReduceOnPlateau <cn_api_paddle_optimizer_lr_ReduceOnPlateau>` ", "loss 自适应学习率衰减"
    " :ref:`StepDecay <cn_api_paddle_optimizer_lr_StepDecay>` ", "按指定间隔轮数学习率衰减"
    " :ref:`MultiplicativeDecay <cn_api_paddle_optimizer_lr_MultiplicativeDecay>` ", "根据lambda函数进行学习率衰减"
    " :ref:`OneCycleLR <cn_api_paddle_optimizer_lr_OneCycleLR>` ", "One Cycle学习率衰减"
    " :ref:`CyclicLR <cn_api_paddle_optimizer_lr_CyclicLR>` ", "Cyclic学习率衰减"
