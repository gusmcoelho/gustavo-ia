# GustavoIA

Chatbot interativo desenvolvido para operar de forma 100% gratuita, sem necessidade de chaves de APIs pagas e sem consumo de recursos para execução de modelos locais.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.111-005571?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-gray.svg?style=flat-square)](LICENSE)

---

## Como Funciona

A aplicação é estruturada de forma simples em duas partes:

1. **Frontend (Este Repositório Público):**
   Contém a interface visual do chatbot (HTML, CSS e JavaScript) hospedada gratuitamente no **GitHub Pages**. Ele cuida de enviar as mensagens do usuário e renderizar o texto em tempo real com Markdown e realce de código.

2. **Backend (Repositório Privado):**
   O processamento e a comunicação com o modelo de IA rodam através de uma API em **Python (FastAPI)** hospedada na nuvem no **Render** em um repositório privado, mantendo as configurações e a infraestrutura do servidor protegidas.

---

## Sobre o Projeto

O GustavoIA é uma aplicação web conversacional construída para oferecer uma interface moderna e rápida para interação com inteligência artificial com foco em custo zero:

- **100% Gratuito:** Não depende de planos pagos ou créditos de API comerciais.
- **Sem Processamento Local:** Não consome hardware do usuário (dispensando uso de GPU ou alto consumo de memória RAM).
- **Arquitetura em Nuvem:** Interface estática no GitHub Pages conectada a um serviço backend assíncrono no Render.

---

## Funcionalidades

- **Streaming em Tempo Real:** Respostas transmitidas de forma progressiva via streams assíncronos.
- **Formatação em Markdown:** Suporte completo à renderização de listas, tabelas e estruturas de texto.
- **Realce de Sintaxe:** Destaque de código com identificação automática de linguagens de programação via Highlight.js.
- **Histórico no Navegador:** Persistência local de sessões e chats utilizando a Web Storage API (localStorage).
- **Design Responsivo:** Interface adaptada para navegação em dispositivos móveis e desktop.

---

## Licença

Distribuído sob a licença [MIT](LICENSE).
