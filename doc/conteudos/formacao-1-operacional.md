# Formação 1 — Profissional Operacional com IA

**Promessa:** entregue em 2 horas o que hoje leva o dia — sem virar programador.
**Pergunta de identificação (funil):** "Você passa o dia executando processos, e-mails e planilhas?"
**Resultado final:** um mini Sistema Operacional de produtividade com IA para o trabalho diário.

## Persona

- **Quem:** administrativo, financeiro, atendimento, suporte, RH, comercial interno, assistentes, analistas.
- **Profissões-alvo nomeadas (contrato v5, exemplos em 100% dos steps):** **analista administrativo** e **assistente de RH** (secundárias: atendente de suporte, analista financeiro).
- **Dores:** dia engolido por e-mail, planilha e retrabalho; cobrança por volume; medo de ser trocado por quem "sabe IA"; não decide a própria ferramenta (empresa manda).
- **Familiaridade:** usa bem Office/Google, zero terminal.
- **Tempo por sessão:** 20–30 min (hora do almoço / fim do expediente).
- **Linguagem:** falar de "tarefa, prazo, chefe, planilha, caixa de entrada" — nunca "stack, deploy, endpoint".

## Nota do war game (riscos específicos do perfil)

- **Comprador ≠ usuário:** vende-se ao indivíduo (crescimento de carreira), não à empresa. O ângulo é "torne-se a pessoa mais produtiva do setor".
- **Dados da empresa:** este perfil manuseia dados que NÃO são dele. O bloco "o que nunca colocar na IA" é ainda mais rígido: nada de dados de clientes/folha sem anonimizar; práticas com dados fictícios fornecidos pelo curso.
- **Autoestima técnica baixa:** é o perfil que mais precisa da escada de vitórias — nenhum atalho na ordem dos módulos.

## Os 8 projetos práticos

| # | Projeto | Módulo | Entrada → Saída | Critério de pronto |
|---|---|---|---|---|
| 1 | **Agente pessoal de produtividade** (isca) | M3 | despejo de demandas da semana → lista organizada por urgência/importância + próximos passos + riscos | organizou a semana real de amanhã |
| 2 | Agente de resumo (reuniões, mensagens, documentos) | M3–M4 | ata/print/PDF → resumo com decisões, pendências e responsáveis | resumiu 1 reunião real em ≤2 min |
| 3 | Agente de e-mail (criar e revisar) | M2–M3 | rascunho ou contexto → e-mail no tom certo (formal/cordial/cobrança) | 3 e-mails reais enviados |
| 4 | Agente organizador de tarefas e prioridades | M3 | lista bagunçada → quadro urgente/importante com prazos sugeridos | usado por 3 dias seguidos |
| 5 | Agente de atendimento interno (FAQ do setor) | M4+M6 | base .md com perguntas do setor → respostas padronizadas com fonte | responde as 10 dúvidas mais comuns do setor |
| 6 | Mini workflow para processo repetitivo | M7 | 1 processo mapeado (ex.: consolidar planilha semanal) → fluxo no n8n básico com template | rodou 1× sem intervenção |
| 7 | Base pessoal de conhecimento em Markdown | M4–M5 | processos, modelos e contatos do trabalho → base organizada e versionada | ≥8 arquivos reais |
| 8 | **SO simples de trabalho com IA** (final) | M8 | entregas 1–7 → sistema montado nas 10 pastas + ritual semanal | 1 semana de uso relatada |

**Ferramentas:** ChatGPT, Claude, Gemini, Perplexity, Notion/Obsidian, Google Docs/Sheets, n8n básico, prompts estruturados.

## Adaptação dos módulos (deltas sobre o `modelo-unico.md`)

- **M1:** inventário guiado com verbos do perfil ("quantas vezes por semana você copia dados de um lugar pra outro?"). Exemplo-fio: a assistente de RH que gastava 3h/semana consolidando ponto.
- **M2:** biblioteca de 5 prompts = e-mail de cobrança gentil, resumo de reunião, resposta padrão a solicitação, relatório de status, checklist de processo.
- **M5–M6:** ênfase na rota navegador-primeiro (muitos usam PC corporativo travado — **risco do perfil: sem permissão de admin para instalar**; a rota navegador é a principal aqui, não a de fuga).
- **M7:** integração exemplo = planilha Google + n8n template pronto (consolidação semanal automática).
- **M8:** SO com pastas orientadas a rotina: `/07-processos` é a estrela (cada processo do setor vira um arquivo com o agente que o executa).

## Copy do caminho (página de lançamento)

> Você não precisa aprender a programar. Precisa parar de fazer na mão o que um agente
> faz em minutos. Nos anos 90, quem sabia Excel virou referência do setor. Agora, quem
> opera agentes vai ser a pessoa que o setor não consegue perder.

**Isca do perfil:** "Organize sua semana em 15 minutos" — o Projeto 1 grátis: cola o prompt-agente, despeja as demandas, recebe a semana organizada.
