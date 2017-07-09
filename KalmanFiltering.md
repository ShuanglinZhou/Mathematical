# 卡尔曼滤波

## 卡尔曼滤波基本原理

思考一下下面简单的问题，给定一组噪声测量值，$z_1, z_2, z_3 ... z_k$，不连续的未知数，我们假设下面的模型

$$
z_k = x + v_k
$$

并且$v_k$是对应的噪声，大量数据最小二乘拟合

$$
\hat x_k = \frac{1}{k} \sum_{i=1}^{k} = \text {estimate of $x$ after $k$ measurement ts}
$$



