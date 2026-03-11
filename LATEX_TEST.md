# LaTeX 渲染测试

## 行内公式测试

爱因斯坦质能方程: $E = mc^2$

勾股定理: $a^2 + b^2 = c^2$

二次方程求根公式: $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

圆的面积: $A = \pi r^2$

## 块级公式测试

欧拉公式:
$$
e^{i\pi} + 1 = 0
$$

高斯积分:
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

巴塞尔问题:
$$
\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}
$$

矩阵:
$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
$$

分段函数:
$$
f(x) = \begin{cases}
x^2 & \text{if } x \geq 0 \\
-x^2 & \text{if } x < 0
\end{cases}
$$

## 混合测试

在量子力学中,薛定谔方程 $i\hbar\frac{\partial}{\partial t}\Psi = \hat{H}\Psi$ 描述了量子系统的演化。

麦克斯韦方程组:
$$
\begin{aligned}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\epsilon_0} \\
\nabla \cdot \mathbf{B} &= 0 \\
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0\mathbf{J} + \mu_0\epsilon_0\frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
$$

## 测试说明

如果你能看到上面的数学公式被正确渲染(而不是原始的 LaTeX 代码),说明 LaTeX 渲染功能已经成功启用!
