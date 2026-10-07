# Controle Financeiro — PWA

Versão atualizada com filtro de Cartões, edição/exclusão de lançamentos, backup/restauração e lógica de cartão de crédito.

## Atualização no GitHub Pages

1. Faça o backup dos dados pelo botão **Exportar backup** antes de substituir os arquivos.
2. No repositório do GitHub, substitua `index.html`.
3. Substitua também `service-worker.js` para atualizar o cache do PWA.
4. Faça o commit na branch `main`.
5. Aguarde a atualização do GitHub Pages.
6. Se o navegador mostrar uma versão antiga, faça `Ctrl + F5`.

## Backup

O botão **Exportar backup** gera um arquivo `.json` com os lançamentos. Para recuperar os dados, use **Restaurar backup** e selecione esse arquivo.

Os dados ficam salvos localmente no navegador/aparelho. O backup é necessário para transportar os dados entre dispositivos ou antes de uma atualização importante.
