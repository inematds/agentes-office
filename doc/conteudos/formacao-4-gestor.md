# Formação 4 — Gestor e Líder com IA

**Promessa:** chegue em toda reunião com análise pronta — e lidere com dados, não com achismo.
**Pergunta de identificação (funil):** "Você responde por uma equipe e por resultados?"
**Resultado final:** um sistema operacional de gestão com IA para liderar projetos, pessoas e decisões.

## Persona

- **Quem:** gestores, líderes, coordenadores, diretores, empresários com equipe, consultores de gestão.
- **Profissões-alvo nomeadas:** **coordenadora de operações (equipe de 12)** e **diretor comercial de PME** (secundárias: gerente de projetos, dono de agência).
- **Dores:** agenda tomada por reunião; decide com informação incompleta e atrasada; status de projeto sempre desatualizado; comunicação com o time se perde; relatório pra cima consome o fim de semana.
- **Familiaridade:** confortável com planilhas e dashboards; delega tecnologia — o risco é ele querer "mandar alguém fazer o curso por ele".
- **Tempo por sessão:** 20–30 min, cedo ou tarde da noite.
- **Linguagem:** "indicador, prazo, time, 1:1, status, meta, decisão" — nunca "pipeline de dados, ETL".

## Nota do war game (riscos específicos do perfil)

- **Delegação do aprendizado:** o gestor quer que o analista faça. Antídoto na copy e no M1: *o julgamento não se delega — os agentes preparam, VOCÊ decide; quem opera o sistema detém o poder dele.*
- **Dados de pessoas (falha #15):** avaliação de desempenho e 1:1 são dados sensíveis de TERCEIROS. Bloco rígido: nada de nome de colaborador em análise de desempenho sem anonimizar; feedback gerado por IA é rascunho privado, nunca vai direto ao colaborador.
- **Risco de "IA gerencial fria":** comunicados gerados por IA soando robóticos queimam o líder. Antídoto: o agente de comunicação é alimentado pela voz do gestor (M4) e todo texto passa por edição humana declarada.

## Os 8 projetos práticos

| # | Projeto | Módulo | Entrada → Saída | Critério de pronto |
|---|---|---|---|---|
| 1 | **Agente de preparação de reuniões** (isca) | M3 | pauta + contexto → briefing: o que decidir, dados a pedir, perguntas certas, armadilhas | 1 reunião real preparada em ≤10 min |
| 2 | Agente de acompanhamento de projetos | M3–M4 | updates soltos do time → status consolidado com riscos e atrasos sinalizados | 1 status semanal real gerado |
| 3 | Agente de análise de indicadores | M3+M7 | planilha de KPIs → leitura executiva: o que mudou, por quê, onde agir | usado numa decisão real |
| 4 | Agente de comunicação com equipe | M3–M4 | decisão/contexto → comunicado no tom do líder (edição humana obrigatória) | 1 comunicado real enviado |
| 5 | Agente de criação de processos | M3 | processo informal descrito → processo documentado com papéis, etapas e critérios | 1 processo real documentado e adotado |
| 6 | Agente de análise de equipe e produtividade | M4+M3 | dados anonimizados de entregas → gargalos e hipóteses (nunca ranking de pessoas) | ≥1 gargalo real identificado |
| 7 | Agente de decisão estratégica | M4+M7 | dilema + dados + `/decisoes` da base → análise estruturada (opções, riscos, recomendação) | usado em 1 decisão real registrada |
| 8 | **SO de gestão com IA** (final) | M8 | entregas 1–7 → sistema montado + ritual semanal de gestão | 1 semana de uso relatada |

**Ferramentas:** ChatGPT, Claude, Codex básico, n8n, planilhas, dashboards, APIs, MCP conceitual, documentos.

## Adaptação dos módulos (deltas sobre o `modelo-unico.md`)

- **M1:** inventário guiado pela agenda ("quantas horas/semana em reunião que não gera decisão?"). Exemplo-fio: a coordenadora que descobriu 9h/semana de reunião de status substituível pelo Projeto 2.
- **M2:** biblioteca de 5 prompts = briefing de reunião, status de projeto, leitura de indicadores, comunicado ao time, estrutura de 1:1.
- **M4:** `/decisoes` é a pasta-estrela: cada decisão registrada com contexto e resultado — vira o histórico que o agente de decisão (P7) consulta. `/processos` documenta a operação do time.
- **M6:** mini-aplicação exemplo = painel simples de status do time (página gerada pelo Claude Code lendo a planilha exportada).
- **M7:** integração exemplo = planilha de indicadores → n8n → resumo executivo semanal no e-mail/Telegram do gestor. MCP apresentado conceitualmente (a tomada universal) com UMA demo guiada.
- **M8:** ritual semanal = revisão de domingo (20 min): status consolidado, indicadores lidos, pauta da semana pronta — o "domingo à noite" da copy vira produto.

## Copy do caminho (página de lançamento)

> Liderar é decidir. E você decide melhor quando a análise chega pronta, o status é de
> hoje e a reunião começa com as perguntas certas. Seus agentes preparam — você decide.
> Sua reunião de segunda podia estar pronta na sua mesa no domingo à noite. A partir
> desta formação, vai estar.

**Isca do perfil:** "Sua próxima reunião preparada em 15 minutos" — o Projeto 1 grátis: cola o prompt-agente, insere a pauta, recebe o briefing de decisão.
