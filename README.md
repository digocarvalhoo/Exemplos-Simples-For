#Estrutura FOR;

🔂 Imprimindo Números Pares do Array 'numeros' - Somente-Pares.js

Explicação:
 - O código percorre o array numeros com um loop for, iniciando com i = 0 até i < numeros.length.
 - A cada iteração, o valor atual do array é armazenado na variável numero.
 - A condição if (numero % 2 === 0) verifica se numero é par (resto da divisão por 2 é igual a 0).
 - Se numero for par, ele é impresso usando console.log(numero).

 🔢 Gerando Tabuadas de Multiplicação de 0 a 10 - Tabuada-For.js

Explicação:
 - O código gera tabuadas de multiplicação de 0 a 10 usando dois loops for aninhados.
 - O loop externo (for (let numero = 0; numero <= 10; numero++)) itera de 0 a 10 para definir o número base da tabuada.
 - Para cada número base (numero), o código imprime o cabeçalho da tabuada usando console.log(Tabuada do ${numero}:).
 - O loop interno (for (let i = 1; i <= 10; i++)) itera de 1 a 10 para calcular e imprimir cada linha da tabuada (${numero} x ${i} = ${i * numero}).
 - Após imprimir todas as linhas da tabuada para um número base, é adicionada uma linha em branco usando console.log('') para melhor legibilidade entre as tabuadas.