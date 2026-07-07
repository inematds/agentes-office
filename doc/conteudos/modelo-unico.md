# Modelo Único — a espinha dos 8 módulos (comum às 4 formações)

> Contrato de conteúdo: esta espinha é a **fonte única**. As 4 formações trocam exemplos,
> projetos e linguagem — nunca a estrutura. Formato de execução: skill `formato-curso-v5`
> (página única, aula 0 + 8 módulos = 9 aulas, promessa + tempo em toda aula, prática
> multi-modo, exemplos por profissão em 100% dos steps).

**Escada de exposição técnica:** M1–M4 só navegador · M5–M6 terminal com rota de fuga · M7 integração com camada gratuita · M8 montagem final.

---

## Aula 0 — Boas-vindas: a terceira virada (10 min)

**Promessa:** em 10 minutos você sabe exatamente o que vai montar, em quanto tempo, e por onde começar.
**Conteúdo:** a narrativa histórica (computador → internet → agentes); o mapa da formação; o contrato ("você não vai assistir, vai montar"); como pedir ajuda; o que fazer quando der erro.
**Entrega:** decisão registrada do primeiro projeto que o aluno quer ter funcionando.

---

## Módulo 1 — Entrando no mundo dos agentes (~25 min)

**Promessa:** você sai com um mapa das 5 tarefas do SEU trabalho que podem virar agentes — e sabe distinguir chat, automação e agente sem jargão.
**Metáfora-trilho:** *funcionário digital* — chat é uma conversa com um consultor; automação é uma esteira que repete; agente é um funcionário que recebe uma missão, usa ferramentas e volta com o resultado.

Steps do núcleo:
1. O que é um agente (definição de trabalho, sem tecnicismo).
2. Chat × automação × workflow × agente — quando usar cada um.
3. Por que agentes são o novo Office (o argumento histórico com casos por profissão).
4. Anatomia de uma tarefa "agentizável": entrada clara + regras conhecidas + saída verificável.
5. O inventário guiado: 10 perguntas sobre a sua semana.

**Prática (modo tarefa, 15 min):** responder o inventário guiado e marcar as 5 tarefas com maior nota (frequência × tempo gasto × chateação).
**Entrega:** mapa de oportunidades de IA no próprio trabalho (5 tarefas priorizadas).
**Erro comum:** escolher a tarefa mais IMPORTANTE em vez da mais REPETITIVA — agente bom começa no repetitivo.

---

## Módulo 2 — Prompt como comando de trabalho (~30 min)

**Promessa:** você sai com uma biblioteca de 5 prompts profissionais do seu perfil — e nunca mais escreve "me ajuda com..." numa IA.
**Metáfora-trilho:** *ordem de serviço* — ninguém entrega serviço bom com pedido vago; prompt é a ordem de serviço do funcionário digital.

Steps do núcleo:
1. Por que "frase bonita" não funciona (anatomia de um pedido vago vs uma instrução operacional).
2. Os 8 blocos: papel · objetivo · contexto · regras · entrada · saída esperada · exemplos · critérios de qualidade.
3. Template mestre com lacunas obrigatórias `[SEU CASO]`.
4. Antes/depois: a mesma tarefa com prompt vago × prompt operacional (saldo mensurável).
5. Como testar e apertar um prompt (crítica dirigida: "o que faltou pra ficar pronto?").

**Prática (modo prompt, 15 min):** transformar a tarefa nº 1 do mapa (M1) num prompt de 8 blocos e rodar.
**Entrega:** biblioteca com 5 prompts do perfil, preenchidos com casos reais.
**Erro comum:** copiar prompt pronto da internet sem preencher contexto próprio — o resultado genérico "prova" que IA não funciona.

---

## Módulo 3 — Seu primeiro agente simples (~30 min)

**Promessa:** você sai com um agente funcional em texto — que trabalha do SEU jeito e pode ser usado amanhã de manhã.
**Metáfora-trilho:** *contratação* — você vai escrever o manual de integração de um novo funcionário: quem ele é, o que faz, como você gosta que seja feito.

Steps do núcleo:
1. De prompt a agente: a diferença é a permanência (instruções que valem para SEMPRE, não para uma conversa).
2. O documento-agente: identidade + missão + regras + formato de resposta + exemplos do seu histórico.
3. Onde esse agente vive hoje (projeto no Claude / GPT personalizado / gem) — conceito antes de ferramenta, `data-versao` nos passos de UI.
4. Teste de mesa: dar 3 casos reais e avaliar com os critérios de qualidade do M2.
5. Iteração: como corrigir o agente sem recomeçar do zero.

**Prática (modo tarefa, 15 min):** montar o Projeto 1 do perfil (ver doc da formação) e rodar com 1 caso real.
**Entrega:** primeiro agente funcional em texto, testado com caso real.
**Erro comum:** agente-canivete ("faz tudo") — agente bom tem UMA missão.

---

## Módulo 4 — Segundo cérebro em Markdown (~30 min)

**Promessa:** você sai com a sua base de conhecimento profissional organizada em arquivos de texto — o combustível que torna seus agentes 10× melhores.
**Metáfora-trilho:** *fichário* — Markdown é um fichário de papel: pastas são divisórias, arquivos são fichas, títulos são abas coloridas. Nada de código.

Steps do núcleo:
1. Por que agente sem contexto é estagiário no 1º dia (e com a sua base é sócio de 10 anos).
2. Markdown em 6 símbolos (`#`, `##`, `-`, `**`, `[]()`, tabela) — texto com títulos, não programação.
3. A estrutura mínima: `/contexto` `/projetos` `/clientes` `/processos` `/prompts` `/agentes` `/referencias` `/decisoes`.
4. O que entra e o que NUNCA entra (bloco fixo: dados sensíveis, sigilo profissional, LGPD).
5. Alimentando o agente com a base: colar contexto vs anexar arquivo.

**Prática (modo tarefa, 15 min):** criar a estrutura e escrever o primeiro arquivo `/contexto/meu-trabalho.md` (5 linhas verdadeiras).
**Entrega:** base pessoal de conhecimento iniciada com ≥3 arquivos reais.
**Erro comum:** organizar pastas por 2 horas e não escrever conteúdo — a base vale pelo que tem dentro.

---

## Módulo 5 — Terminal e ambiente de trabalho com IA (~40 min) ⚠️ travessia

**Promessa:** você sai com seu primeiro projeto organizado no computador e perde o medo da tela preta — digitando só 6 comandos.
**Metáfora-trilho:** *balcão da cozinha* — o terminal é falar direto com o cozinheiro em vez de pedir pelo cardápio. Mais rápido, mais poder, mesmas panelas.

Steps do núcleo:
1. Aula-escudo "o erro é o normal": antes de qualquer comando, aprender a copiar o erro e colar na IA pedindo socorro.
2. Os 6 comandos que bastam (`pwd`, `ls`, `cd`, `mkdir`, abrir editor, e pedir o resto pra IA).
3. Pastas e arquivos do M4 agora no computador (a base sai do papel).
4. Git básico como "salvar versão" (conceito de pontos de restauração — sem decorar comando: a IA escreve, você entende).
5. Como conversar com a IA DENTRO de um projeto (contexto de pasta).

**Rota de fuga oficial:** quem travar na instalação segue pela versão navegador (claude.ai/code) — mesmo resultado, zero instalação. Card visível, sem tom de "plano B para fracos".
**Prática (modo tarefa, 15 min):** criar a pasta do projeto, mover a base do M4 pra dentro, salvar a 1ª versão.
**Entrega:** primeiro projeto organizado no computador (ou no navegador), versionado.
**Erro comum:** tentar decorar comandos — o objetivo é entender o que se está pedindo, quem decora é a IA.

---

## Módulo 6 — Claude Code, Codex e agentes de desenvolvimento (~40 min)

**Promessa:** você sai com uma mini-aplicação ou automação construída pela IA sob a SUA direção — sem escrever uma linha de código.
**Metáfora-trilho:** *mestre de obras* — você não assenta tijolo; você tem a planta, dá a ordem, confere a parede. O Claude Code é a equipe de obra.

Steps do núcleo:
1. O que é um agente de desenvolvimento (a IA que mexe nos SEUS arquivos com a SUA permissão).
2. Abrir o projeto do M5 e o primeiro pedido bem-feito (contexto + objetivo + critério de pronto).
3. README e arquivo de instruções: o "manual da obra" que evita a IA se perder.
4. O ciclo pedir → conferir → ajustar (nunca aceitar sem testar; teste de mesa com caso real).
5. Quando a IA se perde: como recuperar (recomeçar a conversa, reduzir o pedido, dar exemplo).

**Prática (modo tarefa, 15 min):** pedir ao Claude Code uma página/automação simples do perfil (ex.: página de FAQ do consultório; planilha-relatório do time) e conferir com critério de pronto.
**Entrega:** mini-aplicação, página ou automação textual funcional.
**Erro comum:** pedido-romance de 20 linhas — pedido bom tem objetivo, insumo e critério de pronto em 5 linhas.

---

## Módulo 7 — APIs, MCP e ferramentas (~40 min)

**Promessa:** você sai com um agente conectado a uma ferramenta externa real — e entende API, webhook e MCP em linguagem de gente.
**Metáfora-trilho:** *tomadas* — API é a tomada padrão de um serviço; webhook é a campainha que toca sozinha quando algo acontece; MCP é o adaptador universal que deixa a IA usar qualquer tomada.

Steps do núcleo:
1. Por que agente sem ferramenta é consultor trancado numa sala (sabe tudo, não alcança nada).
2. API em 1 diagrama de mecanismo (pedido → serviço → resposta) — com exemplo do perfil.
3. Webhook e gatilhos: quando o mundo avisa o agente.
4. MCP: a IA usando ferramentas sozinha, com as suas permissões.
5. Custo e segurança: quanto custa cada chamada (estimativa ANTES do exercício), o que nunca conectar, camadas gratuitas.

**Prática (modo tarefa, 15 min):** conectar o agente a UMA ferramenta externa simples (ex.: n8n com template pronto, ou MCP no Claude) usando camada gratuita — sem cartão.
**Entrega:** primeiro agente conectado a uma ferramenta externa, com custo conhecido.
**Erro comum:** conectar tudo de uma vez — uma integração funcionando vale mais que cinco pela metade.

---

## Módulo 8 — Sistema Operacional de IA (~40 min)

**Promessa:** você sai com seu Sistema Operacional de IA montado com material 100% real — e um ritual de 20 min por semana pra ele nunca morrer.
**Metáfora-trilho:** *sede da empresa* — até aqui você contratou funcionários (agentes) e montou arquivos (base). Agora eles ganham uma sede, com organograma, regras e memória.

Steps do núcleo:
1. A estrutura: `/01-identidade` `/02-contexto` `/03-regras` `/04-agentes` `/05-prompts` `/06-ferramentas` `/07-processos` `/08-projetos` `/09-memoria` `/10-auditoria`.
2. **Montagem, não criação:** cada pasta recebe uma entrega dos módulos 1–7 (mapa→02, biblioteca→05, agentes→04, base→02/08, integrações→06). Critério de pronto: ≥1 arquivo REAL por pasta-chave.
3. Regras e limites: o `/03-regras` com o bloco "o que nunca colocar na IA".
4. Memória e auditoria: registrar decisões e revisar o que o sistema errou.
5. O ritual semanal de 20 min (revisar memória, atualizar projetos, apertar 1 prompt).

**Prática (modo tarefa, 15 min):** montar as 10 pastas e distribuir as entregas dos módulos anteriores.
**Entrega:** Sistema Operacional de IA do perfil, funcionando com material real + ritual semanal agendado.
**Erro comum:** SO-vitrine (estrutura linda, pastas vazias) — pasta sem arquivo real não conta como pronta.

---

## Regras transversais (valem para os 8 módulos, nas 4 formações)

1. Toda aula: promessa verificável + tempo declarado (`data-tempo`).
2. Todo step: exemplo com profissão real do perfil (≥2 profissões nomeadas por formação).
3. Todo termo técnico: metáfora do mundo real ANTES da definição.
4. Toda prática: 5–15 min, com material do próprio aluno, critério de pronto explícito e nota de segurança (`.psafe`) sobre dados sensíveis.
5. Todo bloco de ferramenta: marcado `data-kind="ferramenta"` + `data-versao` (o conceito é eterno, o print não).
6. Fim de aula: microação de ≤15 min + gancho para a próxima.
