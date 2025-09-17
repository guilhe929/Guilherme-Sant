# Guilherme-Sant# 

exemplos-cyberseguranca/
├─ README.md
├─ .gitignore
├─ LICENSE
├─ c/
│  └─ encrypt.c
└─ java/
   └─ SecureExample.java
# 🔐 Exemplos de Cybersegurança

[![Language: C](https://img.shields.io/badge/language-C-blue)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Language: Java](https://img.shields.io/badge/language-Java-orange)](https://en.wikipedia.org/wiki/Java_(programming_language))

Este repositório contém exemplos **didáticos** de criptografia em **C** e **Java**.

⚠️ **Atenção**: são exemplos educacionais. Para produção, use bibliotecas modernas, proteja suas chaves e siga boas práticas de segurança.

## 📂 Conteúdo
- `c/encrypt.c` → Exemplo de encriptação AES-256-CBC em C (com OpenSSL).
- `java/SecureExample.java` → Exemplo de encriptação AES-GCM em Java.

## ▶️ Como executar

### C
```bash
gcc c/encrypt.c -o c/encrypt -lcrypto
./c/encrypt encrypt input.txt output.bin
./c/encrypt decrypt output.bin recovered.txt
