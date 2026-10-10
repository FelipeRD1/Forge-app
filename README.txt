# FORGE — Treino e Rotina

PWA instalável para celular com:
- Plano de treino de 5 dias, marcação de exercícios, carga e repetições
- Cronômetro de descanso
- Ideias de refeições e lista de compras
- Hábitos, tarefas e contador de copos de água
- Histórico e exportação de backup
- Cache offline via service worker

## Como instalar no Android
O app precisa estar hospedado em HTTPS (ou rodar em localhost) para ser instalável como PWA.
1. Publique o conteúdo desta pasta em um host estático HTTPS, por exemplo GitHub Pages ou Netlify.
2. Abra a URL publicada no Chrome do Android.
3. Menu ⋮ > “Instalar app” ou “Adicionar à tela inicial”.

## Arquivos
- `index.html`: aplicativo
- `manifest.json`: metadados de instalação
- `sw.js`: cache offline
- `icon-192.png` e `icon-512.png`: ícones

## Dados
Os dados são armazenados localmente no navegador do aparelho. Use “Exportar” dentro do app para criar um backup JSON. Limpar os dados do navegador pode apagar o histórico. Não há sincronização em nuvem nem publicação na Play Store incluída neste pacote.
