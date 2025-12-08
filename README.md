# 🏦 Sistema de Conta Bancária (conta-bancaria-ts)

<p align="center">
  <img src="https://img.shields.io/badge/Projeto%20em%20TypeScript-Conta%20Banc%C3%A1ria-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="Badge do Projeto">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-OOP-2F74C0?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Terminal-CLI-000000?style=for-the-badge&logo=gnometerminal&logoColor=white">
  <img src="https://img.shields.io/badge/Bootcamp-Generation%20Brasil-F94877?style=for-the-badge">
</p>

---

## 🧐 Sobre o projeto

**Conta Bancária** é um projeto de prática em **TypeScript** desenvolvido durante o Bloco 01 do Bootcamp de Desenvolvimento Full-Stack em JavaScript da **Generation Brasil**.  
A aplicação é uma simulação de sistema bancário que roda no terminal (console) e possibilita operações básicas como **criar contas**, **depositar**, **sacar**, **transferir** e **consultar extrato/saldo**.

O foco do projeto é consolidar conceitos de **programação orientada a objetos (OOP)** em TypeScript, manipulação de dados em memória/arquivos e interação via terminal, além de lidar com validação e tratamento de erros.

---

## 🎯 Principais objetivos

- Implementar operações bancárias clássicas: depósito, saque, transferência e consulta de saldo/extrato;  
- Modelar entidades com OOP (Cliente, Conta, Transação);  
- Praticar **TypeScript** (tipagem forte, interfaces, classes, herança/composição);  
- Trabalhar entrada/saída via terminal (readline-sync);  
- Aprender boas práticas de tratamento de erros e validação de dados;  
- Preparar para testes manuais e cenários de uso reais.

---

## 🔧 Funcionalidades

- Criar novas contas (com titular e número);  
- Depositar valores em conta;  
- Sacar valores (com verificação de saldo);  
- Transferir entre contas;  
- Visualizar saldo e extrato;  
- Persistência simples (opcional: salvar/ler de arquivo JSON dependendo da implementação);  
- Mensagens e validações amigáveis no terminal.

---

## 💻 Tecnologias utilizadas

- **TypeScript** — tipagem estática e OOP  
- **Node.js** — execução da aplicação  
- **readline-sync** — leitura interativa no terminal  
- **ts-node** — executar arquivos `.ts` diretamente  
- (opcional) **fs** — para persistência em arquivo JSON

---
## 🚀 Como executar

1. Clone o repositório:
```bash
git clone https://github.com/MichelleGSilva/conta-bancaria-ts.git
cd conta-bancaria-ts

2. Instale as dependências:
npm install

3. Execute em modo de desenvolvimento (com ts-node):
npm run dev

O comando npm run dev deve estar configurado no package.json (ex: "dev": "ts-node src/index.ts"). Se preferir, compile e rode com tsc + node.

---
## Uso (fluxo típico no terminal)

Ao rodar o app, escolha uma opção do menu (ex: 1 - Criar conta, 2 - Depositar, 3 - Sacar, 4 - Transferir, 5 - Ver saldo, 6 - Extrato, 0 - Sair).

Siga as instruções exibidas, informe números e valores conforme pedido.

Mensagens de erro aparecem em casos de tentativa de saque maior que o saldo, conta inexistente, valores inválidos, etc.



