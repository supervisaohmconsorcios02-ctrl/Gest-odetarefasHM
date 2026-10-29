# HM Gestão de Tarefas — protótipo

## Publicação
O projeto é estático e pode ser publicado pelo GitHub Pages. Envie `index.html` e a pasta `assets/` para a raiz do repositório.

## Perfis demonstrativos
- TI/Admin: administra o quadro de funcionários, perfis e áreas.
- Gestor: visualiza o Painel com indicadores de todos os supervisores e operadores.
- Supervisor: visualiza o Painel e tarefas da equipe identificada pelas áreas em comum.
- Operador: não possui acesso à aba Painel; vê suas tarefas e calendário individual.

## Importante
Este é apenas um protótipo demonstrativo. Os dados ficam no armazenamento local do navegador, não são sincronizados entre usuários e não há autenticação segura de produção. O escopo da equipe do supervisor neste protótipo é calculado pelas áreas em comum. Para uso real da empresa, será necessário backend, banco de dados, autenticação e uma relação explícita de supervisor por área.
