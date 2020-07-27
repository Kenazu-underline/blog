---
title: Ondas - Introdução
tags:
  - Física
  - Ondulatória
mathjax: true
categories:
  - Física
  - Ondulatória
date: 2020-07-12 20:00:00
---

De forma extremamente simplificada,
>Onda é uma perturbação que se propaga.

<!-- more -->

Ou de forma mais completa:
>Uma onda é uma perturbação oscilante de alguma grandeza física no espaço e periódica no tempo.

Outra definição é:
>Uma onda é um pulso energético que se propaga através do espaço ou através de um meio, com velocidade definida.

#### Tipos de Ondas

##### Quanto ao tipo de perturbação

* __Ondas mecânicas__: são governadas pelas leis de Newton e existem apenas em meios materiais.
* __Ondas eletromagnéticas__: não precisam de um meio material para existir, e se propagam na velocidade do som.
* __Ondas de matéria__: sob certas condições um feixe de partículas pode apresentar caracterísricas ondulatórias. Estas ondas são governadas pelas leis da física quântica.

##### Quanto à direção de deslocamento

* __Ondas transversais__: Os elementos que compõem a onda se deslocam perpendicularmente à direção de propagação da onda. Exemplos: Ondas na superfície de um som e ondas eletromagnéticas.
* __Ondas Longitudinais__: Os elementos que compõem a onda se deslocam paralelamente à direção de propagação da onda. Exemplos: Ondas se propagando em uma mola e ondas sonoras.

##### Quanto à propagação

* __Ondas progressivas__: Se propagam de um local para outro. É importante notar que apenas a onda se move e não o meio material.
* __Ondas estacionárias__: Não se propagam. Em geral são formadas quando duas ondas progressivas de mesma frequência e se propagando em sentidos opostos interagem entre sim.

#### Equação de onda

A equação de onda é uma equação diferencial parcial (EDP) linear de segunda ordem que descreve o comportamento das ondas.

{% blockquote Wikipédia, a enciclopédia livre. https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%A3o_da_onda Equação da onda %}
Na sua forma mais simples, a equação de onda diz respeito a uma variável de tempo t, uma ou mais variáveis ​​espaciais $x_1$, $x_2$, $\ldots $, $x_n$, e uma função escalar $u = u (x_1, x_2, \ldots , x_n; t)$, cujos valores poderiam modelar o deslocamento de uma onda. A equação de onda para u é: 

\begin{equation}
  \frac{\partial ^2 u}{\partial t^2} = c^2 \nabla ^2 u
\end{equation}

onde $\nabla ^2$ é o laplaciano e onde $c$ é uma constante fixa.
{% endblockquote %}

Uma solução desta EDP para ondas se propagando em uma dimensão é

\begin{equation}
  y(x,t) = y_m sen (kx-\omega t +\phi)
\end{equation}

Sendo
&#8195; $ y(x,t) $ o deslocamento ou variação na intensidade da grandez física perturbada.
&#8195; $ y_m $ é o módulo do deslocamento máximo dos elementos em relação à posição de equilíbrio.
&#8195; $ (kx-\omega t) $ é a fase instantânea da onda.
&#8195; $ k $ é o número de onda e possui unidade de medida $ m^{-1} $.
&#8195; $ \omega $ é a frequência angular da onda.
&#8195; $ \phi $ é a constante de fase. É utilizada para fornecer uma posição inicial para o elemento de onda $x=0$.

A partir do número de onda podemos calcular o comprimento de onda ($\lambda$) por meio da equação

\begin{equation}
  \lambda = \frac{2 \pi}{k}
\end{equation}

A partir da frequência angular é possível calcular a frequência ($f$) e o período ($T$) da onda. Sendo a frequência igual ao número de oscilações por segundo e o período igual ao tempo que um elemento da onda leva para fazer uma oscilação completa.

\begin{align}
  T &= \frac{2 \pi}{\omega}\\\\
  f &= \frac{1}{T} = \frac{\omega}{2 \pi}
\end{align}

A partir da equação da onda também é possível determinar a velocidade de uma onda progresiva.

\begin{equation}
  v = \frac{dx}{dt} = \frac{\omega}{k} = \frac{\lambda}{T} = \lambda f
\end{equation}

Porém é importante salientar que a velocidade da onda depende apenas de características do meio, e não da frequência ou comprimento de onda. A velocidade da onda é apenas uma relação entre o comprimento de onda e a frequência.

Para exemplificar essa independência da velocidade da onda da frequência e da frequência, temos o caso da velocidade de propagação de uma onda transversal ao longo de uma corda, a qual é

\begin{equation}
  V = \sqrt{\frac{\tau}{\mu}}
\end{equation}

sendo
&#8195; $ \tau $ a tensão aplicada à corda.
&#8195; $ \mu $ a massa específica linear da corda.

Note que ao retornar a equação da onda para a forma de EDP, obtemos

\begin{equation}
  \frac{\partial ^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial ^2 y}{\partial t^2}
\end{equation}