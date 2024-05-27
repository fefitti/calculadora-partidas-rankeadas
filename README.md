# Calculadora de Partidas Rankeadas

Este é um projeto simples de uma calculadora de nível para jogadores com base no saldo de vitórias em partidas ranqueadas.

## Como Usar

1. Clone o repositório para o seu computador.
2. Abra o arquivo `calculadora.js` para ver a implementação da função.
3. Utilize a função `calcularNivel(vitorias, derrotas)` fornecendo o número de vitórias e derrotas do jogador para calcular o nível.

Exemplo de uso:

```javascript
let vitorias = 70;
let derrotas = 30;
let resultado = calcularNivel(vitorias, derrotas);
console.log(`O Herói tem saldo de ${resultado.saldoVitorias} e está no nível ${resultado.nivel}`);
