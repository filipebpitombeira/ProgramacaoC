# Super Trunfo – Countries

🇧🇷 [Leia em português](README.pt-BR.md)

Card registration for a *Super Trunfo* game (a Brazilian card game similar to Top Trumps), where each card represents a city. A challenge from my C programming course, split into levels.

## Levels

| Folder | What it does | Concepts practiced |
|---|---|---|
| `nivel-novato/` (beginner) | Registers one card (state, code, city, population, area, GDP and tourist attractions) and displays its data | variables, `scanf`, `printf` |
| `nivel-aventureiro/` (adventurer) | Registers two cards and calculates each one's population density and GDP per capita | arithmetic operations, `int` to `float` conversion |

## How to run

```bash
gcc nivel-novato/cadastro_carta.c -o cadastro_carta
./cadastro_carta
```

Card codes follow the format state letter + city number, for example `A01` or `B03`.
