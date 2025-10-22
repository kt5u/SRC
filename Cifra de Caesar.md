# Cifra de Caesar

> [!info]
> A **Cifra de Caesar** é uma das cifras de substituição mais simples e conhecidas. Consiste em substituir cada letra da mensagem original por outra, deslocada um número fixo de posições no alfabeto.  
> O alfabeto é considerado circular: após Z, volta-se a A.

---

## Como funciona

1. **Escolhe um valor de deslocamento** (por exemplo, 3).
2. **Para cada letra**, soma esse valor ao seu índice no alfabeto.
3. **Se passar de Z**, continua a contar a partir de A (alfabeto circular).

> [!note]
> A cifra pode ser facilmente quebrada por força bruta, já que existem apenas 25 chaves possíveis.

---

## Exemplo prático

Mensagem: `P O R T U G A L`  
Chaves para cada letra: `3 8 14 3 8 14 3 8`  
(este exemplo usa chaves variáveis para ilustrar o conceito geral; o mais comum é usar um único valor fixo)

| Letra original | P | O | R | T | U | G | A | L |
|:--------------:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Deslocamento   | 3 | 8 |14 | 3 | 8 |14 | 3 | 8 |
| Letra cifrada  | S | W | F | W | C | U | D | T |

> [!tip]
> Com um valor fixo (por exemplo, 3), este é o famoso exemplo "ABC" → "DEF".

---

## Exemplo clássico

Mensagem: `A B C D E F G`  
Deslocamento: **3**  
Resultado: `D E F G H I J`

---

## Como decifrar

> [!note]
> Para descifrar, subtrai o valor do deslocamento à letra cifrada (também circular).

---
## Ligações

- [[Criptografia Clássica]]
---
