# GustavoIA

Chatbot interativo desenvolvido para operar de forma 100% gratuita, sem necessidade de chaves de APIs pagas e sem consumo de recursos para execução de modelos locais.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.111-005571?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-gray.svg?style=flat-square)](LICENSE)

---

## Sobre o Projeto

O GustavoIA é uma aplicação web conversacional construída para oferecer uma interface moderna e rápida para interação com inteligência artificial. O projeto foi projetado com foco em custo zero de infraestrutura e operação:

- **100% Gratuito:** Não depende de créditos, planos pagos ou chaves de API comerciais.
- **Sem Processamento Local:** Não exige execução de modelos pesados no hardware do usuário (dispensando uso de GPU ou alto consumo de memória RAM).
- **Arquitetura em Nuvem:** Interface estática hospedada via GitHub Pages conectada a um serviço backend assíncrono em FastAPI hospedado no Render.

---

## Funcionalidades

- **Streaming em Tempo Real:** Respostas transmitidas de forma progressiva via streams assíncronos.
- **Formatação em Markdown:** Suporte completo à renderização de listas, tabelas e estruturas de texto.
- **Realce de Sintaxe:** Destaque de código com identificação automática de linguagens de programação via Highlight.js.
- **Histórico no Navegador:** Persistência local de sessões e chats utilizando a Web Storage API (localStorage).
- **Design Responsivo:** Interface adaptada para navegação em dispositivos móveis e desktop.

---

## Arquitetura e Tecnologias

- **Frontend:** HTML5, CSS3 estruturado com variáveis de tema e JavaScript (ES6+).
- **Backend:** Python e FastAPI para roteamento assíncrono e controle de requisições.
- **Hospedagem & CI/CD:** GitHub Pages (distribuição estática), Render (serviço web) e GitHub Actions (rotina de disponibilidade).

---

## Licença

Distribuído sob a licença [MIT](LICENSE).
