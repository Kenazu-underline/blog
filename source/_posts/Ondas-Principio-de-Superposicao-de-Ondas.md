---
title: Ondas - Princípio de Superposição de Ondas
tags:
  - Física
  - Ondulatória
mathjax: true
categories:
  - Física
  - Ondulatória
  - Superposição
date: 2020-07-13 11:30:00
---

Ondas superpostas se somam algebricamente para produzir uma __onda resultante__ ou __onda total__.

Ondas superpostas não se afetam mutualmente, ou seja, não há qualquer alteração nas propriedades das ondas após ocorrer superposição. 

<!-- more -->

##### Interferência de ondas
O fenômeno de combinação de ondas recebe o node de __interferência__, e dizemos que as ondas interferem entre si.

Se duas ondas senoidais de mesma amplitude e comprimento de onda se propagam no mesmo sentido em uma corda, elas interferem para produzir uma onda resultante também senoidal e que se propaga no mesmo sentido.

Dois exemplos de interferência são:
* __Interferência totalmente construtiva__: Ocorre quando duas ondas de mesma fase e frequência interferem. Neste caso os picos e vales das duas ondas são conincidentes e, portanto, a onda resultante terá uma amplitude igual à soma das amplitudes das duas ondas originais.
* __Interferência totalmente destrutiva__: Ocorre quando duas ondas de mesma frequência e amplitude mas defasadas de meio comprimento de onda interferem. Neste caso o pico de uma onda será coincidente com o vale da outra e cada ponto de uma onda será coincidente com um ponto oposto da outra onda. Desse modo a interferência das duas ondas resulta em uma onda resultante d eamplitude nula.

Matematicamente a interferência totalmente destrutiva ocorre quando duas ondas idênticas, salvo de uma constante de fase diferente por um valor igual a $pi$ interferem. Ao somar a equação destas duas ondas obtemos:

\begin{align}
  y_m sen (kx-\omega t) + y_m sen (kx-\omega t +\pi) &=\\\\
   y_m sen (kx-\omega t) - y_m sen (kx-\omega t) &= 0
\end{align}

Na interferência entre duas ondas ocorre o fenômeno de sobreposição, desse modo a onda resultante é igual à soma das duas ondas originais. Porém a soma de duas funções senoidais, apesar de não se muito complexa, pode ser simplificada ao utilizar a técnica de fasores.

##### Fasores
Um fasor é um vetor de módulo igual à amplitude da onda e que gira em torno da origem com velocidade angular igual à frequência angular $\omega$ da onda. Podemos usar fasores para combinar ondas de mesma frequência, mesmo que com amplitudes e fases diferentes.

Os fasores advém da representação de uma função senoidal na notação de exponencial complexa. Porém para utilizá-lo não é necessário tal conhecimento.

Para calcular a onda resultante por meio da técnica da fasores basta representar cada onda por um fasor e realizar a soma dos fasores.

Como dito anteriormente, o fasor que representa a onda tem módulo igual à amplitude da onda. Seu ângulo em relação ao eixo horizontal será igual à constante de fase de cada onda. O fasor resultante da soma dos fasores terá um módulo igual à amplitude da onda resultante e seu ângulo em relação à origem será igual à constante de fase.

##### Ondas estacionárias
São ondas que apresentam nós (pontos da corda que não se movem). A onda em si não se desloca para nenhuma direção, porém os pontos entre os nós oscilam em relação ao ponto médio dos mesmos. Como a onda não se desloca, os pontos de máximos e mínimos não variam com o tempo.

Tais ondas surgem quando duas ondas senoidais de mesma amplitude e mesmo comprimento de onda se propagam em sentidos opostos em um meio. A interferência mútua produz uma onda que tem a forma 

\begin{align}
  y(x,t) &= y_m sen (kx-\omega t +\phi) + y_m sen (kx +\omega t +\phi)\\\\
  y(x,t) &= 2y_m sen(kx) cos(\omega t)
\end{align}

###### Ressonância
Quando uma onda se desloca em um meio finito, ao atingir algum dos limites deste meio, ela sofrerá reflexão. A onda refletida sofrerá uma alteração de sentido de deslocamento e pode sofrer uma inversão de fase (dependendo de características da interface do limite do meio).

A ressonância ocorre quando uma onda interfere com a onda refletida produzindo uma onda estacionária.

Para o caso de uma reflexão com inversão de fase, a ressonância ocorre caso o comprimento do meio qua onda está se propagando seja igual a um multiplo de meio comprimento de onda. Para reflexão sem inversão de fase, ocorre quando o comprimento é multiplo de meio comprimento de onda somado a um quarto do comprimento de onda.

Matematicamente teremos ressonância para uma reflexão com inversão de fase quando

\begin{equation}
  f = n \frac{v}{2L} , \forall n \in \mathbb{N}, n \geqslant 1
\end{equation}

ou

\begin{equation}
  L = n \frac{\lambda}{2L} , \forall n \in \mathbb{N}, n \geqslant 1
\end{equation}

E para uma reflexão sem inversão de fase quando

\begin{equation}
  f = n \frac{((2n+1)v}{4L} , \forall n \in \mathbb{N}, \geqslant 0
\end{equation}

ou

\begin{equation}
  L = n \frac{((2n+1)\lambda}{4L} , \forall n \in \mathbb{N}, \geqslant 0
\end{equation}

As frequências resultantes em cada caso são chamadas de harmônicas e o conjunto delas formam a série harmônica.
