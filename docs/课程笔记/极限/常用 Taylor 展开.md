
$$
\begin{array}{ll}
e^x = \sum\limits_{n = 0 }^{\infty}\frac{x^n}{n!}& \ln(1 + x) = \sum\limits_{n = 1}^{\infty}(-1)^{n-1}\frac{x^n}{n} \\
\sin x = \sum\limits_{n = 0}^{\infty}(-1)^n \frac{x^{2n+1}}{(2n+1)!}& \cos x = \sum\limits_{n = 0}^{\infty}(-1)^n \frac{x^{2n}}{(2n)!} \\
\arcsin x =\sum\limits_{n = 0}^{\infty}\left( \frac{(2n)!}{2^{2n}(n!)^2} \right)\frac{x^{2n+1}}{2n+1} =  x + \frac{1}{6}x^3 + o(x^3) &\arctan x = \sum\limits_{n = 0}^{\infty} \frac{(-1)^nx^{2n+1}}{2n+1} = x - \frac{1}{3}x^3 + o(x^3) \\
\frac{1}{1+x} = \sum\limits_{n = 0}^{\infty}(-1)^n x^n&\frac{1}{1 - x} = \sum\limits_{n = 0}^{\infty}x^n \\
(1+x)^{\alpha} = 1 + \alpha x + \frac{\alpha(\alpha - 1)}{2}x^2 + o(x^2)&(1 + x)^{\alpha} = \sum\limits_{n = 0}^{\infty}{\alpha \choose n} x^n
\end{array}
$$


- $\arctan x = \sum\limits_{n = 0}^{\infty} \frac{(-1)^n x^{2n+1}}{2n+1}$

> 证明：由于 $\displaystyle (\arctan x)^{\prime} = \frac{1}{1 + x^2} = \sum\limits_{n = 0}^{\infty} (-1)^n x^{2n}$，因此逐项积分得到
>
> $$ \arctan x = \sum\limits_{n = 0}^{\infty} \frac{(-1)^n x^{2n+1}}{2n+1} $$

- $\displaystyle \ln(1+x) = \sum\limits_{n = 1}^{\infty}(-1)^{n-1} \frac{x^n}{n}$

> 证明：由于 $\displaystyle \left( \ln(1+x) \right)^{\prime} = \frac{1}{1+x} = \sum\limits_{n = 0}^{\infty} (-1)^n x^n$，因此逐项积分得到
>
> $$ \ln(1+x) = \sum\limits_{n = 0}^{\infty} (-1)^n \frac{x^{n+1}}{n+1} = \sum\limits_{n = 1}^{\infty} (-1)^{n-1} \frac{x^n}{n} $$
