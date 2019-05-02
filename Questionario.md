## 1 Problema 
###### Quais são as duas características mais comuns para analisar algoritmos?
As duas características mais comuns para analisar um software para dizer se é bom ou ruim são: Tempo e Consumo de memória.

## 2 Problema
###### Por que a medida de tempo em segundos não representa qualificadamente o tempo de execuçãoo de um algoritmo?
Não é medida em tempo o software já que deve possuir certa independência entre a tecnología; o software e o hardware.

## 3 Problema 
###### A medida de tempo de um algoritmo é realizada através de qual informação? O que pode afetá-la?
A medição do tempo em representação a qualidade e estabilidade do software é feita mediante os passos do algoritmo que precisa para finalizar a sua execução.
Pode afetá-la pelo ambiente do hardware em que ela é executada e o tamanho da entrada.

## 4 Problema
###### Na análise de algoritmos, qual é o valor da base da função logarítmica e exponencial? Por que é escolhido este valor?

A base da função logarítmica e exponencial é 2.
A base 2 tem uma importância muito considerada na informática dada a codificação binária que utiliza. O número determinado em um bit é de oito (8) exemplares que podem codificar-se com 2^8 = 256 que é o número de variações que pode realizar-se.
O algoritmo binário tem uma frequência de aparição grande no análise de algoritmos.

## 5 Problema
###### O que é complexidade de tempo?
É uma função que representa o número máximo de passos de um algoritmo.

## 6 Problema
###### Dado dois algoritmos A e B com as complexidades de tempo respectivamente f1 e f2, qual é o melhor algoritmo? O que indica qual é o melhor algoritmo?
Considerando A e B dois algoritmos totalmentes diferentes, é selecionado o melhor aquele que é executado com menores números de passos à finalização da execução e aquele que tem uma menor complexidade de tempo.

## 7 Problema
###### Em uma função de complexidade, o que representa o termo n?
Em uma função de complexidade o termo “n” é considerado como o comprimento da entrada.

## 8 Problema
###### Quais são as operações primitivas de um algoritmo?
As operações primitivas de um algoritmo são:
·        Atribuição de valores a variáveis;
·        Chamadas de métodos;
·        Operações aritméticas;
·        Comparação de dois números;
·        Acesso a um arranjo;
·        Seguimento de uma referência para um objeto;
·        Retorno de um método.

## 9 Problema
###### Qual é o valor de uma operação primitiva de um algoritmo?
Para cada valor de uma operação primitiva de um algoritmo é atribuído o valor 1.

## 10 Problema
###### Desenvolva o pseudocódigo do algoritmo SOMA, que realiza a soma de dois números inteiros recebidos por parâmetro e tem como saída a resultado da operação. Identifique a sua função de complexidade de tempo.
1 – função soma(int a, int b)
<br />
2 – retorna a + b
//Main
<br />
3 – a,b,res int
<br />
início
<br />
4 – a <- 5
<br />
5 – b <- 10
<br />
6 – res <- soma(a,b)
<br />
7 - escreva(res)
<br />
fim
 
Tem um tempo de complexidade de 9 passos para finalizar a execução do programa.

## 15 Problema
###### O que é análise assintótica? Qual é o seu objetivo?
A análise assintótica é um método de descrever o comportamento de limites, com objetivo de compreender o tempo de execução para entradas grandes.

## 16 Problema
###### Qual é o processo da análise assintótica? Crie um exemplo
1 - f(n) = 6n³ + 2n² + 20n + 45;
<br />
2 - Identificar o componente de maior ordem;
<br />
3 - 6n³;
<br />
4 - Ignorar os coeficientes;
<br />
5 - n³;
<br />
Dizemos que f é assintoticamente no, máximo, n³.

## 17 Problema
###### O que é a notação assintótica?
É uma notação utilizada para descrever o relacionamento é f(n) = O(n³).

## 18 Problema
###### O que é a notação O-Grande ou Big-Oh?
Notação O-Grande diz que uma função é menor que ou igual a outra função g(n). Ou seja, f é limitada superiormente por g assintoticamente. Geralmente é usada para mostrar como os programas precisam de recursos em relação ao tamanho de entrada.

## 19 Problema
###### Qual é a definição formal da notação O-Grande?
Formalmente definimos como: Onde R+ é o conjunto dos reais não negativos.

## 20 Problema
###### Crie um gráfico explicando a notação O-grande. Utilize f(n) = 2n + 4. Qual é um valor possível para n0?

## 21 Problema
###### O que é a notação o-pequeno ou Little-Oh?
É uma notação a qual diz que uma função é menor que a outra g(n). Ou seja, f é dominada por g assintoticamente

## 22 Problema
###### Qual é a definição formal da notação o-pequeno?
Formalmente definimos como: Onde R+ é o conjunto dos reais não negativos.

## 23 Problema
###### Crie um gráfico explicando a notação o-pequeno.

## 24 Problema
###### Passe a notação O-grande e o-pequeno as funções abaixo:

## 25 Problema
###### Identifique o O-Grande dos algoritmos desenvolvidos nos Problemas 10 até 14.



