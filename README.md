# Sorting-Uni-Project
Um trabalho da faculdade sobre sorting/ordenação.

Sorting, também chamado de ordenação são métodos na linguagem de programação para colocar elementos de uma sequências dados em uma certa ordem.

No caso, temos quatro tipos de ordenação em C/C++: método da bolha (bubble sort), método da seleção (selection sort), método da inserção (insertion sort) e heapsort.

Neste README, vou apenas apresentar o conceito e comparação de todas, e o resto do repositório vão de ser exemplo das mesmas.

BUBBLE SORT:

Bubble Sort é um tipo de ordenação que, além de ser a mais lenta entre elas, é a mais simples dos algorítmos. Funciona em duas tarefas principais que são executados em loop até os dados serem totalmente ordenados:

-Comparação de itens adjacentes.

-Troca de posição dos itens, quando for necessário.

É estável, ou seja, caso um elemento esteja posicionado corretamente em relação ao seu sucessor e antecessor na sequência, o algoritmo não efetua troca. É não recursivo. Tem baixa complexidade de espaço O(n), isto é, só utiliza a memória necessária para armazenar a sequência a ser ordenada e é um método de ordenação interna.

SELECTION SORT:

Selection sort, também conhecido em português como ordenação por seleção baseado em passar o menor valor do vetor para a primeira posição (ou maior, dependendo da ordem), depois o de segundo menor valor do vetor para a segunda posição, e assim é feito sucessivamente até o último elemento.

A complexidade computacional do algoritmo é O(n2). Este fato pode ser provado analisando o número de iteração e a quantidade de operações por iteração. O primeiro passo para a análise é determinar a operação fundamental do algoritmo. A cada iteração, necessitamos o valor mínimo de uma sequência de n elementos. A operação básica para isto é a comparação.

