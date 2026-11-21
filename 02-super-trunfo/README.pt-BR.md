# Super Trunfo – Países

🇺🇸 [Read in English](README.md)

Cadastro de cartas de um jogo de Super Trunfo em que cada carta representa uma cidade. Desafio do curso de Programação em C, dividido em níveis.

## Níveis

| Pasta | O que faz | Conceitos praticados |
|---|---|---|
| `nivel-novato/` | Cadastra uma carta (estado, código, cidade, população, área, PIB e pontos turísticos) e exibe os dados | variáveis, `scanf`, `printf` |
| `nivel-aventureiro/` | Cadastra duas cartas e calcula a densidade populacional e o PIB per capita de cada uma | operações aritméticas, conversão entre `int` e `float` |

## Como rodar

```bash
gcc nivel-novato/cadastro_carta.c -o cadastro_carta
./cadastro_carta
```

O código das cartas segue o formato letra do estado + número da cidade, por exemplo `A01` ou `B03`.
