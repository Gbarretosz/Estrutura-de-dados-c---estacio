# Estrutura-de-dados-c---estacio

### [Insertion Sort](https://github.com/Gbarretosz/Estrutura-de-dados-c---estacio/blob/main/insertionSort.c)
  O metodo de ordenação citado se basea na ideia de ordenar de forma objetiva os numeros, já os colocando desde o principio em ordem crescente. Sendo feito pegando o primeiro número e comparando com o seguinte, se for mais será feita a troca e ele seguirá para fazer a troca, todo número trocado deve fazer comparações com os números anteriores ao trocado, com o objetivo de encontrar um menor, pois se forem maiores devem ser novamente feita a troca.

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201231938-bdc2128c-9f68-41ea-9060-f5bfcc1bf56f.gif" width="400px"/>
</div>

### [Merget Sort](https://github.com/Gbarretosz/Estrutura-de-dados-c---estacio/blob/main/mergeSort.c)
  O metodo de ordenação citado se basea na ideia de "Dividir para conquistar", ou seja, ele divide o vetor inicial em subvetores que continuam a se dividir em vetores subsequentes até que sobre apenas 1 índice dentro do vetor. Isso feito os subvetores volta a se reagrupar formando vetores maiores organizados até voltar ao tamanho do vetor original.

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201232281-17996b90-f887-4bf1-bccb-52aaecbe120e.gif" width="400px"/>
</div>

### [Bubble Sort](https://github.com/Gbarretosz/Estrutura-de-dados-c---estacio/blob/main/bubbleSort.c)
  O metodo de ordenação citado se basea na ideia de jogar para o final os maiores fazendo uma comparação por vez sendo iniciada apartir do índice 0 e se direcionando até o -1, fazendo a troca se encontra um número menor que o anterior.
	
<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201231768-41e20129-c0b3-492f-ab96-36e8915ffe0c.gif" width="400px"/>
</div>

### [Selection Sort](https://github.com/Gbarretosz/Estrutura-de-dados-c---estacio/blob/main/selectSort.c)
  O metodo de ordenação citado se basea na ideia de colocar o menor na frente, até que a sequencia execute o número de passos equivalente a quantidade de elementos dentro do array e o mesmo se encontra ordenado de maneira crescente.
	
<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201232081-e1e2e08c-3631-437f-84cd-d1adcf3b3541.gif" width="100px" height="300px"/>
</div>

## Comparação de Complexidade
  **O cálculo da complexidade se dá pela formula de recorrência, que é váriavel.**

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201243473-3e50912c-56c0-44f5-84fa-9a378f5a866a.png" width="433px" height="78px"/>
</div>

## Comparação de Estabilidade
  A estabilidade é definida se o metodo de ordenação respeita a ordem lexical do objeto passado.
  
  **BubbleSort:** ✔️
  
  **InsertionSort:** ✔️
  
  **SelectionSort:** ✔️
  
  **MergeSort:** ✔️
  
  **Importante:** Todos os metodos de ordenação usados respeitam a ordem lexicografia, mas alguns outros não o fazem, como o **HeapSort** e o **QuickSort**
