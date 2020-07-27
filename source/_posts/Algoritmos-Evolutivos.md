---
title: Algoritmos Evolutivos - Parte 2
tags:
  - Programação
  - Algoritmos
  - Algoritmos Evolutivos
  - Otimização
mathjax: true
categories:
  - Programação
  - Algoritmos Evolutivos
date: 2020-07-27 12:15:00
---

Caso ainda não tenha lido o post anterior, leia {% post_link Algoritmos-Evolutivos-introducao %}. Também sugere-se que utilize [este glossario básico][1] em caso de dúvidas quanto aos termos. <br><br>

<!-- block -->
Os algoritmos evolutivos possuem fundamentação na teoria da evolução biológica. 

Em geral, a evolução biológica otimiza uma população de indivíduos para o ambiente em que estão inseridos, ou seja, para os problemas que estão enfrentando.

Os algoritmos evolutivos otimizam uma população de soluções para uma determinada função objetivo, a qual mede o nível de adaptabilidade, ou _fitness_, de cada solução.
<!-- block -->

Os algoritmos genéticos são analogias computacionais à teoria de seleção natural proposta por Charles Darwin no livro _A Origem das Espécies_ (1859). Uma das bases desta teoria pode ser sintetizada no seguinte recorte:

{% blockquote Charles Darwin, A Origem das Espécies (1859)%}
[...] qualquer variação, por menor que seja e por qualquer que seja a causa, se for de algum modo lucrativa para um indivíduo de qualquer espécie [...], tenderá à preservação daquele indivíduo, e geralmente será herdada pelos descendentes.
{% endblockquote %}

Este conceito é utilizado como base para todos os algoritmos evolutivos baseados em populações. Desse modo enquanto houver uma diferença que der vantagem a uma solução, mesmo que seja muito sutil, inevitavelmente haverá a seleção dos indivíduos mais adaptados.

De forma resumida, os principais postulados da genética e seleção natural utilizados nos algoritmos evolutivos são:

* Os mecanimos evolutivos atuam apenas no genótipo (cromossomos) e não no fenótipo. Ou seja, as informações são passadas entre as gerações apenas através do material genético e nenhuma informação extra, referente à vida do indivíduo, será passada adiante.

* A seleção natual é um processo responsável por aplicar uma pressão evolutiva em uma população de indivíduos. Essa pressão evolutiva é responsável por selecionar os melhores indivíduos para se reproduzirem com maior frequência e possibilitam a passagem dos melhores genes para as futuras gerações.

* A evolução ocorre ao longo do processo de reprodução, onde ocorre a combinação dos materiais genéticos dos pais e podem ocorrer mutações aleatórias no código genético do indivíduo filho. Desse modo o material genético do filho é diferente do material genético de cada pai.

Utilizando estes postulados, a estrutura básica de um algoritmo evolutivo é mostrada a seguir.

{% codeblock "Algoritmo Evolutivo Genérico" lang:pseudo %}
Gerar população inicial aleatória
Calcular o fitness de cada indivíduo
Enquanto (fitness_médio < fitness_alvo) faça:
    Selecionar os indivíduos com melhores fitness para reprodução
    Criar novos indivíduos atraves de crossover
    Aplicar a mutação aleatoriamente
    Calcular o fitness para a nova geração
    Substituir a população antiga pela nova
{% endcodeblock %}

Dois pontos muito importantes para a implementação de um algoritmo evolutivo são a forma da codificação do material genético e a técnica utilizada para calcular o fitness. A codificação do cromossomo muitas vezes é determinado pela técnica de algoritmo genético a ser utilizada, já o cálculo do fitness é dependente do problema a ser otimizado pelo algoritmo.

Como o fitness será calculado para cada indivíduo, em execuções de algoritmos evolutivos com populações grandes ou com muitas gerações este cálculo será efetuado diversas vezes. Desse modo, esta função pode se tornar extremamente custosa, sendo um ponto a ser pensado com cuidado no momento da modelagem do problema a ser otimizado.

Para mais informações sobre as classes de algoritmos evolutivos, fique atento a novas postagens.

[1]: /Algoritmos-Evolutivos-Glossario
[2]: http://stoa.usp.br/algoritmos/files/2349/13122/Tag.PDF