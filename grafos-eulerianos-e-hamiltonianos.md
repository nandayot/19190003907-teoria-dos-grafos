# Grafos Eulerianos e Hamiltonianos

## Motivação

### O problema do carteiro chinês

A tarefa de um carteiro é pegar as correspondências na agência, entregá-las, e retornar à agência. Ele deve cobrir cada rua na sua área e deseja fazer sua rota de tal forma que caminhe o menos possível. Mas como fazer isso? Este problema, conhecido como “Problema do Carteiro Chinês”, foi proposto por um matemático chinês, chamado Kuan, em 1962.

## Grafo Euleriano

Uma **trilha de Euler** é uma trilha que passa por todas as arestas de um grafo. Um grafo é **euleriano** se ele contém uma trilha de Euler fechada, ou seja, uma trilha cujos extremos coincidem.

## Teorema

Um grafo conexo é euleriano se, e somente se, todo vértice tem grau par.

### Prova

TODO

### Corolario

Um grafo conexo tem uma trilha de Euler se, e somente se, ele tem no máximo dois vértices de grau ímpar

## PCC

Obviamente, se G é euleriano, então qualquer trilha fechada de Euler é uma solução ótima, já que passa exatamente por cada uma das arestas do grafo. Assim, o PCC é facilmente resolvido para grafos eulerianos. **Basta encontrarmos uma trilha fechada de Euler**.

Existe um algoritmo bem simples que encontra uma trilha fechada de Euler em um grafo euleriano. Este algoritmo, devido a Fleury \(1921\), constrói uma tal trilha sujeita à seguinte condição

* em cada passo, escolha uma aresta que não seja de corte no grafo restante, a menos que não haja alternativa

Agora, **se G não é euleriano**, certamente o carteiro terá que passar mais de uma vez por algumas ruas. Em outras palavras, um percurso ótimo passará mais de uma vez por algumas arestas. A pergunta então é: já que devemos passar mais de uma vez por algumas arestas, quais escolheremos?



## Grafos Hamiltonianos

Um circuito que contém todos os vértices de um grafo é chamado circuito hamiltoniano. Um grafo é hamiltoniano se ele contém um circuito hamiltoniano. Por exemplo, os grafos completos com pelo menos três vértices são hamiltonianos.

**Problema**: Decidir se um grafo é hamiltoniano

## Teorema

Se $$G$$ é hamiltoniano então para todo subconjunto próprio $$S$$ de $$V (G)$$

$$
w(G − S) ≤ |S|
$$

Esta condição, no entanto, não é suficiente. Por exemplo, o grafo de Petersen satisfaz a condição do teorema mas não é hamiltoniano

Passaremos agora a discutir condições suficientes para que um grafo seja hamiltoniano. Claramente, é suficiente limitarmos os nossos estudos para grafos simples. Iniciaremos com um resultado de Bondy e Chvátal \(1976\).

## Teorema

Seja $$G$$ um grafo simples com $$n$$ vértices e sejam $$u$$ e $$v$$ dois vértices não adjacentes em $$G$$ tais que

$$
d(u) + d(v) ≥ n
$$

Então $$G$$ é hamiltoniano se, e somente se, $$G + (u, v) $$ é hamiltoniano.

> Anotações feita com base nos slides de grafos do professor Marcelo Henriques de Carvalho da FACOM-UFMS

