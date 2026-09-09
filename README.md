# Teste do Preciso de Ajuda

Teste de usabilidade do novo fluxo de abertura de chamado do Pigz Partner.

Página única, sem build: `index.html`. Réplica da tela de Vendas com um defeito
plantado, o fluxo do "Preciso de ajuda" e o formulário de avaliação. Todos os
dados são fictícios — nada aqui conversa com sistema de produção.

As respostas são enviadas para um Web App do Google Apps Script (constante
`ENDPOINT_PADRAO`, no topo do script). Sem endpoint configurado, a página
oferece o download do `.md` no fim.
