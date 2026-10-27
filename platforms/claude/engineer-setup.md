# Configuração do Engenheiro de Software no Claude

## Fonte de verdade
- Perfil: `agents/engineering/software-engineer.md`
- Perfis especialistas: `agents/business/marketing-analyst.md`, `agents/legal/legal-analyst.md` e `agents/finance/accounting-analyst.md` quando a tarefa exigir análise fora do escopo técnico.
- Instruções comuns: `agents/shared/common-instructions.md`
- Governança: arquivos de `governance/`
- Contexto: documentos do projeto ativo em `projects/<projeto>/`

## Configuração
Adapte o perfil ao mecanismo de instruções/projeto disponível no Claude. Indique explicitamente o papel ativo, as entradas esperadas e os entregáveis técnicos.

Este documento é um guia de configuração e não é aplicado automaticamente pelo repositório.

## Verificação
- Produz especificações implementáveis e testáveis.
- Identifica dependências e riscos.
- Não altera decisões arquiteturais materiais unilateralmente.
