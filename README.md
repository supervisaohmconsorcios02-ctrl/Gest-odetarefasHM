# HM Consórcios — Gestão de Tarefas (protótipo independente)

Este pacote contém um protótipo navegável em HTML/CSS/JavaScript para servir de base à migração do projeto criado na Emergent.

## Como testar localmente
1. Extraia o ZIP.
2. Abra `index.html` no Chrome/Edge.
3. Entre com uma das contas demonstrativas mostradas na tela de login.

## O que este protótipo já demonstra
- Identidade visual azul da HM Consórcios.
- Login demonstrativo por perfil (TI/Admin, Gestor, Supervisor e Operador).
- Navegação por painel, equipe/tarefas, minhas tarefas, calendário e administração.
- Criar tarefas/reuniões, alterar status e progresso.
- Cronômetro iniciar/pausar por tarefa.
- Comentários por tarefa.
- Dashboard com indicadores, tarefas atrasadas/parciais, produtividade ilustrativa e tabela de desempenho.
- Exportação CSV compatível com Excel e impressão/salvar como PDF pelo navegador.
- Dados de tarefas salvos no armazenamento local do navegador (`localStorage`).

## Limitações IMPORTANTES
Esta é uma **demonstração local**, não uma aplicação pronta para uso empresarial:
- Login e senhas são de demonstração no código; não são seguros.
- Os dados ficam apenas no navegador e não sincronizam entre pessoas ou computadores.
- Não existe banco de dados remoto, autenticação segura, controle de acesso no servidor ou atualização real-time multiusuário.
- Anexos, envio de e-mails automáticos, cadastro persistente de usuários/áreas e PDF com layout corporativo ainda precisam ser ligados a um backend.
- Não use dados reais, senhas reais ou informações confidenciais nesta versão.

## Próxima etapa para produção gratuita
Configurar um backend externo (por exemplo Supabase ou outro serviço compatível), criar tabelas e regras de acesso por perfil/área, habilitar autenticação real, armazenamento de anexos e uma função agendada para alertas. Depois, publicar o frontend e configurar as variáveis secretas fora do repositório.

## GitHub
Crie um repositório privado em https://github.com/new e envie `index.html` e `README.md`. Nunca coloque senhas, chaves de API ou dados reais no repositório.
