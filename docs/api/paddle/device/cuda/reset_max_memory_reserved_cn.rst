.. _cn_api_paddle_device_cuda_reset_max_memory_reserved:

reset_max_memory_reserved
-------------------------------

.. py:function:: paddle.device.cuda.reset_max_memory_reserved(device=None)

重置给定设备上由 Allocator 管理的显存峰值统计。

参数
::::::::

**device** (paddle.CUDAPlace|int|str，可选) - 设备、设备 ID 或形如 ``gpu:x`` 的设备名称。如果 ``device`` 为 None，则 ``device`` 为当前的设备。默认值为 None。


返回
::::::::

None

代码示例
::::::::

COPY-FROM: paddle.device.cuda.reset_max_memory_reserved
