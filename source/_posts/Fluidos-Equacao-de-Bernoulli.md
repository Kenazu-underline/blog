---
title: Fluidos - Equação de Bernoulli
tags:
  - Física
  - Hidráulica
  - Fluidos
mathjax: true
categories:
  - Física
  - Fluidos
date: 2020-07-11 23:30:00
---

A equação de Bernoulli aqui abordada descreve o comportamente de um {% post_link Fluidos-Hidrodinamica-de-Fluidos-ideais "fluido ideal"%} em movimento ao longo de um tubo sob um campo gravitacional uniforme. Por vezes esta equação também é utilizada como uma aproximação para fluidos reais em escoamento laminar.

{% blockquote Wikipédia, a enciclopédia livre. https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%A3o_de_Bernoulli Equação de Bernoulli %}
O princípio de Bernoulli afirma que para um fluxo sem viscosidade, um aumento na velocidade do fluido ocorre simultaneamente com uma diminuição na pressão ou uma diminuição na energia potencial do fluido.
{% endblockquote %}

A equação de Bernouli é escrita como

\begin{equation}
  p + \frac{1}{2} \rho v^2 + \rho g h = constante
\end{equation}

<!-- more -->

ou,

\begin{equation}
  \frac{p}{\rho} + \frac{v^2}{2} + g h = constante
\end{equation}

onde
&#8195; $ v $ é a velocidade do fluido ao longo do tubo
&#8195; $ g $ é a aceleração da gravidade local
&#8195; $ h $ é a altura em relção a um referencial
&#8195; $ p $ é a pressão ao longo tubo
&#8195; $ \rho $ é a massa específica do fluido

Esta equação é comummente utilizada em situações de comparação entre dois pontos da tubulação. Nesse caso a equação toma a forma

\begin{equation}
  p_1 + \frac{1}{2} \rho v_1^2 + \rho g h_1 = p_2 + \frac{1}{2} \rho v_2^2 + \rho g h_2
\end{equation}

{% note info %}
Quando analizamos o caso de a altura não variar, temos

\begin{equation}
  p_1 + \frac{1}{2} \rho v_1^2 = p_2 + \frac{1}{2} \rho v_2^2 
\end{equation}

Ou seja, se a velocidade de um fluido aumenta enquanto ele se move horizontalmente ao longo de uma linha de fluxo, a pressão do fluido diminui, e vice-versa.
{% endnote %}

{% note warning %}
A equação de Bernoulli também é utilizada em situações de movimentação de fluidos fora de um tubo, nesse caso um feixe de linhas de fluxo é considerado como se fosse o tubo.

Esta equação também possui uma variante para fluidos comprenssíveis.
{% endnote %}