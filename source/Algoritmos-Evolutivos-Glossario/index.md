---
title: Algoritmos Evolutivos - Glossário
date: 2020-07-27 16:53:41
mathjax: true
---


Traduzido e adaptado de [Genetic Algorithm Key Terms, Explained - KDnuggets][1] e [Genetic Algorithm Terminology - MathWorks][2].

#### Algoritmo Evolutivo
Algoritmos Evolutivos (AE) são algoritmos inspirados na seleção natural e são utilizados para encontrar uma solução otimizada (ou aproximadamente otimizada) de um problema e na soluçaõ de problemas de buscas. É uma classe de algoritmos de aprendizado que possuem motivações e paralelos relacionados à evolução biológica, incluindo [algoritmos genéticos](#Algoritmo-Genetico), estratégias evolutivas, [programação genética](#Programacao-Genetica), entre outros.

#### Algoritmo Genético
Algoritmos Genéticos (AG) são um subconjunto dos [AEs](#Algoritmo-Evolutivo) que se caracterizam pela representação da solução do problema por meio de um vetor e que itera um espaçõ de pesquisa de soluções em potencial na tentativa de identificar a "melhor solução", que é aquela que otimiza numericamente uma medida predefinida de [fitness](#Fitness).

#### Programação Genética
A programação genética é um tipo específico de [AE](#Algoritmo-Evolutivo) que utiliza estratégias de aprendizado evolutivo para otimizar a criação de código de computador, resultando em programas com desempenho ideal em uma tarefa predefinida ou conjunto de tarefas

#### Cromossomo ou Indivíduo
É o equivalente ao cromossomo biológico. É a representação de uma única solução do problema em questão.

#### População
É um conjunto de indivíduos utilizados em um [AE](#Algoritmo-Evolutivo). Os [AEs](#Algoritmo-Evolutivo) são algoritmos iterativos que atuam sobre populações de indivíduos. Após cada iteração os algoritmos retornam uma nova [geração](#Geracao) de indivíduos, ou seja, uma nova população.

#### Genes
Nos [AGs](#Algoritmo-Genetico), as soluções são representadas pelos [cromossomos](#Cromossomo-ou-Individuo) na forma de um vetor. Os genes, por sua vez, são as posições do vetor.

#### Geração
Uma geração é o conjunto de todos os [indivíduos](#Cromossomo-ou-Individuo) que formam a [população](#Populacao) de um [AE](#Algoritmo-Genetico) em uma determinada iteração.

#### Reprodução
A reprodução é o método mais comum para criar novos [cromossomos](#Cromossomo-ou-Individuo) a partir da geração anterior. Cada operação de reprodução produz um (ou dois) novo [indivíduo](#Cromossomo-ou-Individuo) a partir de dois [indivíduos](#Cromossomo-ou-Individuo) da geração anterior.

#### Seleção
Em uma analogia à seleção natural, a seleção nos [AEs](#Algoritmo-Evolutivo) garantem uma maior probabilidade de que os [indivíduos](#Cromossomo-ou-Individuo) com melhor desempenho ([fitness](#Fitness)) sejam utilizados na reprodução e tenham seus genes passados para as gerações futuras.

#### Crossover
É um dos métodos utilizados para criar novos [indivíduos](#Cromossomo-ou-Individuo) na reprodução. Consiste de dividir os cromossomos a serem cruzados em um ponto comum e utilizar a primeira parte de um dos cromossomos junto com a segunda parte do outro, gerando dois novos [indivíduos](#Cromossomo-ou-Individuo).

Supondo um problema para o qual o [cromossomo](#Cromossomo-ou-Individuo) é um vetor binário, a imagem a seguir exemplifica um crossover simples.

![Crossover de dois cromossomos vetores binários. <br> <a href="https://www.kdnuggets.com/2018/04/genetic-algorithm-key-terms-explained.html" title='via KDnuggets'>KDnuggets</a>](https://www.kdnuggets.com/wp-content/uploads/ga-key-terms-crossover.jpg)

#### Mutação
A mutação é análoga à mutação biológica. Neste processo algum gene do [indivíduo](#Cromossomo-ou-Individuo) pode aleatóreamente sofrer uma mudança em seu valor.

Exemplificando para o problema com [cromossomo](#Cromossomo-ou-Individuo) binário, a mutação é a negação de um dos genes do [cromossomo](#Cromossomo-ou-Individuo). A figura a seguir mostra este processo.

![Mutação de um cromossomos de vetores binários. <br> <a href="https://www.kdnuggets.com/2018/04/genetic-algorithm-key-terms-explained.html" title='via KDnuggets'>KDnuggets</a>](https://www.kdnuggets.com/wp-content/uploads/ga-key-terms-mutation.jpg)

#### Fitness
O fitness também é uma analogia ao _fitness_ da biologia. Na biologia, o _fitness_ é a aptidão de um [indivíduo](#Cromossomo-ou-Individuo), que é uma medida simples de sucesso reprodutivo. Nos [AEs](#Algoritmo-Evolutivo) o fitness é uma métrica utilizada para avaliar cada [indivíduo](#Cromossomo-ou-Individuo), identificando e ranqueando cada [indivíduo](#Cromossomo-ou-Individuo).

O fitness depende completamente do problema a ser resolvido pelo [AE](#Algoritmo-Evolutivo), sendo basicamente a função a ser otimizada.


[1]: https://www.kdnuggets.com/2018/04/genetic-algorithm-key-terms-explained.html
[2]: https://www.mathworks.com/help/gads/some-genetic-algorithm-terminology.html
[3]: https://www.kdnuggets.com/wp-content/uploads/ga-key-terms-crossover.jpg