
> **定理**(Wallis 公式)
>
> 当 $n \rightarrow +\infty$ 时，${\displaystyle \frac{(2n)!!}{(2n-1)!!} \sim \sqrt{n\pi}}$，更具体地，
>
> $$ \lim \limits _{n \rightarrow \infty} \left[ \frac{(2n)!!}{(2n-1)!!}  \right]^2\frac{1}{2n+1} = \frac{\pi}{2} $$
>
> 证明：根据 $\sin^{2n+1}x < \sin^{2n}x < \sin^{2n-1}x$ 得到
>
> $$\displaystyle \int_0^{\frac{\pi}{2}}\sin^{2n+1}x \mathrm{d}x < \int_0^{\frac{\pi}{2}} \sin^{2n}x \mathrm{d}x < \int_0^{\frac{\pi}{2}} \sin^{2n-1}x \mathrm{d} x$$
>
> 根据 Wallis 积分公式得到下面不等式
>
> $$\frac{(2n)!!}{(2n+1)!!} < \frac{(2n-1)!!}{(2n)!!}\frac{\pi}{2} < \frac{(2n-2)!!}{(2n-1)!!} $$
>
> 构造 $A_n,B_n$
>
> $$A_n := \left[ \frac{(2n)!!}{(2n-1)!!} \right]^2 \frac{1}{2n+1} < \frac{\pi}{2} < \left[ \frac{(2n)!!}{(2n-1)!!} \right]^2 \frac{1}{2n} := B_n $$
>
> 得到
>
> $$\displaystyle B_n - A_n = \left[ \frac{(2n)!!}{(2n-1)!!} \right]^2 \frac{1}{2n(2n - 1)} = A_n \cdot \frac{1}{2n} < \frac{\pi}{2}\frac{1}{2n} \rightarrow 0$$
>
> 因此 $\lim \limits _{n \rightarrow \infty} A_n = \lim \limits _{n \rightarrow \infty} B_n = \frac{\pi}{2}$。
