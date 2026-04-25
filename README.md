# REAB GRUPE

Site estático para gerenciamento de pacientes e avaliações.

## Como executar localmente

1. Abra o terminal no diretório `reabgroup`
2. Execute:
   ```bash
   python3 -m http.server 8000
   ```
3. Abra no navegador:
   ```text
   http://localhost:8000/
   ```

## Como publicar na web

Este repositório já tem um workflow GitHub Actions para publicar em GitHub Pages.

1. Faça commit e push para a branch `main`
2. Acesse `Settings > Pages` no GitHub
3. Configure para publicar da branch `gh-pages`

Se precisar, posso também ajudar a configurar o domínio customizado ou publicar no Netlify/Vercel.``