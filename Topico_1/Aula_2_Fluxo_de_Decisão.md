# Fluxo de Decisão
Quando criamos um programa, esse mesmo segue um fluxo de leitura parecido com o nosso: Da esquerda pra direita, de cima para baixo. Ou seja, se levarmos em conta 
o código a seguir:
```
  var nome = 'João';
  nome = 'Maria';
```
Estamos criando a variável com o nome 'João', e depois *atribuindo* um novo nome, 'Maria'.
O **valor final** da variável nome é 'Maria'.

## If...else
Porém, há momentos em que queremos direcionar o curso do programa, como se ele estivesse seguindo uma estrada, e dependendo do valor de uma variável, 
nós decidimos ir para a esquerda ou para a direita.

Para definir esse curso nós utilizamos o **if** e o **else**, peguemos o exemplo abaixo:
```
  var idade = 21;
  
  if (idade >= 18) {
    console.log('Maior de Idade');
  } else {
    console.log('Menor de Idade');
  }
```

Nesse programa nós estamos dizendo: "Verifique se a idade é maior ou igual a 18, caso seja, retorne 'Maior de Idade', se não for, retorne 'Menor de Idade'". 
E ai, qual o resultado ?
Se você respondeu 'Maior de Idade', está corretíssimo, pois a variável 'idade' possui o valor 21, logo, é maior de idade.

* **Lembre-se**: O **else** sempre irá executar caso o **if** retorne falso, isso é, por exemplo, caso a idade não seja >= (maior ou igual) a 18.
