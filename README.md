# Controle de Expedição

App web para controle diário de rotas da expedição: quantidades, prazos D0/D1/D2, express e baixas.
Funciona no celular, instala na tela inicial e funciona sem internet. Os dados ficam salvos no próprio aparelho.

## Arquivos
- `index.html` – o app
- `manifest.json` – nome e ícone para instalar no celular
- `sw.js` – permite usar sem internet
- `icon-192.png`, `icon-512.png`, `icon-maskable.png` – ícones

## Publicar grátis (GitHub Pages)
1. Coloque todos os arquivos na raiz do repositório.
2. Settings → Pages → Branch `main` / `(root)` → Save.
3. Acesse `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Atualizar
Substitua os arquivos, faça Commit e Sync. Ao lançar uma versão nova, mude o nome do cache em `sw.js`
(ex.: `expedicao-v3.1`) para os celulares pegarem a atualização.

## Backup
Os dados ficam só no aparelho. Use Mais → Backup toda semana.
