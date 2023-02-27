
> **命题.** 极限 ${\displaystyle \gamma = \lim \limits _{n \rightarrow \infty} a_n = \lim \limits _{n \rightarrow \infty} \left[ \left( \sum\limits_{k = 1}^n \frac{1}{k}  \right)- \ln n \right]}$ 存在。
>
> 证明：根据 [[课程笔记/数学基础/不等式基础.md|调和级数不等式]] 不等式可知
>
> $$\lim \limits _{n \rightarrow \infty}   \ln \frac{n+1}{n}= 0 < \gamma < 1 $$
>
> 而根据 [[课程笔记/数学基础/不等式基础.md|对数不等式]] 可知 ${\displaystyle a_{n+1} - a_n = \frac{1}{n+1} - \ln(n+1) + \ln n = \frac{1}{n+1} - \ln (1 + \frac{1}{n}) < 0}$ ，因此 $a_n$ 单调递减有下界，故收敛。


> **定义**(Euler 常数)
>
> 定义 ${\displaystyle \gamma = \lim \limits _{n \rightarrow \infty} \left[ \left( \sum\limits_{k = 1}^n \frac{1}{k} \right) - \ln n \right] }$ 为 Euler 常数。

> **推论.** 调和级数满足如下性质
>
> $$ \lim \limits _{n \rightarrow \infty} \frac{1 + \frac{1}{2} + \cdots + \frac{1}{n}}{\ln n} = 1 $$
>
> 证明：由于 $\sum\limits_{k = 1}^n \frac{1}{k} = \ln n + \gamma + o(1)$，显然。


