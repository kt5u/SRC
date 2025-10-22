

> [!info]
> A [[Cifra de Vigenère]] é uma cifra de substituição polialfabética e um clássico exemplo de [[Criptografia Clássica]].  
> Usa uma palavra-chave para determinar o deslocamento de cada letra da mensagem.  
> O alfabeto é circular (após Z volta para A) e a chave repete-se até igualar o comprimento da mensagem.

---

## Como funciona

1. **Escreve a mensagem original.**
2. **Repete a chave** até ter o mesmo comprimento da mensagem.
3. Para cada letra:
    - Converte ambas (mensagem e chave) para índices (A=0, B=1, ..., Z=25).
    - Soma os índices (mod 26) para obter a letra cifrada.

---

## Exemplo prático

Mensagem: `B E J A`  
Chave:    `P O R T`  
Mensagem (índices): B=1, E=4, J=9, A=0  
Chave (índices):    P=15, O=14, R=17, T=19  

Somas (mod 26):  
- B + P = 1 + 15 = 16 → Q  
- E + O = 4 + 14 = 18 → S  
- J + R = 9 + 17 = 26 → 0 → A  
- A + T = 0 + 19 = 19 → T  

| Letra Mensagem | B | E | J | A |
|:--------------:|:-:|:-:|:-:|:-:|
| Letra Chave    | P | O | R | T |
| Resultado      | Q | S | A | T |

Cifrado: `Q S A T`

---

## Como decifrar

> [!note]
> Para descifrar, subtrai o valor da chave ao da letra cifrada (também módulo 26).

---

## Ligações

- [[Criptografia Clássica]]
- [[Cifra de Caesar]]
- [[Cifra de PlayFair]]

---