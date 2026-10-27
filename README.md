# AI Team

Repositório de instruções, papéis e fluxos de trabalho para uma equipe de agentes de IA que apoia estratégia, arquitetura, engenharia e revisão de software. Os documentos são independentes de plataforma sempre que possível; `platforms/` contém adaptações para ferramentas específicas.

## Como usar

1. Leia as políticas em `governance/` antes de delegar trabalho. Elas definem princípios, tomada de decisão, segurança e limites de aprovação.
2. Escolha o agente adequado em `agents/` e forneça o contexto do produto, as restrições e o resultado esperado. Isso inclui perfis especializados em marketing, jurídico e contábil quando a demanda exigir esses domínios.
3. Siga o fluxo correspondente em `workflows/`. Registre decisões relevantes e critérios verificáveis nos documentos do projeto.
4. Revise os resultados. Agentes podem analisar, recomendar e preparar mudanças, mas não substituem a autoridade humana definida pelas políticas.
5. Adapte as instruções da plataforma em `platforms/` sem enfraquecer as políticas de governança.

## Estrutura

- `agents/`: instruções e responsabilidades dos agentes executivos, de arquitetura, engenharia, negócios, jurídico, contábil e revisão.
- `governance/`: princípios comuns, política de decisão, segurança e aprovação humana.
- `workflows/`: processos reutilizáveis para novos projetos, implementação e revisões.
- `platforms/`: instruções de configuração para ambientes e ferramentas de IA específicos.
- `projects/`: contexto, requisitos, arquitetura, riscos, decisões e critérios de qualidade por projeto.
- `evaluations/`: rubricas e casos de teste para avaliar a qualidade do trabalho dos agentes.

## Ordem de precedência

Em caso de conflito, aplique nesta ordem:

1. Leis, regulamentos e políticas organizacionais aplicáveis.
2. `governance/constitution.md`, `governance/security-policy.md` e `governance/human-approval.md`.
3. `governance/decision-policy.md` e políticas específicas do projeto aprovadas por responsáveis humanos.
4. Fluxos de trabalho e instruções dos agentes.
5. Preferências locais da plataforma.

Uma instrução de nível inferior não pode autorizar uma ação proibida em nível superior. Diante de conflito ou ambiguidade com impacto material, interrompa a ação afetada e solicite decisão humana.

## Princípios de colaboração

- Trate as saídas dos agentes como propostas sujeitas a verificação, não como fatos ou aprovações implícitas.
- Diferencie evidências, hipóteses, riscos e recomendações; não invente contexto ausente.
- Mantenha decisões importantes, responsáveis, alternativas e consequências registradas.
- Use o menor acesso e a menor quantidade de dados necessários para a tarefa.
- Não execute ações externas, irreversíveis ou de alto impacto sem a aprovação exigida.

## Projetos

Cada projeto deve manter, conforme aplicável, um brief, requisitos, arquitetura, riscos, decisões (ADRs) e critérios de aceitação. Os documentos em `projects/exemplo-sistema/` servem como referência de organização, não como requisitos universais.
