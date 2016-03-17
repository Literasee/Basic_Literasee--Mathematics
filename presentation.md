# Basic Literasee
## Mathematics typesetting

---

## Mathematics typesetting

- [Literasee](http://literasee.io) supports math typesetting with [MathJax](https://www.mathjax.org/).
- Professional quality typeset mathematics as part of any web-based content one produces!
- Supported in both Report and Presentation formats.
- Accessible via standard [LaTeX](https://www.latex-project.org/) markup.

Note:
This will only display in the Notes window.

---

## In-line Math

===

- <p class="fragment">The cube root of $x$ is denoted $\sqrt[3]{x}$.</p>
- <p class="fragment">Let $x\_i = i$, then $\sum\_{i=1}^n x\_{i} = x\_1 + \cdots + x\_n = n(n-1)/2$.</p>
- <p class="fragment">By L'Hôpital's rule, $\lim\_{n \rightarrow \infty} \frac{2n + 5}{n} = 2$.</p>
- <p class="fragment">The Continuum Hypothesis implies: $2^{\aleph\_0} = \aleph\_1$.</p>
- <p class="fragment">Cauchy-Schwarz Inequality: $\left( \sum\_{k=1}^n a\_k b\_k \right)^2 \leq \left( \sum\_{k=1}^n a\_k^2 \right) \left( \sum\_{k=1}^n b\_k^2 \right)$.</p>

---

## Centered Math

===

### Basic limit notation:

$$
\lim\_{n \rightarrow \infty} \frac{2n + 5}{n} = 2
$$

===

### Stokes Theorem:

$$
\int\_{\partial \Omega} = \int\_\Omega d\omega
$$

===

### Three parameter logistic IRT model:

$$
p\_i (\theta) = c\_i + {1 - c\_i \over 1 + e^{-a\_i(\theta - b\_i)}}
$$

===

### A Cross Product Formula

$$\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\\\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\\\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0
\end{vmatrix}  $$

---

## Aligned Equations

===

The binomial expansion is given in Equation \eqref{eq:binomial}

$\begin{align} f(x, y) & = (x+y)^n \tag{1}\\\\ & = {n \choose 0} x^ny^0+ {n \choose 1} x^{n-1}y^1 + \cdots + {n \choose n} x^0y^n\tag{2} \label{eq:binomial}\\\\ \end{align}$

===

$\begin{align} MSE(\hat{\theta}) & = \mathbb{E}[(\hat{\theta} - \theta)^2] \\\\ & = \dfrac{1}{n} \sum\limits\_{i=1}^n (\widehat{\theta}\_{i} - \theta\_i)^2 \\\\ \end{align}$

---

## Matrices

===

$\left( \begin{matrix} a & b \\\\ c & d \end{matrix} \right) \left( \begin{matrix} 0 \\\\ 1 \end{matrix} \right) = \left( \begin{matrix} b \\\\ d \end{matrix} \right)$

===

$\left( \begin{matrix} 1 & 2 & \cdots & 10 \\\\ 2 & 3 & \cdots & 11 \\\\ \vdots & \vdots & \ddots & \vdots \\\\ 10 & 11 & \cdots & 20 \end{matrix} \right)$

---

## Conditional Equations

===

$$f(x) = \begin{cases}1 & -1 \le x < 0 \\\\ \frac{1}{2} & x = 0 \\\\ 1 - x^2 & \text{otherwise} \end{cases}$$

---

## Mixtures of inline and centered mathematics

===

#### Quadratic equation

When $a \ne 0$, there are two solutions to the quadratic equation $ax^2 + bx + c = 0$ and they are

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

===

#### Golden Ratio

The _Golden Ratio_ is an irrational number equal to $\frac{1 + \sqrt{5}}{2}$. The ratio, often denoted as $\varphi$, can be expressed as a continued fraction as follows:

$$\bbox[10px,gold,border:2px solid black]{\textrm{Golden Ratio} \equiv \varphi=1+\cfrac1{1+\cfrac1{1+\cfrac1{1+\cfrac1{1+\ddots}}}}}$$

===

#### Normal distribution

The probability density of the normal distribution with mean $\mu$ and standard deviation $\sigma$, denoted $\mathcal{N}(\mu, \sigma)$, is given by:

$$
f(x | \mu, \sigma^2) = \frac{1}{\sigma \sqrt{2 \pi}} e^{-\frac{(x - \mu)^2}{2 \sigma^2}}
$$

===

#### Dot product

Let $\mathbf{x}, \mathbf{y} \in \mathbb{R}^n$, then the _dot product_ of $\mathbf{x}$ and $\mathbf{y}$ is

$$
\mathbf{x} \cdot \mathbf{y} = \sum\_{i=1}^n x_i y_i.
$$

The inner product of a vector $\mathbf{x} \in \mathbb{R}^n$ with itself, denoted $\lVert x \rVert$, is the squared Euclidean distance associated
with $\mathbf{x}$.


---

## Numerous Math fonts

===

Bulletin Board font: $\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$

===

Math bold font: $\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

===

Math typewriter font: $\mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

===

Math sans-serif font: $\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

===

Math Roman font: $\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$

===

Math calligraphic letters: $\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ}$

===

Math script letters: $\mathscr{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ}$

===

Math "fraktur" (old German) letters: $\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz}$
