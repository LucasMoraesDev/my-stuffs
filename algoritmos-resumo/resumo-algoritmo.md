# Resumo da aula Desmistificando Algoritmo

## Conceito de Algoritmo

> Um algoritmo é entendido como uma rotina, um processo - pode ser conceituado de diversas formas:


* Uma Sequência ordenada, finita e não ambígua de etapas que conduzem à solução de um problema.

* Descrição de um conjunto padronizado de ações primitivas, bem definidas e executáveis, que encadeiam a realização de uma tarefa.

 * Processo de cálculo ou de resolução de um grupo de problemas semelhantes, em que se estipulam, com generalidade e sem restrições, as regras formais para a obtenção do resultado ou da solução do problema

## Estruturas de Controle

> Existem três formas básicas de agregar instruções primitivas: sequência , seleção  e repetição.

### Sequência

* Entende-se que toda idéia que desejamos transmitir deva ter as instruções para serem executadas uma em sequência à outra.
  
* Este é o primeiro mecanismo de agregação utilizado para gerar processos complexos a partir de processos mais simples, ou seja: a Sequenciação.

  <img src="https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/estrutura-de-sequencia.png?token=ARJXBMU5WBWTRFETTRDLXGTAKOPVC" >
  
### Seleção

* É um mecanismo de Seleção das instruções a serem executadas, que depende da situação de veracidade ou falsidade da(s) condiçâo(ões) imposta(s) no momento da execução do trecho considerado.


<img src= "https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/estrutura-de-selecao-simples.png?token=ARJXBMSTSNOVQGOUPESLKILAKOQEE">


### Repetição

* Exerce um mecanismo de Repetição subordinado a uma condição que regula a execução da instrução primitiva


<img src="https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/estrutura-de-repeticao-com-teste-a-priori.png?token=ARJXBMX3AIGAHYGSAO4US2DAKOQUS">


## Representação de Algoritmos

>Agora obsevaremos as principais formas de representação das três estruturas básicas de controle usadas na descrição de processos estruturados: Seqüência, Seleção e Repetição.

### Diagrama Estruturado

#### Observe a representação em diagrama estruturado.
* Um algoritmo é representado por um retângulo cujas fatias horizontais são suas etapas em sequência.
* Além disso, a representação de estruturas de seleção e de repetição são retângulos especiais.
* Observe, intuitivamente, o retângulo utilizado para a estrutura de seleção deste exemplo.


<img src="https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/diagrama-estruturado.png?token=ARJXBMTJKDAA72KBESOZY2DAKOSPE">


### Fluxograma

#### A representação em Fluxograma possui duas características principais:

* as instruções primitivas são expressas em retângulos (se houver várias instruções primitivas em seqüência para simplificar, podem ser descritas em um único retângulo).
 
* os testes (tanto nas estruturas de seleção quanto nas de repetição) são explicitados em losangos, onde a mágica é o “siga a seta” para acompanhar que instruções serão executadas quando a condição do teste for verdadeira ou for falsa.


<img src="https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/fluxograma-estruturado.png?token=ARJXBMVJFI36J3H2EKQAWBDAKOSCI">


### Linguagem Estruturada (Pseudocódigo)

#### Na representação de uma estrutura condicional Pseudo-linguagem, note que:

* a condição está descrita entre as expressões “Se” e “então”;
* as instruções a serem executadas quando a condição for verdadeira, serão descritas entre as expressões “Então” e “Senão”;
* as instruções a serem executadas quando a condição é falsa estão descritas entre as expressões “Senão” e “Fim-do-se”


<img src="https://raw.githubusercontent.com/lucasmoraesdev/my-stuffs/main/algoritmos-resumo/img/linguagem-estruturada.png?token=ARJXBMQ6HBAPISLHR5LWW7TAKOR5A">


<style>
    img{
        display: flex;
        width: 50%;
        margin: 20px auto;
        border: 1px solid darkgrey;
    }
</style>