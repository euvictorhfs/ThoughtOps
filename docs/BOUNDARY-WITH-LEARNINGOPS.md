# Boundary with LearningOps

## Decisão arquitetural

ThoughtOps e LearningOps se complementam, mas não executam a mesma função.

| Necessidade | Sistema responsável |
|---|---|
| Produzir e revisar e-mail, Jira, sprint, retrospectiva ou decisão | ThoughtOps |
| Melhorar o artefato atual e explicar escolhas relevantes | ThoughtOps |
| Guardar contexto, preferências e decisões do trabalho | ThoughtOps Workspace |
| Sugerir uma evidência surgida no trabalho | ThoughtOps |
| Estudar deliberadamente um tema | LearningOps |
| Validar evidência e atualizar domínio observado | LearningOps |
| Manter currículo, PDI, gaps, repertório validado e evolução longitudinal | LearningOps |
| Construir currículo profissional baseado em evidências | LearningOps |

## Regra de decisão

- Se a pergunta é **“como produzir melhor agora?”**, use ThoughtOps.
- Se a pergunta é **“o que estou aprendendo e demonstrando ao longo do tempo?”**, use LearningOps.

## O que permanece no ThoughtOps

Nenhuma capacidade operacional é removida. ThoughtOps continua capaz de observar raciocínio, postura, comunicação e inglês no artefato atual; dar feedback; sugerir melhoria; e gerar um candidato de evidência.

Ele não transforma uma observação pontual em domínio, perfil profissional longitudinal ou currículo. Isso evita inferência de identidade e dupla contabilidade.

## Fluxo entre sistemas

1. ThoughtOps conclui o trabalho.
2. Se houver sinal útil, oferece um candidato de evidência.
3. O usuário decide se quer transferi-lo.
4. LearningOps valida, rejeita ou pede demonstração adicional.
5. LearningOps pode devolver ao ThoughtOps apenas prioridades aprovadas, como “praticar síntese executiva”.
6. ThoughtOps usa a prioridade na tarefa atual sem copiar o perfil completo do LearningOps.

A transferência pode ser manual por copiar e colar. Automação não é requisito.
