Criptografia Assimétrica

> [!info]
> [[Criptografia Assimétrica]] utiliza um **par de chaves** distintas: uma chave pública (que pode ser partilhada com qualquer pessoa) e uma chave privada (que deve ser mantida secreta).  
> Permite comunicação segura sem necessidade de trocar previamente um segredo.

---

## Como funciona

- Cada utilizador gera:
    - **Chave pública:** usada para encriptar mensagens ou verificar assinaturas.
    - **Chave privada:** usada para desencriptar mensagens ou criar assinaturas digitais.
- A chave pública pode ser livremente distribuída; a chave privada é confidencial.

---

## Vantagens

- **Dispensa troca prévia de segredo:** Não é preciso um canal seguro para trocar chaves.
- **Permite assinaturas digitais:** Garante autenticidade e integridade das mensagens.

---

## Desvantagens

- **Mais lenta:** Algoritmos assimétricos são mais lentos e computacionalmente exigentes do que os simétricos.
- **Chaves maiores:** Para atingir o mesmo nível de segurança, as chaves precisam ser bem maiores.

---

## Exemplos de algoritmos

- **RSA (Rivest–Shamir–Adleman)**
- **ECC (Elliptic Curve Cryptography)**
- **DSA (Digital Signature Algorithm)**

---

## Exemplo prático

> [!example]
> **Situação:**  
> O João quer enviar uma mensagem secreta à Maria.
> - Maria envia a sua **chave pública** ao João.
> - O João encripta a mensagem com a chave pública da Maria.
> - Só a Maria consegue desencriptar, usando a sua **chave privada**.

---

## Ligações

- [[Criptografia Moderna]]
- [[Criptografia Simétrica]]

---