# 📍 Buscador de Endereços por CEP - Java + API ViaCEP

Este projeto consiste em uma aplicação Java que permite consultar informações de endereço a partir de um CEP, utilizando a API pública do [ViaCEP](https://viacep.com.br/). Os dados são exibidos no console e salvos automaticamente em um arquivo `.json`.

---

## 🚀 Funcionalidades

- ✅ Entrada de CEP pelo usuário
- 🌐 Consumo da API ViaCEP usando `HttpClient`
- 🧾 Conversão do JSON com a biblioteca `Gson`
- 💾 Gravação automática do resultado em um arquivo `endereco.json`

---

## 📸 Demonstração

```bash
Digite o CEP para consulta (somente números): 01001000

📍 Resultado da consulta:
CEP: 01001-000
Rua: Praça da Sé
Bairro: Sé
Cidade: São Paulo
Estado: SP

✅ Dados salvos em 'endereco.json' com sucesso!

🧠 Conceitos e tecnologias usadas

Ferramenta/Tecnologia	Finalidade
Java 17	Linguagem de programação
API ViaCEP	Fornece dados de endereço via CEP
Gson (Google)	Serialização/deserialização de JSON
HttpClient	Requisições HTTP modernas com Java
FileWriter	Escrita de arquivos em Java

🛠️ Como executar o projeto
Clone o repositório:

bash

git clone https://github.com/seuusuario/consulta-cep-java.git
Abra no IntelliJ IDEA ou Eclipse

Execute a classe ConsultaCepApp

Digite um CEP válido!

📂 Estrutura de Pastas
css

📦 src
 ┣ 📜 ConsultaCepApp.java
 ┣ 📜 Endereco.java
 ┣ 📜 endereco.json

👩‍💻 Desenvolvido por
Monyse Moura
Estudante de Análise e Desenvolvimento de Sistemas | Backend Java




