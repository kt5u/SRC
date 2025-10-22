

> [!info]
> [[Criptografia Simétrica]] é um método de encriptação onde a **mesma chave** é usada tanto para encriptar como para desencriptar a informação.

---

## Como funciona

- O emissor e o recetor partilham uma única chave secreta.
- Quem tiver a chave consegue transformar o texto cifrado de volta ao texto original.
- É necessário garantir que a chave é trocada de forma segura e não interceptada.
- Apenas usa métodos de substituição, transposição e lógica (XOR).

---

## Vantagens

- **Rapidez:** Algoritmos simétricos são geralmente muito rápidos e eficientes, mesmo para grandes volumes de dados.
- **Implementação simples:** São mais fáceis de implementar do que algoritmos assimétricos.

---

## Desvantagens

- **Distribuição da chave:** Todos os participantes precisam de ter a chave antes de comunicar. Se a chave for interceptada, a segurança é comprometida.
- **Escalabilidade:** Em grupos grandes, o número de chaves necessárias cresce rapidamente.

---

## Exemplos de algoritmos simétricos

- **AES (Advanced Encryption Standard)**
- **DES (Data Encryption Standard)**
- **3DES (Triple DES)**
- **RC4**

---

## Exemplo prático

> [!example]
> **Situação:**  
> O João quer enviar uma mensagem secreta à Maria. Ambos combinam previamente uma chave, por exemplo: `segredo123`.
> - João usa `segredo123` para encriptar a mensagem.
> - Maria recebe a mensagem cifrada e usa a mesma chave `segredo123` para decifrar.

---

## Ligações

- [[Criptografia Moderna]]

---