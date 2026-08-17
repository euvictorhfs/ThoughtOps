# Onboarding simples no ChatGPT

## Configuração única

1. Crie um Projeto chamado **ThoughtOps**.
2. Nas configurações, use memória somente do projeto se quiser isolamento das demais conversas.
3. Conecte o GitHub e conceda acesso aos repositórios, quando essa opção estiver disponível.
4. Cole as instruções de [runtime/CHATGPT_PROJECT_INSTRUCTIONS.md](../../runtime/CHATGPT_PROJECT_INSTRUCTIONS.md).
5. Como fallback, envie ao Projeto os arquivos de runtime do Core e do Workspace.

## Primeiro e principal chat

Crie um chat chamado **Daily** e escreva:

> Quero usar o ThoughtOps no meu trabalho diário. Confirme quais fontes você realmente consegue acessar e depois me ajude com esta tarefa: [descreva a tarefa].

Depois, continue no mesmo chat. Não precisa abrir um chat por e-mail, Jira ou sprint.

Se a conversa ficar longa, lenta ou começar a misturar contextos, crie **Daily 2** ou **Daily — AAAA-MM**. Isso é manutenção prática, não uma regra rígida.

## Exemplos

- “Transforme estes números em um e-mail para liderança, sem exagerar conclusões.”
- “Crie uma descrição de Jira com contexto, escopo e critérios de aceite.”
- “Organize minhas notas em documento de sprint.”
- “Faça uma retrospectiva da entrega e separe fatos, interpretações e próximos passos.”
- “Revise este texto em inglês para um público dos EUA e explique mudanças culturais importantes.”

## Uso no celular

Use o mesmo Projeto e o chat Daily. O GitHub online continua sendo a fonte portátil; clone local é opcional. Se a integração GitHub não estiver acessível naquele momento, trabalhe com os arquivos do Projeto e registre depois o que precisa ser persistido.

## Manutenção

Use uma conversa separada, **Core Maintenance**, somente quando quiser mudar o sistema. Daily não altera o Core. Mudanças são feitas em branch, revisadas em PR e então mescladas.

## Atualizações e automação

Hoje, confirme acesso antes de depender de leitura ou escrita no GitHub. Uma rotina futura pode preparar atualizações do Workspace, mas só deve ser ativada depois de um teste manual de permissões, escopo, revisão e recuperação. Dashboards, integrações e outras automações ficam anotados como evolução futura sob solicitação.
