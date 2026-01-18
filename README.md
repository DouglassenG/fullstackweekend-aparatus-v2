# 🔭 Aparatus V2 - Estudo de Arquitetura Full Stack

![Status](https://img.shields.io/badge/Status-Em_Análise-yellow)
![Next.js](https://img.shields.io/badge/Framework-Next.js_14-black?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/Lib-React-61DAFB?logo=react&logoColor=black)
![NodeJS](https://img.shields.io/badge/Runtime-Node.js-green?logo=node.js&logoColor=white)

> Este repositório é um **Fork de Estudo** baseado no projeto Aparatus V2. O objetivo é dissecar e compreender as decisões arquiteturais, padrões de código e integrações implementadas em uma aplicação Next.js de nível de produção.

## 🎯 Motivação e Propósito

No desenvolvimento sênior, a habilidade de ler e entender código legado ou de terceiros é tão importante quanto escrever código novo. O propósito deste fork é servir como um **Laboratório de Aprendizado**.

Este projeto resolve a lacuna entre a teoria e a prática, permitindo a análise detalhada de:
* **Estruturação de Pastas em Next.js:** Como organizar páginas, componentes e serviços.
* **Server-Side Rendering (SSR) vs Static Generation (SSG):** Estudo de estratégias de renderização.
* **Integração de APIs:** Como o Frontend consome e trata dados do Backend.

## 🛠️ Tecnologias Utilizadas

A stack tecnológica analisada neste projeto inclui:

* **[Next.js](https://nextjs.org/):** Framework React principal para produção (Full Stack).
* **[ReactJS](https://react.dev/):** Biblioteca para construção de interfaces de usuário baseada em componentes.
* **[TypeScript/JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Linguagem base da aplicação.
* **[CSS Modules / Tailwind](https://tailwindcss.com/):** (A confirmar no código) Estratégia de estilização e design system.
* **[ESLint/Prettier](https://eslint.org/):** Ferramentas de padronização e qualidade de código.

## ✨ Funcionalidades Analisadas

Durante o estudo deste código, os seguintes pontos são destacados:

1.  **Roteamento Dinâmico:** Análise de como o Next.js gerencia rotas e parâmetros na URL.
2.  **Gerenciamento de Estado:** Identificação de como os dados fluem entre componentes (Context API ou Props Drilling).
3.  **Componentização:** Estudo da quebra de responsabilidades em componentes menores e reutilizáveis.
4.  **Hooks Personalizados:** Análise da lógica abstraída em *Custom Hooks* para reutilização de regras de negócio.

## 📂 Estrutura de Arquivos (Análise)

A organização do projeto segue as convenções modernas do Next.js:

```text
fullstackweekend-aparatus-v2/
├── public/              # Arquivos estáticos (imagens, favicon)
├── src/
│   ├── components/      # Componentes visuais isolados
│   ├── pages/ (ou app/) # Rotas da aplicação e Views
│   ├── styles/          # Arquivos de estilização global
│   └── utils/           # Funções auxiliares e helpers
├── package.json         # Dependências e Scripts
└── README.md            # Documentação de Estudo
