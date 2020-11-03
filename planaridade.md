# Planaridade

## Definição

Um grafo é **planar** se ele _**pode**_ ser desenhado no plano sem cruzamento de arestas.

O grande problema desta definição é decidir se um grafo é planar ou não.

## Teorema 

$$K_5$$ é não planar.

O único argumento usado para provar este teorema é dizermos que quando temos um circuito fechado, um vértice interno, dentor desse circuito e outro vértice, na parte externa, ou seja, fora desse circuito, eles não podem se ligar sem cruzamento de arestas.

#### Prova

TODO

## Subdivisão

Uma subdivisão de um grafo $$G$$ é um grafo obtido a partir de $$G$$ trocando cada aresta por um caminho ligando seus extremos. Em outras palavras, inserindo vértices nas arestas de $$G$$.

### Teorema

Um grafo $$G$$ é planar se, e somente se, qualquer subdivisão de $$G$$ é planar

## Teorema Fundamental

Um teorema fundamental, devido a **Kuratowski** \(1930\), afirma que a recíproca desta afirmação é verdadeira, isto é, todo grafo não planar contém uma subdivisão do $$K_5$$ ou $$K_{3,3}$$ .

Dessa forma o $$K_5$$e o $$K_{3,3}$$ são a essência da não-planaridade. Conseguimos provar que um grafo é não-planar quando o grafo contém ou o $$K_{3,3}$$ ou o $$K_5$$**.**

## Fórmula de Euler

Um grafo planar imerso no plano será chamado de grafo plano. Euler \(1752\) estabeleceu uma fórmula bem simples relacionando o número de vértices \( $$v$$ \), arestas \( $$a$$ \) e faces \( $$f$$ \) de um grafo conexo e plano.

### Teorema

Se G é um grafo conexo e plano então:

$$
v(G) − a(G) + f(G)=2
$$

### Colorário

Toda imersão no plano \(desenho no plano\) de um grafo conexo planar tem o **mesmo** número de faces.

### Grau de face

O **grau de uma face** $$f$$ , denotado por $$d(f)$$ , é o número de arestas que limitam a face $$f$$ \(cada aresta de corte é contada 2 vezes\). Logo,

$$
\sum_{f \in \text{face}}d(f) = 2a
$$

### Colorário

Se $$G$$ é um grafo planar simples com pelo menos três vértices, então;

$$
a(G) ≤ 3v(G) − 6
$$



> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS

