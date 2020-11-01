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

## Aresta de Corte

Já vimos que $$w(G)$$ é o número de componentes de um grafo $$G$$ . Assim, se $$G$$ é um grafo conexo então $$w(G)=1$$ . Uma aresta de corte em um grafo $$G$$ é uma aresta tal que $$w(G − e) > w(G)$$ .

Em outras palavras, uma aresta de corte em um grafo conexo é tal que, tirando ela, o grafo não fique mais conexo. Em árvores, toda aresta, é uma aresta de corte. Assim, podemos introduzir o seguinte teorema.

## Teorema 3

Um grafo conexo é uma árvore se, e somente se, toda aresta é de corte.

## Árvore Geradora

Uma árvore geradora de um grafo $$G$$ é um **subgrafo gerador** de $$G$$ que é uma árvore.

Logo, todo grafo conexo, contem uma árvore geradora. Um grafo conexo pode ter diferentes árvores geradoras.

## Vértice de Corte

Um vértice $$v$$ de um grafo $$G$$ é chamado de vertice de corte se $$w(G − v) > w(G)$$ . Ou seja, um vértice do grafo, é um vértice de corte, se, quando removido ele do grafo \(tirando todas as arestas que incidem nele\), o número de componentes no grafo, aumenta.



Com as definições já feitas acima é possível voltar para o problema previamente mostrado e resolver com base no algoritmo abaixo.

## Algoritmo de Kruskal

O algoritmo que vamos estudar para resolver este problema é de autoria de **Kruskal** \(1956\).

1. Dado um grafo $$G = (V,E)$$ , considere o grafo $$T = (V (G), ∅)$$ 
2. $$S ← E(G)$$ 
3. Enquanto $$|T| < |V | − 1$$ 
   1. remova uma aresta $$e$$ de peso mínimo de $$S$$ 
   2. Se $$e$$ liga duas componentes distintas de $$T$$ então adicione $$e$$ à $$T$$ ; Senão descarte $$e$$ 

### Corretude

#### Teorema

O algoritmo de Kruskal determina corretamente uma árvore geradora K de custo mínimo em um grafo conexo com custos reais associados às arestas.

#### Prova 

TODO





> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS.



