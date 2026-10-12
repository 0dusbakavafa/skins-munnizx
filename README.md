# MunnizX skins

Site estático para GitHub Pages. A página principal é `index.html`; mantenha os arquivos JavaScript, CSS e a pasta `assets/` na estrutura deste pacote.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo, `munnizx-skins`).
2. Extraia todo o conteúdo deste ZIP.
3. Envie **o conteúdo desta pasta** para a raiz do repositório — `index.html` precisa ficar na raiz, não dentro de uma subpasta.
4. Abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/ (root)` e salve.
6. Aguarde a publicação e abra a URL exibida em Settings → Pages.

## Estrutura

- `index.html` — página principal e interface.
- `fish-menu.js`, `item-picker.js`, `wardrobe-app.js`, `wardrobe-preview.js` — lógica do menu, seletores, aplicação e pré-visualização.
- `category-icons.css`, `item-picker.css` — estilos auxiliares.
- `assets/` — ícones e recursos visuais locais.

## Notas importantes

- Preparado como projeto estático para GitHub Pages; não requer build npm.
- A interface de geração não usa saldo de pontos/créditos. A barra de progresso da exportação é apenas feedback de processamento.
- A pré-visualização e a exportação dependem dos arquivos capturados no Web Archive e da compatibilidade do navegador. Como a origem é um snapshot, não é possível garantir que todos os serviços/recursos externos originais continuem disponíveis.
- Faça o primeiro teste no link publicado antes de substituir qualquer site já em produção.
