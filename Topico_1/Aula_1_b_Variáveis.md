# Variáveis
Imagine o seguinte: Você tem uma caixinha e nela você pode guardar várias coisas, um livro da Culpa é das Estrelas, um martelo, um Buzz Lightyear,
porém nessa caixinha, uma vez que você coloca um martelo, você só pode colocar ferramentas, assim como se você colocar um livro qualquer, você só poderá colocar livros 
ali dentro.
Transferindo isso para o âmbito da computação, essas caixinhas se chamam **variáveis**, e cada tipo de valor computacional que essas variáveis armazenam, são os objetos 
e suas classificações. Mas afinal, que classificações são essas?

## Tiṕos
Para esse primeiro contato, nós vamos considerar 3 classificações de variáveis:
  * Número: São as variáveis que possuem um valor **numérico**.
  * String: São as variáveis que possuem um valor de **texto**.
  * Boolean:  São as variáveis que possuem como valor **Verdadeiro** ou **Falso**.

## Como Declarar
Existem 2 meios de declarar variáveis:
  * `var`: Para quando a variável possui um *escopo* *global*.
  * `let`: Para quando a variável possui um escopo *local*.
Também existem as **constantes**, que são valores fixos imutáveis e possuem um escopo local.
Para declarar uma constante, se utiliza o comando `const`.

## Exemplos
Vamos criar um pequeno programa que simula os dados de uma pessoa, onde cada variável armazena um valor:
  * A variável **nome** é uma **string** com o valor 'João'.
  * A variável **idade** é um **número** com o valor 21.
  * A variável **maiorDeIdade** é uma **booleana** com o valor `true`, pois João é maior de idade.
  * A variável **sexoFeminino** é uma **booleana** com o valor `false`, pois na hora do registro João negou ser do sexo feminino.
```
  var nome = 'João';
  var idade = 21;
  var maiorDeIdade = true;
  var sexoFeminino = false;  
```
