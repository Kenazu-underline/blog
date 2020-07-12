---
title: Fluidos - Equação de Continuidade
tags:
  - Física
  - Hidráulica
  - Fluidos
mathjax: true
categories:
  - Física
  - Fluidos
date: 2020-07-11 23:00:00
---
 
A equação da continuidade advém do princípio da conservação da massa aplicado a um fluido incomprensível. Ao definir um volume de controle, por exemplo uma seção de uma tubulação, a quantidade de massa que adentra esse volume de controle é igual à quantidade de massa que sai.

<!-- more -->

Algumas equações podem sem desenvolvidas a partir deste princípio. Aqui será abordada a equação que relaciona velocidade em função da área de uma tubulação.

Assumindo o volume de controle como uma tubulação, existem apenas duas superfícies pelas quais o fluido podem entrar e sair. Tomando como base a figura abaixo, o volume de fluido que entra em um determinado intervalo de tempo infinitesimal ($\partial V_1$) está demarcado em cinza na ponta 1 e o volume de fluido que sai ($\partial V_2$) está demarcado em cinza na ponta 2.

![Tubulação com área de secção transversal diferente. <br><a href="https://mundoeducacao.uol.com.br/fisica/equacao-continuidade.htm" title="via Mundo Educação">Mundo Educação</a> ](/blog/images/equacao-continuidade.jpg)

Assumindo que a área de secção transversão ao longo de $\partial V_1$ e $\partial V_2$ sejam constante, visto que possuem comprimentos infinitesimais e chamando o comprimento destes volumes de $\partial x_1$ e $\partial x_2$, a velocidade do fluido pode ser definida como

\begin{equation}
  \vec{v} = \frac{\partial x}{ \partial t}
\end{equation}

O volume de fluido entrando e saindo pode ser escrito como

\begin{equation}
  \partial V = A \partial x = A \vec{v} \partial t
\end{equation}

Sendo $A$ a área de secção transversal.

Como $\partial V_1 = \partial V_2$,

\begin{align}
  A_1 \vec{v_1} \partial t &= A_2 \vec{v_2} \partial t\\\\
  A_1 \vec{v_1} &= A_2 \vec{v_2}  \label{eq:continuidade}
\end{align}

A equação da continuidade é a equação \ref{eq:continuidade}. 

A vazão de fluido $R_v$ é definida como

\begin{equation}
  R_v = A \vec{v}
\end{equation}

e é constante ao longo de toda a tubulação.

Caso o fluido possua uma massa específica uniforme, sua vazão mássica $R_m$ também será constante ao longo da tubulação. A vazão mássica é definida como

\begin{equation}
  R_m = \rho R_v = \rho A \vec{v}
\end{equation}
