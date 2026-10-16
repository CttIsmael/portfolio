# Portfólio · Ismael Oliveira

Site estático (HTML, CSS e JavaScript puros), sem build. Pronto para GitHub + Cloudflare Pages.

## Estrutura

```
index.html                      página completa (PT/EN)
assets/img/                     imagens dos projetos, foto, favicon e imagem de compartilhamento
assets/cv/Curriculo_Ismael_Oliveira.pdf   currículo baixado pelo botão do site
robots.txt / sitemap.xml        orientam os buscadores (Google, Bing)
_headers                        cache das imagens no Cloudflare
```

## Endereço

https://ismaeloliveiradesign.pages.dev

## Como atualizar

- **Currículo:** substitua `assets/cv/Curriculo_Ismael_Oliveira.pdf` por um arquivo com o mesmo nome.
- **Imagem de um projeto:** substitua o arquivo em `assets/img/` mantendo o nome
  (ex.: `4play.webp` e `4play-thumb.webp`). Proporção ideal: 4:3, 1600 × 1195 px.
- **Novo projeto ou textos:** no `index.html`, procure por `const PROJECTS` (projetos) ou
  `const I18N` (textos em português e inglês).

Cada alteração enviada ao GitHub publica o site de novo automaticamente.
