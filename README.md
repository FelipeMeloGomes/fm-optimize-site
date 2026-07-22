# FM Optimize — Site Oficial

[![site](https://img.shields.io/badge/site-fmoptimize-0044ff?style=for-the-badge)](https://fmoptimize.vercel.app)

Landing page do [FM Optimize](https://fmoptimize.vercel.app), app desktop de otimização do Windows.

---

## Sobre

Página estática com informações sobre o app, download direto, changelog automático via GitHub API e FAQ. Sem build step — HTML, CSS e JavaScript puro.

## Funcionalidades

- **Hero animado** — fundo de circuito SVG com partículas luminosas
- **Carousel de screenshots** — com lightbox, zoom e autoplay
- **Download dinâmico** — links e tamanhos atualizados automaticamente via GitHub Releases API
- **Changelog** — renderiza o histórico de versões diretamente do GitHub
- **Dark/Light mode** — toggle com persistência no localStorage
- **Contadores animados** — números com efeito de contagem ao entrar no viewport
- **FAQ interativo** — seções expansíveis com `<details>`
- **Responsivo** — menu hamburger e layout adaptado para mobile

## Tech Stack

HTML · CSS · JavaScript · Vercel

## Desenvolvimento local

```bash
git clone https://github.com/FelipeMeloGomes/fm-optimize-site.git
cd fm-optimize-site
# Abra index.html no navegador ou use um servidor local
npx serve .
```

## Deploy

O deploy é automático via Vercel a cada push na branch `main`.

Domínio: [fmoptimize.vercel.app](https://fmoptimize.vercel.app)

## Estrutura

```
├── index.html          # Página principal
├── styles.css          # Estilos (dark/light theme)
├── script.js           # Lógica: carousel, lightbox, counters, releases API
├── manifest.json       # PWA manifest
├── vercel.json         # Configuração do Vercel
└── assets/
    ├── favicon.ico
    ├── fonts/          # Inter, JetBrains Mono
    ├── icon-*.png      # Ícones PWA
    └── screenshots/    # Screenshots do app
```

## Repositório principal

O código-fonte do app desktop está em [FelipeMeloGomes/FM-Optimization](https://github.com/FelipeMeloGomes/FM-Optimization).
