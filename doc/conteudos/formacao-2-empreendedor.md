# Formação 2 — Empreendedor Estratégico com IA

**Promessa:** uma equipe digital de vendas, conteúdo e atendimento — que custa menos que um estagiário.
**Pergunta de identificação (funil):** "Você é dono do negócio e faz de tudo um pouco?"
**Resultado final:** um sistema de IA para vender, atender, criar conteúdo e decidir melhor.

## Persona

- **Quem:** empreendedores, pequenos empresários, MEIs, prestadores de serviço, donos de negócio local, infoprodutores, gestores comerciais.
- **Profissões-alvo nomeadas:** **dona de loja de roupas (física + Instagram)** e **prestador de serviços (marido de aluguel/reformas)** (secundárias: infoprodutora, dono de restaurante).
- **Dores:** faz tudo sozinho; marketing irregular ("posto quando dá"); orçamentos demoram e viram não-venda; não sabe o que o concorrente cobra; decide no feeling.
- **Familiaridade:** WhatsApp e Instagram fluentes; computador mediano; zero terminal.
- **Tempo por sessão:** 20–30 min, horários quebrados.
- **Linguagem:** "cliente, venda, orçamento, caixa, concorrente, post" — nunca "funil de aquisição, CAC, stack".

## Nota do war game (riscos específicos do perfil)

- **Ansiedade por resultado imediato:** este perfil abandona se não vier venda rápido. Antídoto: os projetos 1–3 miram dinheiro direto (oferta, proposta, atendimento) antes dos de estrutura.
- **Síndrome do objeto brilhante:** quer pular pro n8n/automação antes do básico. Antídoto: trancar a ordem — automação (M7) só destrava com agente testado manualmente.
- **Risco de conteúdo-clichê:** agente de post que gera "conteúdo de coach". Antídoto: o agente de conteúdo é alimentado pela base do M4 (a voz e os casos DO negócio).

## Os 8 projetos práticos

| # | Projeto | Módulo | Entrada → Saída | Critério de pronto |
|---|---|---|---|---|
| 1 | **Agente de diagnóstico do negócio** (isca) | M3 | 10 respostas sobre o negócio → raio-X: onde vaza dinheiro, o que automatizar primeiro | dono reconhece ≥2 verdades incômodas |
| 2 | Agente de criação de oferta | M2–M3 | produto/serviço + público → oferta com promessa, preço-âncora e objeções respondidas | 1 oferta real publicada/testada |
| 3 | Agente de proposta comercial | M3 | briefing do cliente → proposta pronta no padrão do negócio, em minutos | 1 proposta real enviada |
| 4 | Agente de pesquisa de mercado e concorrentes | M3+M7 | nome do nicho/região → levantamento de concorrentes, preços e diferenciais | usado numa decisão de preço real |
| 5 | Agente de conteúdo para redes sociais | M4+M3 | base .md com a voz do negócio → calendário semanal + posts no tom da marca | 1 semana de posts saiu do agente |
| 6 | Agente de atendimento comercial | M4+M6 | FAQ + tabela de preços em .md → respostas de WhatsApp padronizadas que conduzem à venda | 10 dúvidas reais respondidas |
| 7 | Automação comercial simples | M7 | 1 gatilho (novo lead no formulário) → n8n notifica + registra na planilha | rodou com lead real |
| 8 | **SO de vendas com IA** (final) | M8 | entregas 1–7 → sistema montado + ritual semanal de revisão comercial | 1 semana de uso relatada |

**Ferramentas:** ChatGPT, Claude, Perplexity, Google Sheets, n8n, WhatsApp/Telegram, APIs simples.

## Adaptação dos módulos (deltas sobre o `modelo-unico.md`)

- **M1:** inventário guiado orientado a dinheiro ("quanto tempo entre o cliente pedir orçamento e você enviar?"). Exemplo-fio: o prestador que perdia 3 orçamentos por semana por demora.
- **M2:** biblioteca de 5 prompts = oferta, resposta de WhatsApp que vende, post com a voz da marca, análise de concorrente, follow-up de orçamento.
- **M4:** a base .md é a ALMA deste perfil: `/clientes` (casos e depoimentos), `/processos` (como orça, como entrega), `/referencias` (concorrentes) — é o que impede o conteúdo-clichê.
- **M6:** mini-aplicação exemplo = página "tabela de serviços + orçamento rápido" feita com Claude Code.
- **M7:** integração exemplo = formulário → n8n → WhatsApp/planilha (lead nunca mais esfria no vácuo).
- **M8:** `/08-projetos` orientado a campanhas; ritual semanal inclui revisar números de venda com o agente de análise.

## Copy do caminho (página de lançamento)

> Seu concorrente já tem um funcionário que trabalha de madrugada: responde cliente,
> escreve post, monta proposta. Custa menos que um almoço por mês. A pergunta não é
> se o seu negócio vai usar agentes — é se vai ser antes ou depois do concorrente.

**Isca do perfil:** "Raio-X do seu negócio em 15 minutos" — o Projeto 1 grátis: cola o prompt-agente, responde 10 perguntas, recebe o diagnóstico com os 3 primeiros agentes a montar.
