title: Fluidos
tags: []
mathjax: true
categories: []
date: 2020-07-12 22:27:00
---
  
Testes
<!-- more -->



\ref{eq:sample} 







#### Simple Equation

For simple equations, use the following form to give a tag,

```latex
$$\begin{equation} \label{eq1}
e=mc^2
\end{equation}$$
```

$$\begin{equation} \label{eq1}
e=mc^2
\end{equation}$$

Then, you can refer to this equation in your text easily by using something like:

```latex
The famous matter-energy equation $\eqref{eq1}$ proposed by Einstein...
```

The famous matter-energy equation $\eqref{eq1}$ proposed by Einstein...

#### Multi-line Equation

For multi-line equations, inside the `equation` environment, you can use the `aligned` environment to split it into multiple lines:

```latex
$$\begin{equation} \label{eq2}
\begin{aligned}
a &= b + c \\
  &= d + e + f + g \\
  &= h + i
\end{aligned}
\end{equation}$$
```

$$\begin{equation} \label{eq2}
\begin{aligned}
a &= b + c \\\\
  &= d + e + f + g \\\\
  &= h + i
\end{aligned}
\end{equation}$$

```latex
Equation \ref{eq2} is a multi-line equation.
```

Equation $\eqref{eq2}$ is a multi-line equation.

#### Multiple Aligned Equations

We can use `align` environment to align multiple equations. Each of these equations will get its own numbers.

```latex
$$\begin{align}
a &= b + c \label{eq3} \\
x &= yz \label{eq4}\\
l &= m - n \label{eq5}
\end{align}$$
```

$$\begin{align}
a &= b + c \label{eq3} \\\\
x &= yz \label{eq4}\\\\
l &= m - n \label{eq5}
\end{align}$$

```latex
There are three aligned equations: equation $\eqref{eq3}$, equation $\eqref{eq4}$ and equation $\eqref{eq5}$.
```

There are three aligned equations: equation $\eqref{eq3}$, equation $\eqref{eq4}$ and equation $\eqref{eq5}$.

Since `align` in and of itself is a complete equation environment (read [here](https://tex.stackexchange.com/questions/95402/what-is-the-difference-between-aligned-in-displayed-mode-and-starred-align) about the difference between `aligned` and `align` in LaTeX). You do not need to wrap it with `equation` environment.

#### Exclude equations from numbering

In the `align` environment, if you do not want to number one or some equations, just use `\nonumber` right behind these equations. Like the following:

```latex
$$\begin{align}
-4 + 5x &= 2+y \nonumber  \\
 w+2 &= -1+w \\
 ab &= cb
\end{align}$$
```

$$\begin{align}
-4 + 5x &= 2+y \nonumber  \\\\
 w+2 &= -1+w \\\\
 ab &= cb
\end{align}$$

#### Use `\tag` to tag equations

Sometimes, you want to use more «exotic» style to refer your equation. You can use `\tag{}` to achieve this. For example:

```latex
$$x+1\over\sqrt{1-x^2} \tag{i}\label{eq_tag}$$
```

$$x+1\over\sqrt{1-x^2} \tag{i}\label{eq_tag}$$

```latex
Equation $\eqref{eq_tag}$ use `\tag{}` instead of automatic numbering.
```

Equation $\eqref{eq_tag}$ use `\tag{}` instead of automatic numbering.


