# LP Marcelo Lusardo

Landing page do ecossistema Austrália Sem Fronteiras, publicada em **marcelolusardo.com.br**.

Site estático (HTML/CSS/JS, sem build). A página principal é `index.html` e os arquivos ficam na raiz para o domínio servir direto.

## Antes de liberar para o Google
As páginas estão com `noindex` e o `robots.txt` bloqueia tudo (`Disallow: /`). Para indexar: trocar por `Allow: /`, adicionar a linha `Sitemap:` e remover `<meta name="robots" content="noindex, nofollow">`.
