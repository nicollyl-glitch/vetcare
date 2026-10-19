# vetcare

# 🐾 VetCare - Hospital Veterinário e Centro Diagnóstico

O **VetCare** é uma aplicação web desenvolvida para um hospital veterinário fictício, focada em oferecer uma experiência intuitiva e acessível para tutores de animais de estimação que buscam atendimento médico especializado.

Este projeto simula o desenvolvimento front-end em ambiente profissional, aplicando boas práticas de arquitetura CSS, semântica HTML5, acessibilidade e responsividade.

---

## 🎯 Objetivo do Projeto

O objetivo principal da aplicação é apresentar as especialidades, o corpo clínico, a infraestrutura hospitalar e as dúvidas frequentes da clínica, garantindo um canal direto de contato emergencial via WhatsApp com integração com a API oficial.

---

## 🚀 Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Estruturação da página focada na acessibilidade, SEO e organização (tags `<header>`, `<nav>`, `<main>`, `<section>`, `<details>`, `<summary>`, `<footer>`).
- **CSS3 Moderno:**
  - **Design System com CSS Variables (`:root`):** Padronização de cores, tipografia, sombras e transições através de tokens.
  - **Metodologia BEM (Block Element Modifier):** Nomenclatura organizada e modular para seletores CSS.
  - **Unidades Relativas (REM, %, vh, vw):** Garantia de escala e fluidez do layout em diferentes dispositivos.
  - **Flexbox:** Organização e alinhamento responsivo dos componentes e cards[cite: 1].
  - **Microinterações:** Pseudo-classes (`:hover`) e efeitos de sombra (`box-shadow`) para melhor UX[cite: 1].
- **Google Fonts:** Importação da família tipográfica **Poppins** (pesos 400, 500, 600 e 700)[cite: 1].
- **API do WhatsApp:** Links estruturados para redirecionamento direto de contato emergencial[cite: 1].

---

## 📁 Organização da Arquitetura de Arquivos

O projeto segue a separação rigorosa de responsabilidades entre estrutura (HTML) e estilo (CSS)[cite: 1]:

```text
├── css/
│   ├── base.css          # Reset, definição da escala REM da raiz e variáveis (:root)
│   ├── layout.css        # Estrutura das seções, sidebar, footer e breakpoints
│   └── components.css    # Estilização de cards, botões, FAQ e microinterações (BEM)
├── assets/
│   └── images/           # Imagens institucionais e recursos visuais
├── index.html            # Estrutura semântica principal da aplicação
└── README.md             # Documentação do repositório