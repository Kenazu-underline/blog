---
title: Fluidos - Princípio de Pascal
tags: 
  - Física
  - Hidráulica
  - Fluidos
mathjax: true
categories:
  - Física
  - Fluidos
date: 2020-07-11 22:00:00
---

O Princípio de Pascal estabelece que

>A pressão aplicada num ponto de um fluido incompressível em repouso transmite-se integralmente a todos os pontos do fluido.

<!-- more -->

Utilizando como base a figura abaixo, que mostra uma prensa (ou elevador) hidráulica, é possível entender de forma simples essa transmissão de pressão.

![Transferência de força em uma prensa hidráulica. <br><a href="https://commons.wikimedia.org/wiki/File:Prensa_Hidr%C3%A1ulica.png" title="via Wikimedia Commons">Anna Carollina Chaves Braz</a> / <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA</a>](https://upload.wikimedia.org/wikipedia/commons/f/f0/Prensa_Hidr%C3%A1ulica.png)

Dado que o fluido está em repouso e que as superfícies de ambos os lados da prensa estão na mesma altura, tem-se que


\begin{align}
  p_1 &= p_2 \\\\
  p_2A_2 &= p_1A_1 
\end{align}

Ao ocorrer uma variação de  pressão $ \Delta p $, devido a uma força externa $ \Delta F_1 $ no lado 1, essa variação será sentida no lado 2. Desse modo,

\begin{equation}
  \Delta p = \frac{\Delta F_1}{A_1} =  \frac{\Delta F_2}{A_2}
\end{equation}

Disso, a variação na força do lado 2 será

\begin{equation}
  \Delta F_2 = \Delta F_1 \frac{A_2}{A_1}
\end{equation}

Ao aplicar essa força, e supondo que a variação na força do lado 2 não seja compensada, ocorre um deslocamento do fluido. O volume $ V $ deslocado será proporcinal ao deslocamento linear da superfície do fluido em ambos os lados, e igual a

\begin{equation}
  V = A_1 \Delta y_1 =  A_2 \Delta y_2
\end{equation}

Obtemos então a relação entre o deslocamento de fluido de um lado para o outro,

\begin{equation}
  \Delta y_2 = \Delta y_1 \frac{A_1}{A_2}
\end{equation}

O trabalho realizado por essa variação de força no lado 1 será dado por

\begin{equation}
  W = F_1 \Delta y_2 = \left( \Delta F_1 \frac{A_2}{A_1} \right) \left( \Delta y_1 \frac{A_1}{A_2} \right) = F_2 \Delta y_2
\end{equation}

Semelhante a uma alavanca, temos que uma força aplicada sobre uma distancia pode ser transformada em uma força maior aplicada ao longo de uma distância menor.

[1]: https://pt.wikipedia.org/wiki/Princ%C3%ADpio_de_Pascal