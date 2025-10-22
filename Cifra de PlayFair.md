
> [!info]
> A [[Cifra de PlayFair]] é um método de [[Criptografia Clássica]] que utiliza uma matriz 5x5 para cifrar pares de letras.  
> O alfabeto tem apenas 25 posições, por isso "I" e "J" partilham a mesma célula na matriz.

---

## Como funciona

1. **Criar uma matriz 5x5** com a palavra-chave (sem letras repetidas, "I/J" juntos).
2. **Completar a matriz** com as restantes letras do alfabeto (também sem repetições).
3. **Agrupar a mensagem em pares de letras.**  
   - Se houver letras iguais num par, inserir uma letra neutra (ex: X).
   - Se a mensagem tiver número ímpar de letras, adicionar uma letra extra no fim.
4. **Cifrar cada par segundo as seguintes regras:**
    - **Mesma linha:** substituir cada letra pela da direita (volta ao início).
    - **Mesma coluna:** substituir cada letra pela de baixo (volta ao topo).
    - **Linhas e colunas diferentes:** cada letra troca para a coluna do par (“retângulo”).

---

## Exemplo de matriz ("BENFICA")

|  B  |  E  |  N  |  F  | I/J |
| :-: | :-: | :-: | :-: | :-: |
|  C  |  A  |  D  |  G  |  H  |
|  K  |  L  |  M  |  O  |  P  |
|  Q  |  R  |  S  |  T  |  U  |
|  V  |  W  |  X  |  Y  |  Z  |

---

## Exemplo prático

Mensagem: `P O R T U G A L`  
Agrupamento em pares: `PO RT UG AL`

| Par | Situação                  | Resultado |
|-----|---------------------------|-----------|
| PO  | Linhas/colunas diferentes | K P       |
| RT  | Linhas/colunas diferentes | S U       |
| UG  | Linhas/colunas diferentes | T H       |
| AL  | Linhas/colunas diferentes | L R       |

Cifrado: `K P S U T H L R`

> [!note]
> Se a mensagem tiver número ímpar de letras, adiciona-se uma letra extra no final ao agrupar.

---

## Ligações

- [[Criptografia Clássica]]
---