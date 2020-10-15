# Exercícios

## 1\). 

#### Descreva algoritmos para responder as seguintes perguntas: Dado um Grafo G..

* G é conexo?

  **R:** Este problema pode ser resolvido utilizando qualquer técnica que Busca que aprendemos na Disciplina. Busca em largura ou em profundidade, ambas podem ser usadas e alteradas conforme a necessida do problema. Neste caso, uma solução seria utilizar o algoritmo que visita todos os vértices e quando termina de visitar, sabemos que é conexo pois ele visitou todos. Sabemos previamente a quantidade de vértices, caso visitamos todos, por meio da Busca, o grafo é conexo.

*  G possui circuito?

  **R:** Podemos utilizar a Busca em Profundidade para encontrar vértices JÁ alcançados e descobrirmos que existe um circuito. A Busca em Profundidade empilha vértices já alcançados e assim conseguimos descobrir se possui circuito ou não.

* G é bipartido?

  **R:** Esse problema pode ser resolvido por qualquer algoritmo de Busca fazendo algumas alterações. Uma solução seria colocar classes em cada vértice visitado de maneira alternada. O primeiro recebe a classa "A", o segundo a classe "B" e assim por diante. Caso o algoritmo estando numa classe encontra um vértice adjacente, já visitado, com a mesma classe, descobrimos que o grafo não pode ser bipartido, e que portanto, possui circuito ímpar.

* Determine a distância entre dois vértices u e v

  R: Esse problema é resolvido pelo algoritmo de Busca em Largura. O vértice u inicialmente é setado como 0 e assim olhamos para todos os seus adjacentes e marcamos a distância incrementando do vértice anterior e assim por diante até chegar no vértice v.

> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS.

