README - Deploy rápido

Como servir localmente:

```bash
python3 -m http.server --directory public 8080
```

Deploy em Netlify:
- No painel Netlify, aponte `Publish directory` para `public/`.

Deploy no GitHub Pages:
- Use um Action para publicar `public/` ou configure Pages para usar `gh-pages` branch com o conteúdo de `public/`.

Observações:
- Atualmente a página referencia imagens em `assets/` na raiz. Se preferir, mova `assets/` para `public/assets/` e atualize os caminhos em `public/index.html`.
