


Prove:$$\lim_{ n \to \infty } \sum_{k=0}^{n} \frac{1}{k!}=e.$$

Compute that:
$$
\begin{align}

e-\lim_{ n \to \infty } \sum_{k=0}^{n} \frac{1}{k!} &= \lim_{ n \to \infty } \left[  \left(  1+\frac{1}{n}  \right)^{n}-\sum_{k=0}^{n} \frac{1}{k!} \right] \\
&= \lim_{ n \to \infty } \sum_{k=2}^{n} \left( \frac{C_{n}^{k}}{n^k} - \frac{1}{k!} \right) \\
&=\lim_{ n \to \infty } \sum_{k=2}^{n} \frac{1}{k!}\left( \frac{\frac{n!}{(n-k)!}-n^k}{ n^k} \right) \\
&=\lim_{ n \to \infty } \sum_{k=2}^{n} \frac{k(k-1)}{k!} \left[ -\frac{1}{n}+O\left( \frac{1}{n} \right) \right] \\
&=-\lim_{ n \to \infty } \frac{1}{n} \sum_{k=2}^{n} \frac{k(k-1)}{k!}+\lim_{ n \to \infty }  \frac{O\left( \frac{1}{n} \right)}{\frac{1}{n}} \\
 \\
\text{Notice that} \lim_{ n \to \infty }  \sum_{k=2}^{n} \frac{k(k-1)}{k!}  \text{ converges},so \\
 \\
e-\lim_{ n \to \infty } \sum_{k=0}^{n} \frac{1}{k!}=0
\end{align}
$$
Q.E.D.
Then prove
$$
e - \sum_{k=0}^{n} \frac{1}{k!} < \frac{1}{n!n}.
$$

Let 
$$
x_{n} =\frac{1}{n!n}+\sum_{k=0}^{n} \frac{1}{k!} 
$$
Compute that 
$$
+\frac{~*}{9}
$$
Thus $\{x_{n}\}$ is monotonically decreasing,and clearly,
$$
\lim_{ n \to \infty } x_{n}=e
$$
which implies that $x_{n}>e$.

