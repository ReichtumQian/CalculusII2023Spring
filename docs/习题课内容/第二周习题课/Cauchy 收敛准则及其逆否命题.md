

- 如何记住 Cauchy 收敛准则逆否命题？

> **定理**(命题取否)
>
> 对于一个逻辑命题，将 $\forall, \exists$ 改为 $\exists, \forall$，并将最终结论取反，则获得其否命题。

> **例.**(Cauchy 收敛准则取否)
>
> - 原命题：${\displaystyle \sum\limits_{n = 1}^{+\infty} a_n}$ 收敛当且仅当 $\forall \epsilon > 0, \exists N > 0, \forall n > N, \forall p \in \mathbb{Z}^+$ 有
>
> $$ |S_{n+p} - S_n| < \epsilon$$
>
> - 逆否命题：${\displaystyle \sum\limits_{n = 1}^{+\infty}a_n}$ 发散当且仅当 $\exists \epsilon > 0, \forall N > 0, \exists n > N, \exists p \in \mathbb{Z}^+$ 使得
>
> $$ |S_{n+p} - S_n| \geq \epsilon$$

- 注意：先取的值不能与后取的值相关，例如 $\forall \epsilon, \exists N = p, \forall n > N, \forall p$ 这种取法是错误的。

## 调和级数相关

> (1) 证明 ${\displaystyle \sum\limits_{n = 1}^{+\infty} \frac{1}{n}}$ 发散
>
> (2) 证明 ${\displaystyle a_n = \sum\limits_{k = 1}^n \frac{1}{k} - \ln n}$ 极限存在
>
> (3) 证明 ${\displaystyle \lim \limits _{n \rightarrow +\infty} \frac{1 + \frac{1}{2} + \cdots + \frac{1}{n}}{\ln n} = 1}$


