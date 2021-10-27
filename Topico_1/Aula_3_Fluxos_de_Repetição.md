# Fluxo de Repetição
Enquanto o fluxo de decisão lida com a direção, o rumo que o programa vai tomar, o fluxo de repetição lida com a quantidade de vezes que o código vai executar 
em determinado trecho.

Peguemos como exemplo:

```
1  var contador = 0;
2  
3  while (contador <= 10) {
4    console.log(contador);
5    contador = contador + 1;
6  }  
```
* Nesse trecho criamos uma variável chamada **contador** com o valor **0**, na **linha 1**.
* Logo após, na **linha 3**, nós **declaramos um loop** chamado **while**, que executa a expressão entre parênteses **(contador <= 10)** e, enquanto ela retornar **verdadeira**, irá executar o que está entre **{}**.
* Na **linha 4** nós falamos ao programa nos dar um output com o valor de **contador**, que na **linha 1** tinha sido previamente declarado com o valor **0**.
* Na **linha 5**, nós falamos ao programa *"Pegue a variável contador, e incremente em 1 o valor dela"*.
No final desse trecho de código, o próprio programa vai verificar se **a variável contador** é <= (*menor ou igual*) a 10, repetindo o trecho até que o valor 
de contador seja **11**.

As duas formas de declarar loops são:
```
  while (expressao_a_ser_avaliada) {
    // Trecho de código que irá repetir enquanto a expressão for verdadeira
  }
  
  for (variavel_de_contagem ; expressao_a_ser_avaliada ; comando_a_ser_executado_ao_final_de_cada_loop) {
    // Trecho de código que irá repetir enquanto a expressão for verdadeira
  }
```

Ambos os loops tem a mesma função de executar o código repetidas vezes, tanto que,o código a seguir faz **exatamente** a mesma coisa que o código que foi visto anteriormente:
```
  for (var contador = 0 ; contador <= 10 ; contador++) {
    console.log(contador)
  }
```
