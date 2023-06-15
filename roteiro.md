# Roteiro de aula

- [Roteiro de aula](#roteiro-de-aula)
  - [Introdução](#introdução)
  - [Listas](#listas)
  - [Objetos](#objetos)
  - [Arrays](#arrays)
  - [Conclusão](#conclusão)

## Introdução

(± 10 minutos)

- Apresentação e boas-vindas às alunas, criando um ambiente acolhedor e encorajador.
- Explicação breve do objetivo da aula: proporcionar às alunas conhecimentos práticos sobre estruturas de dados em JavaScript.
- Destacar a importância de aprender sobre estruturas de dados em JavaScript, ressaltando como esses conceitos são fundamentais para o desenvolvimento de aplicativos e sites.
- Mencionar o potencial da área de tecnologia para mulheres em transição de carreira, enfatizando as oportunidades disponíveis e a diversidade que pode ser alcançada nesse campo.
- Reservar um tempo para conhecer um pouco mais sobre as alunas, suas motivações e expectativas em relação à aula. //Se tivesse mais tempo

## Listas

(± 20 minutos)

- Explicar o que são listas em JavaScript e para que servem, usando exemplos cotidianos que possam ser facilmente compreendidos pelas alunas.
- Mostras como listas são usadas em programas JavaScript, destacando casos de uso comuns, como lista de compras, lista de contatos ou lista de tarefas.

// Listas em JavaScript são representadas por arrays, que podem armazenar diversos tipos de dados.

// Elas servem para armazenar uma coleção de elementos de forma organizada e acessível.

// Exemplos de listas cotidianas:

```
let listaCompras = ['maçã', 'banana', 'leite', 'pão'];
```

```
let listaContatos = ['Maria', 'João', 'Ana'];
```

```
let listaTarefas = ['Estudar', 'Fazer exercícios', 'Limpar a casa'];
```

// A partir dessas listas, podemos realizar diversas operações, como adicionar, remover e acessar itens.

- Introduzir os conceitos básicos de como criar, acessar e modificar listas, demonstrando a sintaxe e os métodos específicos do JavaScript.

// Criando uma lista vazia

```
let minhaLista = [];
```

// Adicionando itens à lista usando o método push

```
minhaLista.push('item1');
minhaLista.push('item2');
minhaLista.push('item3');
```

// Acessando elementos da lista pelo seu índice

```
console.log(minhaLista[0]); // Output: 'item1'
```

// Modificando um item da lista

```
minhaLista[1] = 'item2 modificado';

console.log(minhaLista); // Output: ['item1', 'item2 modificado', 'item3']
```

- Explicar como criar uma lista usando um array em JavaScript, ressaltando a simplicidade e flexibilidade dessa estrutura de dados.
- Mostrar exemplos práticos de como adicionar e remover itens de uma lista, utilizando métodos como push, pop, shift e unshift.

// Adicionando itens no final da lista usando o método push

```
minhaLista.push('item4');
minhaLista.push('item5');
```

// Removendo o último item da lista usando o método pop

```
minhaLista.pop();
```

// Adicionando itens no início da lista usando o método unshift

```
minhaLista.unshift('item0');
```

// Removendo o primeiro item da lista usando o método shift

```
minhaLista.shift();

console.log(minhaLista); // Output: ['item1', 'item2 modificado', 'item3', 'item4']
```

- Explicar como percorrer uma lista usando loops, como for ou forEach, mostrando como acessar e manipular cada elemento individualmente.

// Percorrendo uma lista usando um loop for

```
for (let i = 0; i < minhaLista.length; i++) {
 console.log(minhaLista[i]);
}
```

// Percorrendo uma lista usando o método forEach

```
minhaLista.forEach(function (item) {
 console.log(item);
});
```

- Pedir às alunas para praticarem a criação e manipulação de listas através de um exercício prático.

// Exercício: Crie uma lista de números e realize as seguintes operações:

1. Adicione um número no final da lista
2. Remova o primeiro número da lista
3. Acesse o segundo número da lista e imprima no console
4. Percorra a lista e imprima todos os números no console

```
let numeros = [1, 2, 3, 4, 5];

numeros.push(6);
numeros.shift();
console.log(numeros[1]);

numeros.forEach(function (numero) {
 console.log(numero);
});
```

## Objetos

(± 25 minutos)

- Explicar o que são objetos em JavaScript e para que servem, enfatizando que eles permitem representar entidades do mundo real e suas características.
- Mostrar exemplos de como objetos são usados em programas JavaScript, como um objeto "pessoa" com propriedades como nome, idade e profissão.

// Objetos em JavaScript são estruturas de dados que permitem representar entidades do mundo real.
// Eles servem para agrupar propriedades e métodos relacionados a um determinado objeto.

// Exemplos de objetos em programas JavaScript:

```
let pessoa = {
 nome: 'Maria',
 idade: 30,
 profissao: 'Engenheira'
};

let carro = {
 marca: 'Toyota',
 modelo: 'Corolla',
 ano: 2020
};
```

// A partir desses objetos, podemos realizar diversas operações, como acessar, modificar e adicionar propriedades.

- Introduzir os conceitos básicos de como criar, acessar e modificar objetos, mostrando a sintaxe e as diferentes formas de atribuição de valores.

// Criando um objeto vazio

```
let meuObjeto = {};
```

// Atribuindo propriedades ao objeto usando a notação de ponto

```
meuObjeto.nome = 'Exemplo';
meuObjeto.idade = 25;
```

// Acessando propriedades do objeto usando a notação de ponto

```
console.log(meuObjeto.nome); // Output: 'Exemplo'
```

// Modificando uma propriedade do objeto

```
meuObjeto.idade = 30;

console.log(meuObjeto); // Output: { nome: 'Exemplo', idade: 30 }
```

- Explicar como criar um objeto em JavaScript, destacando a utilização de chaves {} e pares de chave-valor para definir as propriedades.
- Mostrar exemplos práticos de como acessar e modificar as propriedades de um objeto usando a notação de ponto e colchetes.

// Acessando propriedades do objeto usando colchetes e uma string com o nome da propriedade

```
console.log(meuObjeto['nome']); // Output: 'Exemplo'
```

// Modificando uma propriedade do objeto usando colchetes

```
meuObjeto['idade'] = 35;

console.log(meuObjeto); // Output: { nome: 'Exemplo', idade: 35 }
```

- Explicar como adicionar métodos a um objeto, demonstrando como uma função pode ser associada a uma propriedade de um objeto.

// Adicionando um método ao objeto usando a notação de ponto

```
meuObjeto.saudacao = function () {
 console.log('Olá!');
};
```

// Chamando o método do objeto

```
meuObjeto.saudacao(); // Output: 'Olá!'
```

- Realizar um exercício prático em que as alunas criem e manipulem objetos para resolver um problema específico.

// Exercício: Crie um objeto "aluno" com as seguintes propriedades: nome, idade e notas.

// Adicione um método ao objeto para calcular a média das notas.

// Acesse e imprima no console o nome, idade e média do aluno.

```
let aluno = {
 nome: 'Joana',
 idade: 20,
 notas: [7, 8, 9, 6],
 calcularMedia: function () {
   let total = 0;
   for (let i = 0; i < this.notas.length; i++) {
     total += this.notas[i];
   }
   return total / this.notas.length;
 }
};

console.log(aluno.nome); // Output: 'Joana'
console.log(aluno.idade); // Output: 20
console.log(aluno.calcularMedia()); // Output: média das notas do aluno
```

## Arrays

(± 25 minutos)

- Explicar o que são arrays em JavaScript e para que servem, ressaltando que eles permitem armazenar múltiplos valores em uma única variável.
- Mostrar exemplos de como arrays são usados em programas JavaScript, como uma lista de números ou uma lista de nomes.

// Arrays em JavaScript são estruturas de dados que permitem armazenar múltiplos valores em uma única variável.
// Eles servem para criar listas ordenadas de elementos relacionados.

// Exemplos de arrays em programas JavaScript:

```
let numeros = [1, 2, 3, 4, 5];
let nomes = ['Ana', 'João', 'Maria'];
```
// A partir desses arrays, podemos realizar diversas operações, como acessar, modificar e adicionar elementos.

- Introduzir os conceitos básicos de como criar, acessar e modificar arrays, mostrando a sintaxe e os métodos específicos do JavaScript.

// Criando um array vazio
```
let meuArray = [];
```
// Atribuindo valores ao array usando colchetes e índices
```
meuArray[0] = 10;
meuArray[1] = 20;
meuArray[2] = 30;
```
// Acessando elementos do array usando colchetes e índices
```
console.log(meuArray[0]); // Output: 10
```
// Modificando um elemento do array
```
meuArray[1] = 25;

console.log(meuArray); // Output: [10, 25, 30]
```
- Explicar como criar um array em JavaScript, enfatizando a flexibilidade para armazenar diferentes tipos de dados em um único array.
- Mostrar exemplos práticos de como adicionar e remover itens de um array usando métodos como push, pop, shift e splice.

// Adicionando elementos ao final do array usando o método push
```
meuArray.push(40);
```
// Removendo o último elemento do array usando o método pop
```
let ultimoElemento = meuArray.pop();

console.log(meuArray); // Output: [10, 25, 30]
```
// Removendo o primeiro elemento do array usando o método shift
```
let primeiroElemento = meuArray.shift();

console.log(meuArray); // Output: [25, 30]
```
// Adicionando elementos no início do array usando o método unshift
```
meuArray.unshift(5, 15);

console.log(meuArray); // Output: [5, 15, 25, 30]
```

- Explicar como percorrer um array usando loops, como for ou forEach, mostrando como acessar e manipular cada elemento individualmente.

// Percorrendo um array usando o loop for
```
for (let i = 0; i < meuArray.length; i++) {
  console.log(meuArray[i]);
}
```
// Percorrendo um array usando o método forEach
```
meuArray.forEach(function (elemento) {
  console.log(elemento);
});
```

- Destacar as diferenças entre listas e arrays em JavaScript.

```
- Listas geralmente se referem a estruturas de dados abstratas, enquanto arrays são uma implementação concreta de listas em JavaScript.
- Arrays em JavaScript são mais flexíveis, permitindo armazenar diferentes tipos de dados em um único array.
- Arrays possuem métodos específicos que facilitam a manipulação dos elementos.
```

- Propor um exercício prático em que as alunas utilizem arrays para resolver um desafio de programação.

// Exercício: Crie um array de números e remova todos os números pares do array.

// Em seguida, multiplique todos os números restantes por 2 e imprima-os no console.
```
let numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
```
// Removendo números pares do array
```
let numerosImpares = numeros.filter(function (numero) {
  return numero % 2 !== 0;
});
```
// Multiplicando os números restantes por 2
```
let numerosMultiplicados = numerosImpares.map(function (numero) {
  return numero * 2;
});

console.log(numerosMultiplicados); // Output: [2, 6, 10, 14, 18]
```

## Conclusão

(± 10 minutos)

- Fazer uma breve revisão dos conceitos apresentados na aula, destacando os pontos-chave e resolvendo quaisquer dúvidas restantes.
- Encorajar as alunas a praticar o que aprenderam através de exercícios e projetos, mencionando recursos online e comunidades de apoio que podem auxiliá-las nesse processo.
- Sugerir exercícios adicionais e projetos para que elas possam aplicar os conceitos de listas, objetos e arrays em JavaScript.
- Abrir espaço para perguntas e esclarecimentos adicionais, incentivando a participação ativa das alunas e criando um ambiente colaborativo.
- Finalizar a aula reforçando a importância da perseverança e da busca contínua por conhecimento na área de tecnologia, encorajando-as a explorar novos desafios e oportunidades.
- Oferecer apoio adicional para as alunas, como um grupo de estudo ou acompanhamento individual, caso estejam interessadas em aprofundar seus conhecimentos após a aula.
