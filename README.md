# 🛡️ Desafio de Cibersegurança: Entendendo um Ransomware na Prática com Python

## 📝 Descrição do Projeto
Este projeto foi desenvolvido no âmbito da formação de cibersegurança da DIO e tem como objetivo demonstrar, de forma prática e educativa, o funcionamento lógico de um **Ransomware**. Utilizando a linguagem **Python**, o projeto divide-se em duas partes principais: a encriptação e a desencriptação de ficheiros.

---

## ⚙️ Estrutura do Projeto

O repositório contém os seguintes ficheiros principais:
* **`encrypter.py`**: Script responsável por procurar um determinado ficheiro e aplicar um algoritmo de encriptação para o bloquear.
* **`decrypter.py`**: Script responsável por reverter o processo, desencriptando o ficheiro com a chave correta.

---

## 🔍 Como Funciona (Lógica Técnica)

### 1. O Encrypter (`encrypter.py`)
* O script abre um ficheiro alvo no formato binário.
* Utiliza uma biblioteca de encriptação (como o `cryptography` em Python) para alterar os dados originais do ficheiro.
* O ficheiro original é substituído pela sua versão encriptada, tornando-se ilegível sem a chave correta.

### 2. O Decrypter (`decrypter.py`)
* Atua como a chave de recuperação (o "resgate").
* Lê o ficheiro encriptado e aplica a chave simétrica ou assimétrica correspondente para restaurar os dados originais.

---

## 🛡️ Considerações de Segurança e Mitigação
Este tipo de simulação é fundamental para analistas de segurança entenderem como os ataques de ransomware operam a nível de código. As principais formas de proteção contra estas ameaças incluem:
* **Backups regulares:** Manter cópias de segurança isoladas e offline.
* **Atualizações de sistemas:** Garantir que o sistema operativo e as aplicações estão atualizados.
* **Segurança de endpoints:** Utilizar soluções antivírus e de deteção avançada.

---

> *Projeto desenvolvido para fins educacionais e de estudo em cibersegurança.*
