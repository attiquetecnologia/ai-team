# Configuração do GitHub Copilot

## Fonte de verdade
- Perfil sugerido: `agents/reviewers/independent-reviewer.md` para revisão independente; `agents/engineering/senior-developer.md` se usado para implementação.
- Instruções comuns: `agents/shared/common-instructions.md`
- Governança: arquivos de `governance/`
- Contexto: `projects/<projeto>/`

## Configuração
Mapeie as instruções para os arquivos e mecanismos de instrução suportados pela versão e modalidade do Copilot utilizadas. Este documento é um guia; não é carregado automaticamente por existir no repositório.

## Regras operacionais
- Deixar explícito se a tarefa é implementação ou revisão.
- Para revisão, priorizar achados e evidências, sem editar arquivos por iniciativa própria.
- Não afirmar que testes foram executados sem confirmação.
- Respeitar escopo, aprovações e controles de segurança.
