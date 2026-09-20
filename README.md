<div align="center">

<img src="logo.png" alt="Caça Ofertas" width="120">

# 🛒 CacaOfertas-Site

**Landing page oficial do canal [Caça Ofertas](https://t.me/cacaofertasofcBR) — achadinhos Shopee + Mercado Livre, todo dia no Telegram.**

<p align="center">
  <a href="https://andersonfqueiroz.github.io/CacaOfertas-Site/"><img src="https://img.shields.io/badge/Live-GitHub%20Pages-222?logo=github&logoColor=white" alt="Live"></a>
  <img src="https://img.shields.io/badge/HTML5-single--file-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-zero--deps-1572B6?logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JS-vanilla-F7DF1E?logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/SEO-OG%20%2B%20JSON--LD-green" alt="SEO">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT"></a>
</p>

**[➡️ Acessar o site](https://andersonfqueiroz.github.io/CacaOfertas-Site/)** · **[➡️ Canal no Telegram](https://t.me/cacaofertasofcBR)**

</div>

---

## ✨ Design

| Recurso | Descrição |
| :--- | :--- |
| 🌌 **Fundo aurora animado** | Blobs cyan/indigo em movimento + ruído sutil + vinheta (identidade marinho/cyan do canal) |
| 🪟 **Glassmorphism** | Nav fixa e cards em vidro com blur sobre o fundo animado |
| 📱 **Mockup de celular flutuante** | Prévia real do formato das ofertas + mini-cards de desconto |
| 🧱 **Bento grid** | Como funciona em 3 passos, contadores animados, cards de oferta e FAQ sanfona |
| 🔘 **CTA único pulsante** | Botão Telegram com glow + brilho varrendo, repetido no hero e no final |
| ⚡ **Performance** | Arquivo único ~20KB, sem frameworks, sem jQuery — só CSS + JS vanilla |
| ♿ **Acessível** | Respeita `prefers-reduced-motion`, layout mobile-first responsivo |
| 🔍 **SEO** | Meta description, Open Graph, canonical e JSON-LD |

---

## 📁 Estrutura do Projeto

```
CacaOfertas-Site/
├── index.html      # Landing completa (único arquivo, ~20KB)
├── blogger.html    # Variante encapsulada p/ colar no Blogger (sem <head>, sem JS)
├── logo.png        # Logo oficial (384px otimizada)
├── LICENSE         # MIT
└── README.md
```

> **Por que um repo separado?** O bot segue privado em [`CacaOfertas-Bot`](https://github.com/AndersonFQueiroz/CacaOfertas-Bot) (plano grátis não libera Pages em repo privado). Este repo é 100% público e estático — nenhum segredo, nenhuma chave, nenhum código do bot.

---

## 🚀 Como editar e publicar

### 1. Clone o repositório

```bash
git clone git@github.com:AndersonFQueiroz/CacaOfertas-Site.git
cd CacaOfertas-Site
```

### 2. Edite o `index.html`

Todo o site vive num único arquivo: CSS no `<style>`, JS no `<script>` final. Textos, preços de exemplo e links dos botões estão direto no HTML.

> ⚠️ Os 6 botões usam o link de tracking `pages` (`https://t.me/+aZsW9ZE1SMRiYmVh`). Não troque pelo link público — o tracking por origem mora em `CacaOfertas-Bot/docs/divulgacao_links.csv`.

### 3. Publique (deploy automático)

```bash
git add index.html && git commit -m "landing: descreva a mudança" && git push origin main
```

O **GitHub Pages** rebuilda sozinho a cada push na `main` (fonte: `/` raiz). Confirme em ~1 min:

```bash
curl -s -o /dev/null -w "%{http_code}\n" https://andersonfqueiroz.github.io/CacaOfertas-Site/
```

---

## 📝 Variante Blogger

O arquivo `blogger.html` é a mesma landing adaptada para colar em postagem do Blogger:

- Sem `<head>`/`<body>`/`<script>` (o Blogger descarta)
- CSS com escopo `.caca` + fundo escuro full-bleed via CSS embutido
- Números estáticos (sem contador JS) e botões com o link de tracking `blogger`
- Blog ao vivo: `cacaofertasofcbr.blogspot.com`

---

## 🔒 Segurança

- Nenhum segredo neste repo: sem `.env`, sem tokens, sem cookies, sem código do bot.
- Os links `t.me/+hash` são convites públicos de tracking — podem ser expostos sem risco.

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">

**Feito com ☕ e automação por [Anderson F. Queiroz](https://github.com/AndersonFQueiroz)**

*Pare de pagar caro — receba achadinhos todo dia.*

</div>
