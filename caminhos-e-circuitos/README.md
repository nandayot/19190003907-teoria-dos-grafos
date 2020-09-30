---
description: 'Conceitos básicos de passeio, trilha e caminho, grafo conexo e desconexo'
---

# Caminhos e Circuitos

## Passeio

Um passeio em um grafo $$G$$ é uma sequência finita e _não nula_ $$W$$ = \( $$ v_0 e_1 v_1 e_2 ...e_k v_k$$\) cujos termos são alternadamente **vértices** e **arestas**, tais que, para $$1 ≤ i ≤ k$$ , os extremos de $$e_i$$ são $$v_i−_1 $$ e $$v_i$$ .

Chamamos $$v_0 $$ de **origem** e $$v_k $$ de **término** do passeio $$W$$ e os demais vértices, $$v_1..v_k-_1$$ são chamados de vértices **internos**. E o **comprimento** de $$W$$ é $$k$$ \(número de vértices\).

## Trilha

Trilha é quando as arestas do passeio são distintas.

## Caminho

Caminho são passeios em que os vértices são distintos. Ou seja, o passeio não passa novamente em um mesmo vértice.

![](../.gitbook/assets/caminhoetrilha.jpg)

## Grafo Conexo e Desconexo

Um grafo é **conexo** se existe caminho ligando qualquer par de vértices. Caso contrário, ele é **desconexo**. Ou seja, grafo conexo é possível desenhar um caminho em que conseguimos percorrer todos os vértices sem _**"tirar o lápis do papel".**_

### Componente

Componentes de um grafo são subgrafos conexos maximais. Ou seja, um caminho em que conseguimos percorrer o maior número de vértices possível dentro da parte conexa do grafo.

![](../.gitbook/assets/conexodesconexo.jpg)

## Circuito

### Passeio fechado

Um passeio é fechado quando sua origem coincide com seu término. Um caminho fechado é chamado de circuito. Ou seja, um caminho \(quando um passeio não repete vértices\) onde sua origem coincide com o seu término, é um circuito.

Agora que sabemos a definição de circuitos, eles possuem .relação o conceito de grafos bipartidos. E qual relação é essa?

## Lema 1

Seja $$ G = (X, Y)$$ um grafo bipartido e $$C$$ um circuito em $$G$$ . Então $$C$$é par.

Ou seja. Todo circuito que pertence a um grafo bipartido, o comprimento dele sempre é par.

### Prova

![](../.gitbook/assets/circuitoprova_page_1.jpg)

## Lema 2

Seja$$G$$um grafo que não possui circuito ímpar. Então $$G$$ é bipartido.

### Prova

![](../.gitbook/assets/provalema2.jpg)



Combinando os dois lemas vistos chegamos no Teorema abaixo.

## Teorema

Um grafo é bipartido se, e somente se, não possui circuito ímpar.



