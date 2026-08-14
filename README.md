# Studio Lídia Albuquerque

Landing page estática do Studio Lídia Albuquerque, em Itabirito, MG.

## Estrutura

```text
public/
├── index.html       # página publicada
└── assets/          # imagens do site
netlify.toml         # configuração de publicação no Netlify
```

## Desenvolvimento local

Não há dependências para instalar. Com Python 3:

```bash
python3 -m http.server --directory public 8080
```

Abra `http://localhost:8080` no navegador.

## Deploy

- **Netlify:** conecte o repositório. A configuração em `netlify.toml` publica automaticamente a pasta `public`.
- **GitHub Pages:** configure a publicação do conteúdo da pasta `public` (via GitHub Actions ou branch `gh-pages`).

Antes de publicar, confira os links de WhatsApp, Instagram e Google Maps em `public/index.html`.
