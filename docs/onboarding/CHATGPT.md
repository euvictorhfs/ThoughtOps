# Usando o ThoughtOps no ChatGPT — guia simples

Este guia serve para quem não programa.

## O que você vai criar

No ChatGPT, um **Projeto** reúne instruções, arquivos e chats relacionados. O ThoughtOps usa:

- instruções do projeto para o comportamento básico;
- um arquivo Core com as regras públicas;
- um arquivo Workspace com seu contexto privado;
- chats separados por resultado;
- o GitHub como fonte de verdade durável.

A memória do projeto ajuda com continuidade, mas não garante recuperação perfeita nem elimina erros. O protocolo do ThoughtOps reduz alucinações exigindo fontes, suposições visíveis e confirmação de memória.

## Se você já criou o projeto

Não precisa criar outro, a menos que queira uma separação mais forte de memória.

1. Abra o projeto **ThoughtOps**.
2. Abra o menu de três pontos e escolha **Configurações do projeto**.
3. Em **Memória**, selecione **Somente do projeto** e salve. A mudança pode levar algumas horas.
4. Confirme nas configurações pessoais que referência a memórias e histórico de chats está habilitada, quando disponível no seu plano.
5. Em instruções do projeto, cole o conteúdo de [CHATGPT_PROJECT_INSTRUCTIONS.md](../../runtime/CHATGPT_PROJECT_INSTRUCTIONS.md).

## Se ainda não criou

1. Na barra lateral do ChatGPT, clique em **Novo projeto**.
2. Dê o nome **ThoughtOps**.
3. Escolha **memória somente do projeto**.
4. Abra **Configurações do projeto**.
5. Cole as instruções do arquivo acima.

As instruções do projeto valem dentro dele e podem substituir suas instruções personalizadas globais.

## Adicione somente dois arquivos de runtime

Para começar, envie como fontes do projeto:

1. [THOUGHTOPS_CORE.md](../../runtime/THOUGHTOPS_CORE.md)
2. o arquivo privado **WORKSPACE_CONTEXT.md** do repositório ThoughtOps-workspace

Não é necessário enviar o repositório inteiro. Isso economiza limite de arquivos e reduz contexto irrelevante. Não compartilhe o arquivo privado.

O ChatGPT não recebe atualizações do GitHub automaticamente nesta versão. Quando esses arquivos mudarem, substitua manualmente as cópias no projeto.

## Crie o primeiro chat

Dentro do projeto, clique em novo chat. Nome sugerido:

**PROD — Onboarding ThoughtOps — data**

Cole:

> Leia as instruções e as fontes ThoughtOps disponíveis neste projeto. Não presuma que leu arquivos ausentes. Diga qual versão do Core e do Workspace encontrou, quais fontes usará e quais informações pessoais continuam desconhecidas. Em seguida, conduza meu onboarding em modo Production, fazendo somente uma pergunta por vez quando ela for necessária.

O ChatGPT deve responder com as fontes encontradas, não com uma história inventada sobre você.

## Como iniciar cada atividade

Abra um novo chat para cada resultado coerente. Cole o [Session Brief](../../templates/SESSION-BRIEF.md) ou escreva de forma simples:

> Modo Production. Preciso de [resultado]. O público é [pessoa/grupo]. Contexto: [contexto]. Não altere [restrição]. Sucesso significa [critério]. Antes de responder, liste somente suposições que podem mudar o resultado.

Você não precisa preencher campos irrelevantes.

## Organização recomendada

- **PROD — assunto — data:** uma entrega ou decisão.
- **EVOL — habilidade — data:** feedback e prática.
- **REVIEW — mês/trimestre:** evolução longitudinal.
- **SYSTEM — mudança:** perfil, memória, regras ou arquitetura.

Abra um novo chat quando mudar o resultado, a audiência, o modo ou o conjunto principal de evidências. Continue no mesmo chat enquanto estiver refinando a mesma entrega.

Não abra um chat por agente. Os papéis trabalham como lentes dentro da sessão.

## Encerrando uma sessão

Peça:

> Encerre esta sessão no formato ThoughtOps. Separe resultado, decisões, suposições abertas, evidências usadas, registros propostos e próximo passo. Não trate nada como memória aprovada sem minha confirmação.

Aprove, edite ou rejeite cada registro proposto. Depois atualize o Workspace no GitHub. A conversa sozinha não é a fonte de verdade.

## Quando o ChatGPT inventar contexto

Responda:

> Isso não está registrado nas fontes aprovadas. Classifique como hipótese, explique de onde veio e refaça sem assumir esse dado.

Se um chat antigo errado estiver influenciando o projeto, mova-o para fora do projeto ou exclua-o. Corrija também qualquer registro incorreto no Workspace.

## Uso seguro

- Não coloque senhas ou tokens no projeto.
- Trate arquivos privados conforme suas obrigações profissionais.
- Use fontes identificáveis para decisões importantes.
- Para trabalho de alto impacto, confira as afirmações fora do modelo.
- Um Projeto organiza contexto; ele não transforma toda resposta em verdade.

## Referências oficiais do ChatGPT

- [Projetos no ChatGPT](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)
- [Retenção de chats e arquivos](https://help.openai.com/en/articles/8983778-how-are-files-vs-chats-retained)

A interface e os limites podem mudar conforme produto e plano.
