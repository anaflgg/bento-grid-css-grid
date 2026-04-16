# Bento Grid 🟪

![Status do Projeto](https://img.shields.io/badge/status-concluído-brightgreen)

> Layout bento grid responsivo desenvolvido a partir de um desafio do Frontend Mentor, com foco em mobile-first e CSS Grid para a versão desktop.

🔗 Desafio original: https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj

### ✨ [Veja o site ao vivo aqui!](https://anaflgg.github.io/bento-grid-main/)

---

### 📸 Screenshot

![Screenshot desktop](./assets/images/print-desktop.png)
![Screenshot mobile](./assets/images/print-mobile.png)

---

### 📖 Sobre o Projeto

Este projeto consiste em um layout bento grid responsivo, baseado em um desafio do Frontend Mentor.

O principal objetivo foi evoluir no uso de CSS Grid para construir um layout complexo de múltiplas colunas no desktop, um desafio de nível **Junior** no Frontend Mentor. Diferente dos projetos anteriores, aqui trabalhei com branches desde o início — `layout-desktop` para construir o grid e `fix-styles` para refinamentos finais.

---

### 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- Flexbox (mobile)
- CSS Grid (desktop)
- Media Queries
- Local Fonts com `@font-face` (DM Sans)

---

### 🧠 Aprendizados

- Aplicação da abordagem mobile-first com `@media (min-width)`
- Primeira experiência prática com CSS Grid, usando `grid-template-columns`, `grid-column` e `grid-row`
- Uso de `@font-face` para fontes locais em vez de Google Fonts
- Evolução no uso de Git: branches com propósitos específicos (`layout-desktop`, `fix-styles`) e commits semânticos (`feat:`, `fix:`, `refactor:`, `style:`)

---

### 🐛 Desafios

- **CSS Grid no desktop** foi o maior desafio do projeto. Entender como posicionar cada card usando `grid-column` e `grid-row` exigiu bastante tentativa e erro até o layout encaixar corretamente.

- **Fontes locais com `@font-face`** — o erro foi colocar o `sans-serif` como fallback dentro do próprio `@font-face`, quando o correto é declarar o fallback na propriedade `font-family` fora dele.

---

### 👷 Como Executar o Projeto

Este é um projeto estático, não precisa instalar nada.

1. Clone o repositório:
```bash
git clone https://github.com/anaflgg/bento-grid-css-grid.git
```
