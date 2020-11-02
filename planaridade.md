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



> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS

