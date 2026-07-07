# Formação 3 — Profissional Liberal Experiente com IA

**Promessa:** sua experiência de 20 anos operando 24h — pareceres, relatórios e triagem com a sua assinatura.
**Pergunta de identificação (funil):** "Você vive da sua expertise — consultório, escritório, consultoria?"
**Resultado final:** um segundo cérebro profissional com agentes para decisões, documentos, pesquisa e atendimento.

> **Perfil recomendado para a ONDA 1 do lançamento** (war game, Fase 0): dor mais clara,
> maior disposição a pagar, e o resultado (documento profissional) é o mais demonstrável.

## Persona

- **Quem:** médicos, advogados, arquitetos, consultores, engenheiros, professores, contadores, terapeutas, especialistas com carreira consolidada.
- **Profissões-alvo nomeadas:** **advogada de escritório próprio** e **médico de consultório** (secundárias: contador, arquiteta).
- **Dores:** afogado em documentos e laudos; hora vale caro mas escorre em tarefa repetitiva; atendimento sem preparo prévio; conhecimento de décadas preso na cabeça; medo de errar em público com tecnologia.
- **Familiaridade:** usa bem sistemas da área; cético com "modinha"; exige fonte e rigor.
- **Tempo por sessão:** 20–40 min, agenda imprevisível.
- **Linguagem:** "parecer, laudo, prontuário, petição, cliente/paciente, prazo, responsabilidade técnica" — respeitar o vocabulário de cada profissão nos exemplos.

## Nota do war game (riscos específicos do perfil — os mais graves da formação)

- **Sigilo e regulação (falha #15 da tabela mestre):** dado de paciente/cliente NUNCA entra em IA sem anonimização. Cada módulo tem o bloco "o que nunca colocar na IA" com exemplos da profissão (CFM/LGPD para médicos, sigilo OAB para advogados). Práticas usam casos fictícios fornecidos pelo curso.
- **Alucinação = risco profissional real:** um parecer com jurisprudência inventada destrói reputação. Regra de ouro ensinada desde o M2: **a IA redige, você assina — verificação de fonte é etapa obrigatória do fluxo, não opcional.**
- **Ceticismo alto:** este perfil não aceita promessa vaga. Toda promessa com número verificável; prova social da MESMA profissão.

## Os 8 projetos práticos

| # | Projeto | Módulo | Entrada → Saída | Critério de pronto |
|---|---|---|---|---|
| 1 | **Agente de triagem e preparação de atendimento** (isca) | M3 | dados básicos do caso (anonimizados) → resumo, hipóteses a explorar e perguntas para a consulta/reunião | preparou 1 atendimento real em ≤10 min |
| 2 | Agente de pesquisa especializada | M3+M7 | pergunta técnica → levantamento com fontes citadas e nível de confiança | usado numa dúvida real, fontes conferidas |
| 3 | Agente de relatórios e pareceres | M3–M4 | notas do caso → minuta no padrão do profissional (estrutura, tom, jurisprudência/refs A VERIFICAR marcadas) | 1 minuta real revisada e assinada |
| 4 | Agente revisor de documentos | M3 | contrato/laudo/documento → riscos, inconsistências e cláusulas faltantes apontados | pegou ≥1 problema real |
| 5 | Agente de organização do conhecimento profissional | M4–M5 | modelos, teses, casos e protocolos → base .md estruturada e versionada | ≥10 arquivos reais |
| 6 | Agente de conteúdo técnico | M4+M3 | base + tema → artigo/post técnico com a voz do especialista | 1 conteúdo publicado |
| 7 | Base conectada (RAG simples / projeto com arquivos) | M7 | base do M5 anexada ao agente → respostas citando OS SEUS documentos | resposta cita arquivo correto |
| 8 | **SO de IA do consultório/escritório** (final) | M8 | entregas 1–7 → sistema montado + ritual semanal | 1 semana de uso relatada |

**Ferramentas:** ChatGPT, Claude, Perplexity, bases confiáveis da área, Markdown, RAG simples (projetos com arquivos), APIs, automações leves.

## Adaptação dos módulos (deltas sobre o `modelo-unico.md`)

- **M1:** inventário guiado pela hora cara ("quantas horas/semana você gasta em tarefa que não exige o SEU julgamento?"). Exemplo-fio: a advogada que gastava 6h/semana em minutas de rotina.
- **M2:** biblioteca de 5 prompts = triagem de caso, minuta de parecer/laudo, revisão de documento, pesquisa com fontes, resposta técnica a cliente/paciente.
- **M2 (extra fixo):** step "critérios de qualidade profissional" — o prompt sempre exige fontes marcadas para verificação e proibição de inventar referência.
- **M4:** `/decisoes` e `/processos` valem ouro: protocolos de atendimento e teses viram arquivos que os agentes consultam.
- **M6:** mini-aplicação exemplo = página de orientações pré-consulta / FAQ do escritório feita com Claude Code.
- **M7:** o projeto 7 (base conectada) é o clímax do perfil: "meus 20 anos respondendo por mim". Custo estimado exibido antes; camada gratuita primeiro.
- **M8:** `/03-regras` ganha seção regulatória da profissão; `/10-auditoria` registra toda verificação de fonte feita (trilha de responsabilidade).

## Copy do caminho (página de lançamento)

> Você levou 20 anos para saber o que sabe. A IA não substitui isso — ela multiplica.
> Um agente treinado nos SEUS modelos, nos SEUS protocolos, com o SEU tom, prepara a
> minuta às 6 da manhã. Você revisa, corrige e assina. A responsabilidade continua sua.
> O tempo, também — só que de volta.

**Isca do perfil:** "Seu próximo atendimento preparado em 15 minutos" — o Projeto 1 grátis com caso fictício da profissão: cola o prompt-agente, insere o caso, recebe triagem + perguntas prontas.
