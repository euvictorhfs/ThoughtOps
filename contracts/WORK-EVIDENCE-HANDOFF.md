# Work Evidence Handoff Contract

Contrato interoperável entre ThoughtOps e LearningOps.

## Princípios

- O usuário controla a transferência.
- Evidência candidata não equivale a competência validada.
- ThoughtOps descreve o observado; LearningOps interpreta longitudinalmente.
- Dados mínimos, finalidade explícita e possibilidade de correção ou exclusão.
- Nenhum sistema deve inferir identidade, senioridade ou valor humano a partir de um artefato.

## Pacote ThoughtOps → LearningOps

```yaml
contract_version: 1.0
candidate_id: work-evidence-YYYYMMDD-NNN
created_at: ISO-8601
consent: explicit | pending
source:
  system: ThoughtOps
  artifact_type: email | jira | sprint_document | retrospective | decision | other
  artifact_ref: redacted-or-approved-reference
  date: YYYY-MM-DD
context:
  objective: string
  audience: string-or-unknown
  constraints: [string]
observation:
  behavior: string
  outcome: string
  assistance_level: none | clarification_only | guided | substantially_generated
  counterevidence: [string]
assessment:
  confidence: low | medium | high
  limits: [string]
privacy:
  classification: private | confidential | shareable
  redactions: [string]
```

O pacote deve conter resumo suficiente para auditoria sem reproduzir material confidencial desnecessário.

## Decisão LearningOps

```yaml
candidate_id: work-evidence-YYYYMMDD-NNN
decision: accepted | rejected | needs_demonstration | superseded
decided_at: ISO-8601
mapped_domain: string-or-null
mapped_competencies: [string]
rationale: string
metric_effects: []
review_after: date-or-null
```

Aceitação não implica alterar métrica. Toda alteração segue as regras de evidência do LearningOps.

## Retorno LearningOps → ThoughtOps

Somente informações aprovadas e acionáveis:

- prioridade de prática;
- gap relevante para a tarefa;
- restrição ou preferência;
- experimento curto;
- data de revisão.

Não retornar domínio completo, notas, perfil psicológico ou inferências de identidade.

## Contradição e correção

Não reescrever silenciosamente. Registre evento superseding, motivo e origem. O usuário pode contestar, corrigir, retirar consentimento e pedir remoção conforme as políticas aplicáveis.
