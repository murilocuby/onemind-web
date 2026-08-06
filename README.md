# onemind-web

Publicação estática do **FLG OneMind** em `onemind.cubyiq.com.br` (GitHub Pages).

O conteúdo deste repositório é **gerado** — não se edita nada aqui. A origem é
`Onemind/app`; para publicar uma versão nova:

```
npm run build:pages
```

e copiar o `dist/` por cima desta pasta antes do commit. O `build:pages` já
gera o `404.html` (rota de SPA), o `.nojekyll` e o `CNAME`.
