# Algoritmos em Grafos

## Como representar computacionalmente um grafo?



## Busca em Largura



## Busca em Profundidade



## O problema do Caminho Mínimo

Como eu parto de uma genarilização do algoritmo em largura que resolve a distancia de um certo ponto ao outro para um problema com **custos** em ****suas ****arestas?

Uma solução seria trocar os custos por caminhos de mesmo custo. Exemplo: tranforma um caminho de custo 8 por 8 vértices, 8 caminhos. Faça isso para cada caminho com custo. E assim conseguimos aplicar busca em largura.

## Algoritmo de Dijkstra

O problema do caminho mínimo é resolvido utilizando o algoritmo chamado Algoritmo de Dijkstra \(1959\). Ele funciona como um generalização do algoritmo de busca em largura. 

O algoritmo faz uma projeção do custo para o próximo vértice. Assim ele escolher o vértice que apontou-se ser o de menor custo. Depois de atinjido temos que atualizar os custos dos vértcies **adjacentes** \(ainda não atinjidos\) e  assim por diante. Relizando esse procedimentos descobrimos o custo de menor caminho. 

Agora a questão é: Quel é o caminho que apresentou esse menor custo? Para descobrirmos isso fazemos o "caminho inverso". Como se voltássemos para a origem de acordo com os custos finais. Substraindo o custo em cada caminho com ocusto final dos vértices adjacentes e escolhendo o caminho que o cálculo bate com o custo do vértice até cehgarmos na origem.

## Algoritmo de Bellman-Ford-Moore



## Algoritmo de Floyd – Warshall

