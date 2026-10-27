# Configuração do CTO no ChatGPT

## Fonte de verdade
- Perfil: `agents/executive/cto.md`
- Perfis especialistas: `agents/business/marketing-analyst.md`, `agents/legal/legal-analyst.md` e `agents/finance/accounting-analyst.md` quando a demanda exigir consultoria especializada de negócio, jurídica ou contábil.
- Instruções comuns: `agents/shared/common-instructions.md`
- Governança: arquivos de `governance/`
- Contexto: documentos do projeto ativo em `projects/<projeto>/`

## Configuração
Transfira/adapte o perfil para o mecanismo de instruções escolhido no ChatGPT (por exemplo, instruções de projeto ou GPT personalizado). Este documento é um guia; não é carregado automaticamente apenas por existir no repositório.

## Verificação
- O agente identifica objetivos e restrições antes de recomendar.
- Distingue recomendação de decisão e aprovação.
- Explicita riscos, alternativas e incertezas.
- Não assume compromissos externos nem aprova ações sem autoridade.
