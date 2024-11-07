$y = \frac{e^x - e^{-x}}{2} = \frac{e^x}{2} -\frac{e^{-x}}{2}$
#### Ex 8
$$ \begin{align}
(ii) \quad &\lim\limits_{x \rightarrow 0} \frac{sin^2(3x)}{x \cdot tan(\pi-4x)} = \lim\limits_{x \rightarrow 0} 3 \cdot \frac{sin(x)}{3x} \cdot \frac{sin(3x)}{tan(-4x)} \\
& \lim\limits_{x \rightarrow 0} 3 \cdot \frac{sin(3x)}{3x} \cdot \frac{sin(3x)}{3x} \cdot -\frac{4x}{sin(-4x)} \cdot cos(-4x)\cdot \frac{3}{-4} \\
&= -\frac{9}{4} \cdot 1 \cdot 1\cdot \frac{1}{1} \cdot 1 = -\frac{9}{4}
\end{align}
$$

$$
\begin{align}
(v) &\lim\limits_{x \rightarrow 3\pi} \frac{tan^2\left( \frac{t}{3} \right)}{1 + cos\left( \frac{t}{3} \right)} =\lim\limits_{x \rightarrow 3\pi} \frac{sin^2\left( \frac{t}{3} \right)}{cos^2\left( \frac{t}{3} \right)\left( 1 +cos\left( \frac{t}{3} \right) \right)} \\
&\lim\limits_{x \rightarrow 3\pi} \frac{\left( 1 -cos^2\left( \frac{t}{3} \right) \right)}{cos^2\left( \frac{t}{3} \right)\left( 1 + cos\left( \frac{t}{3} \right) \right)} \\
& \lim\limits_{x \rightarrow 3\pi} \frac{\left(1-cos^2\left( \frac{t}{3} \right) \right)\left( 1 + cos\left( \frac{t}{3} \right) \right)}{cos^2\left( \frac{t}{3} \right)\left( 1 + cos\left( \frac{t}{3} \right) \right)} \\
& = \frac{2}{1} = 2

\end{align}
$$

$$
\begin{align}
(vi) &\lim\limits_{x \rightarrow \frac{\pi}{2}} \frac{\sqrt{1 + cos(x)} -1}{x-\frac{\pi}{2}} = \lim\limits_{x \rightarrow \frac{\pi}{2}} \frac{cos(x)}{\left( x-\frac{\pi}{2} \right)(\sqrt{1 + cos(x)} + 1)} \\
&\lim\limits_{x \rightarrow \frac{\pi}{2}} \frac{sin\left( x + \frac{\pi}{2} \right)}{\left( x-\frac{\pi}{2} \right)(\sqrt{1 + cos(x)} + 1)} = \lim\limits_{x \rightarrow \frac{\pi}{2}}
\frac{sin\left( \pi - \left( x + \frac{\pi}{2} \right) \right)}{\left( x-\frac{\pi}{2} \right)(\sqrt{1 + cos(x)} +1)} \\
&=\frac{1}{-2} = - \frac{1}{2} \\
\end{align}
$$

#### Ex 9
$$
\begin{align}
&\lim\limits_{x \rightarrow \pm\infty} \frac{1}{\sqrt{x^2 + 3x}-\sqrt{x^2-2x}} \cdot\frac{\sqrt{x^2 + 3x} + \sqrt{x^2 -2x}}{\sqrt{x^2 + 3x} + \sqrt{x^2 -2x}} \\ \\

&= \lim\limits_{x \rightarrow \pm\infty} \frac{\sqrt{x^2 + 3x} + \sqrt{x^2-2x}}{x^2+3x-x^2 + 2x} \\ \\

&= \lim\limits_{x \rightarrow \pm\infty} \sqrt{x^2} \frac{\sqrt{1 + \frac{3}{x}} + \sqrt{1 -\frac{2}{x}}}{5x} \\ \\

&\text{Pour x} \mapsto \infty : \lim\limits_{x \rightarrow \infty} \frac{\sqrt{1+\frac{3}{x}} + \sqrt{1 -\frac{2}{x}}}{5}=\frac{2}{5} \\
&\text{Pour x} \mapsto -\infty : \lim\limits_{x \rightarrow -\infty} \frac{-\sqrt{1+\frac{3}{x}} + \sqrt{1 -\frac{2}{x}}}{5}=-\frac{2}{5} \\

\end{align}
$$

#### Ex12
$$
\begin{gather}
f(x) = \sqrt{x^2 -4x} = \sqrt{x(x-4)} \quad D(f) ]-\infty,0]\cup[4,\infty[\\ \\
A.H : \lim\limits_{x \rightarrow \pm\infty} f(x) = +\infty \\
A.V : \lim\limits_{x \rightarrow 0^-} f(x) = 0 \lim\limits_{x \rightarrow 4^+} f(x) = 0 \\
A.O : \lim\limits_{x \rightarrow \pm\infty} \frac{f(x)}{x} = \frac{\sqrt{x^2-4x}}{x} = \lim\limits_{x \rightarrow \pm\infty}
 |x| \frac{\sqrt{\left( 1-\frac{4}{x} \right)}}{x} \\
1 \text{ vers } +\infty \\
-1 \text{ vers } -\infty 

\end{gather}
$$