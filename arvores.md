# Árvores

## Definição

Uma árvore é um grafo acíclico \(não possui circuito\) e conexo.

Essa estrutura tem muitas aplicações, como o sistema de cabeamento de redes e distribuição de banda larga.

## Motivação

Se imaginarmos uma grafo conexo com pesos nas arestas, como determinaos um subgrafo gerador de custo mínimo?

Para resolver este problema, não utilizamos nenhum algoritmo já visto sobre caminho mínimo. De nada tem a ver aplicar conceitos de caminho mínimo neste problema. Vamos ver que as propriedades de árvore são essências para resolver este problema

## Teorema

Quaisquer dois vértices de uma árvore estão ligamos por um **ÚNICO** caminho.

#### Prova

TODO

### Colorário

Seja G uma árvore,  $$x$$ e $$y$$ dois vértices de $$G$$ tais que $$e = (x, y) \notin E(G)$$ . Então $$G + e$$ contém um único circuito.

## Teorema 2

O número de arestas é o número de vértices - 1.

#### Prova

TODO

### Colorário

Toda árvore com pelo menos dois vértices tem pelo menos dois vértices de grau um.





> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS.



