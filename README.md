# DELIZZ — Loja virtual gratuita

Pacote inicial com:
- `index.html`: loja responsiva, catálogo, busca, categorias, sacola e painel administrativo.
- `Código.gs`: backend Google Apps Script conectado ao Google Sheets.
- `PASSO_A_PASSO.txt`: instruções para publicar.

## Importante
O GitHub Pages hospeda os arquivos estáticos. Ele não armazena estoque nem pedidos por conta própria. Por isso, a loja usa uma planilha Google Sheets por meio de um Web App do Apps Script.

A primeira versão usa JSONP para a comunicação com o Apps Script. O PIN administrativo é validado no servidor e a sessão fica em cache por até 6 horas. Não use essa arquitetura para dados altamente sensíveis nem armazene dados de cartão.

## Configuração
Siga `PASSO_A_PASSO.txt`. Não publique a URL do Web App em posts públicos se quiser limitar a exposição do endpoint, embora a URL seja necessária para a loja funcionar.
