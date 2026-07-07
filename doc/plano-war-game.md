# War Game — Formação "Agentes: o Novo Office da Era da IA" (INEMA.CLUB)

> Planejamento completo da formação-mãe com 4 caminhos por perfil, feito como **war game**:
> não assumimos o caminho feliz. O inimigo principal deste projeto **não é técnico — é a
> resistência das pessoas**. Cada fase tem suposição otimista, suposição pessimista, modos
> de falha com correção, critérios de saída verificáveis e orçamento de tentativas.

**Data:** 2026-07-07 · **Status:** aguardando aprovação do Nei · **Repo de execução:** a definir (sugestão: `~/projetos/agentes-office`)

---

## Preâmbulo (para um agente começando do zero)

O INEMA.CLUB vai lançar uma **formação-mãe** chamada **"Agentes: o Novo Office da Era da IA"**
com **4 caminhos por perfil**:

1. **Operacional com IA** — administrativo, financeiro, atendimento, RH, analistas.
2. **Empreendedor com IA** — donos de negócio, MEIs, prestadores de serviço, infoprodutores.
3. **Profissional Liberal com IA** — médicos, advogados, contadores, arquitetos, consultores.
4. **Gestor e Líder com IA** — gestores, coordenadores, diretores, líderes de equipe.

Todos os caminhos compartilham a **mesma espinha de 8 módulos** (ver `conteudos/modelo-unico.md`);
o que muda são **exemplos, projetos e linguagem** — 100% do perfil. A tese de venda é histórica:
*anos 90 = aprender computador; anos 2000 = aprender internet; agora = aprender agentes de IA.*

O aluno não entra para assistir aula. Ele entra para **montar o próprio ambiente de trabalho
com agentes** e sair com um "sistema operacional de IA" funcionando com material real dele.

**Formato de execução dos cursos:** skill `formato-curso-v5` (página única, dark editorial,
promessa + tempo em toda aula, prática multi-modo sem terminal nos módulos iniciais, exemplos
por profissão obrigatórios em 100% dos steps). Publicação: GitHub Pages + card no portal
(inema.club), via git push — nunca Vercel direto.

**Restrição central (o inimigo):** o público-alvo tem **resistência e limitação** —
"não sou técnico", "não tenho tempo", "já tentei ChatGPT e não mudou nada", "isso é pra
programador", "tenho medo de parecer burro". O conteúdo sozinho não vence isso.
**Atração é parte do produto**, não do marketing (ver `estrategia-atracao.md`).

---

## Caminho crítico

```
Fase 0 ──► Fase 1 ──► Fase 2 ──► Fase 3 ──► Fase 4 ──► Fase 5
decisões   isca +      núcleo     travessia   projeto     lançamento
de formato página de   comum      técnica     final por   + loop de
e escopo   lançamento  (M1–M4)    (M5–M7)     perfil (M8) melhoria
```

A ordem importa: a **isca (Fase 1) vem antes do curso completo** — valida a promessa e a
linguagem com gente real antes de investir nos 8 módulos × 4 perfis. A **travessia técnica
(Fase 3)** é o ponto de maior risco de abandono e recebe o maior orçamento de correção.

---

## Fase 0 — Fundação e decisões de formato

**Objetivo:** fechar as decisões estruturais antes de produzir qualquer conteúdo:
1 curso com 4 variantes vs 4 cursos; plataforma; nome; preço-âncora; repo e URL.

**Suposição otimista:** a estrutura "formação-mãe + 4 caminhos" do brief funciona como está;
o formato v5 cobre tudo; decide-se em 1 sessão.

**Suposição pessimista:** "1 curso com 4 verniz de perfil" se revela genérico demais na
prática — os projetos do médico e do dono de loja não cabem na mesma página; ou o v5
(máx. 9 aulas por trilha) não comporta 8 módulos × conteúdo por perfil.

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| Conteúdo genérico com verniz de perfil | Leitura-teste: um advogado não se reconhece nos exemplos | Estrutura **4 páginas separadas** (1 por perfil) que compartilham a espinha, nunca 1 página com abas de perfil. O v5 já exige exemplo por profissão em 100% dos steps — usar as ≥2 profissões-alvo de cada formação |
| 8 módulos não cabem no teto v5 (9 aulas/trilha) | Contagem na maquete | 8 módulos = 8 aulas + 1 aula-0 de boas-vindas = exatamente 9; ou dividir em 2 trilhas (base comum / aplicação) |
| Nome não comunica pra leigo | Teste de 5 segundos com 3 pessoas do público | Manter "Agentes: o Novo Office da Era da IA" como marca-mãe e nomear cada caminho pela DOR, não pela tecnologia |
| Escopo explode (4 cursos completos de uma vez) | Cronograma > 4 semanas | Lançar **1 perfil primeiro** (recomendo Profissional Liberal — maior disposição a pagar e dor mais clara), os outros 3 em ondas |

**Critérios de saída (verificáveis):**
- [ ] Decisão registrada: 4 páginas-irmãs com espinha comum, publicadas em ondas.
- [ ] Ordem de lançamento dos perfis definida e justificada.
- [ ] Nome, URL do repo e preço-âncora fechados.
- [ ] `modelo-unico.md` aprovado como contrato de conteúdo.

**Orçamento:** 1–2 sessões de decisão. Se passar disso, decidir pelos defaults recomendados acima e seguir.

---

## Fase 1 — A isca: prova de 15 minutos + página de lançamento

**Objetivo:** construir a **porta de entrada anti-resistência**: uma página de lançamento
que vende pela dor do perfil (não pela tecnologia) e uma **aula aberta de 15 minutos** em
que a pessoa constrói o primeiro agente em texto e sente a vitória ANTES de pagar.

**Suposição otimista:** a comparação histórica (Office → Internet → Agentes) conecta
sozinha; a página converte visitante frio.

**Suposição pessimista:** tráfego frio não sabe o que é "agente" e a palavra assusta
("isso é programação"); a página bonita não converte porque fala de ferramentas
(Claude, MCP, terminal) em vez de resultados (parecer pronto em 20 min).

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| Visitante não se reconhece ("isso não é pra mim") | Alta rejeição na página; ninguém clica nos caminhos | Seletor de perfil no topo: 4 cards pela PROFISSÃO/dor ("Você passa o dia executando processos?"), não pelo nome do curso |
| Palavra "agente" lida como técnica | Feedback direto; perguntas "precisa saber programar?" | Definir agente em 1 frase de trabalho ("um funcionário digital que executa uma tarefa sua, do seu jeito") logo no hero; jargão só depois da 1ª vitória |
| Aula-isca sem vitória real | Pessoa termina os 15 min sem nada usável | A isca entrega o **Projeto 1 do perfil** (agente de produtividade/diagnóstico) pronto para colar no ChatGPT/Claude — sai com algo funcionando no próprio trabalho hoje |
| Promessa inflada gera desconfiança | Comentários céticos, reembolso alto depois | Promessas verificáveis estilo v5 ("você sai com X funcionando em Y min"), nunca "domine a IA" |

**Critérios de saída:**
- [ ] `lancamento/index.html` publicada (self-contained, dark âmbar INEMA, responsiva).
- [ ] Página passa o teste dos 5 segundos: pessoa do público diz em 1 frase o que ganha.
- [ ] Aula-isca de 15 min escrita e testada com ≥1 pessoa real de ≥2 perfis: ambas terminam com um agente colado e rodando.
- [ ] CTA da página leva à isca, não direto ao checkout.

**Orçamento:** 3 tentativas de copy do hero. Se a 3ª não passar no teste de 5 segundos, trocar o ângulo (de história → dor direta do perfil).

---

## Fase 2 — Núcleo comum: Módulos 1–4 (sem terminal)

**Objetivo:** produzir os 4 primeiros módulos (mundo dos agentes; prompt como comando de
trabalho; primeiro agente simples; segundo cérebro em Markdown) — tudo **sem terminal**,
só navegador e editor de texto, para o aluno acumular 4 vitórias antes de qualquer tela preta.

**Suposição otimista:** o público avança sozinho; prompts estruturados bastam para os
projetos 1–4 de cada perfil.

**Suposição pessimista:** mesmo sem terminal há abandono — Markdown assusta ("código!"),
o aluno não sabe o que perguntar à IA, e a "biblioteca de prompts" vira exercício teórico
que ninguém aplica no trabalho.

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| Markdown lido como programação | Dúvidas/travadas no M4 | Apresentar Markdown como "texto com títulos" via metáfora do fichário; primeira prática é escrever 5 linhas sobre o próprio trabalho, não sintaxe |
| Aluno sem matéria-prima ("não sei o que automatizar") | M1 sem entrega do mapa de oportunidades | M1 traz o **inventário guiado**: 10 perguntas sobre a semana da pessoa que geram o mapa automaticamente |
| Prompts genéricos copiados sem adaptação | Entregas iguais entre alunos | Toda prática exige preencher com caso real do aluno; prompt-template tem lacunas obrigatórias `[SEU CASO]` |
| Ritmo: aluno some entre módulos | Progresso estagna no painel | Microação de ≤15 min ao fim de cada aula + gancho (contrato v5 `.next-action`) |

**Critérios de saída:**
- [ ] M1–M4 publicados no formato v5 para o 1º perfil da onda, com promessa+tempo em cada aula.
- [ ] 100% dos steps com exemplo da profissão-alvo (auditável pelo contrato v5).
- [ ] Teste com aluno-piloto: completa M1–M4 e mostra os 4 entregáveis (mapa, biblioteca, agente, base .md).
- [ ] Zero menção a terminal/Git até o fim do M4.

**Orçamento:** 1 rodada de revisão por módulo com a skill `revisar-curso` + 1 correção pós-piloto.

---

## Fase 3 — A travessia técnica: Módulos 5–7 (terminal, Claude Code, APIs/MCP)

**Objetivo:** atravessar o ponto de maior risco do produto: levar um leigo do navegador
para terminal + Claude Code/Codex + primeira integração, **sem perder o aluno**.

**Suposição otimista:** com 4 vitórias acumuladas, o aluno confia no método e aceita a
tela preta; instalação é tranquila.

**Suposição pessimista (a mais provável de todas):** **aqui mora o churn.** Instalação
falha (Windows sem WSL, Mac antigo, permissões), o primeiro erro vermelho no terminal
dispara o "eu sabia que não era pra mim", custos de API assustam, e a diferença
Windows/Mac/Linux triplica o suporte.

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| Instalação quebra no 1º passo | Aluno para no M5 sem abrir o terminal | **Plano B pronto:** caminho navegador-primeiro (Claude Code na web / claude.ai/code) como rota oficial para quem travar; instalação local vira opcional |
| Primeiro erro = pânico | Mensagens "deu erro, desisti" | Aula "o erro é o normal": ensinar a colar o erro na IA e pedir ajuda ANTES de qualquer comando; erro vira exercício, não acidente |
| Custo de API surpreende | Reclamações de cobrança | M7 usa camadas gratuitas e mostra o custo estimado ANTES de cada exercício; alternativa sem cartão para todo exercício |
| Windows vs Mac vs Linux | Suporte explode | Guias por sistema só onde divergem; todo o resto em caminho único; testar os 3 antes de publicar |
| Jargão de plataforma (MCP, webhook, endpoint) | Aluno relê e não entende | Contrato 40+ do v5: metáfora do mundo real antes de todo termo (MCP = "tomada padrão onde qualquer ferramenta se pluga") |

**Critérios de saída:**
- [ ] M5–M7 publicados; cada exercício técnico tem rota principal + plano B navegador.
- [ ] Piloto leigo real: sai do M6 com uma mini-aplicação feita via Claude Code sem intervenção humana além do material.
- [ ] Tabela de custos de API por exercício revisada e exposta ao aluno.
- [ ] Toda mensagem de erro provável dos exercícios tem card "se aparecer isso, faça isso".

**Orçamento:** 2 pilotos leigos. Se ambos travarem no mesmo ponto, o ponto é redesenhado (não "melhor explicado").

---

## Fase 4 — Sistema Operacional de IA: Módulo 8 + projeto final por perfil

**Objetivo:** fechar o ciclo — o aluno monta o SO de IA (`/01-identidade` … `/10-auditoria`)
com material real do trabalho dele e conclui o projeto final do perfil (SO de produtividade /
vendas / consultório / gestão).

**Suposição otimista:** com 7 módulos, montar o SO é só juntar as peças.

**Suposição pessimista:** o SO vira pasta morta — bonito no dia da entrega, abandonado em
2 semanas; ou o aluno copia a estrutura sem conteúdo próprio.

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| SO montado vazio (estrutura sem conteúdo real) | Pastas com placeholders na entrega | Critério de pronto exige ≥1 arquivo real por pasta-chave, vindos das entregas dos M1–M7 (o SO é a MONTAGEM do que já existe, não algo novo) |
| Abandono pós-curso | Sem uso após 2 semanas | M8 termina com "ritual semanal de 20 min" (revisar /09-memoria, atualizar /08-projetos) + convite para comunidade/coorte |
| Projeto final grande demais | Alunos não concluem | Projeto final = integrar os 8 projetos já feitos, não construir um 9º |

**Critérios de saída:**
- [ ] M8 publicado; piloto entrega SO com material real e o usa por 1 semana (auto-relato).
- [ ] Página do curso completa (aula 0 + 8 módulos) auditada com `revisar-curso`.
- [ ] Card publicado no portal via skill `atualiza-portal`.

**Orçamento:** 1 iteração de simplificação do projeto final se a taxa de conclusão do piloto for < 100%.

---

## Fase 5 — Lançamento em ondas + loop de melhoria

**Objetivo:** lançar o 1º perfil, medir, corrigir, e replicar para os outros 3 perfis em
ondas — cada onda mais barata que a anterior porque a espinha comum já existe.

**Suposição otimista:** replicar um perfil = trocar exemplos e projetos em 20% do conteúdo.

**Suposição pessimista:** cada perfil exige 60%+ de reescrita (o gestor não quer "criar
oferta", o médico tem LGPD/sigilo, o operacional não decide a própria compra); e o loop de
melhoria nunca roda porque não há métrica coletada.

**Modos de falha prováveis:**

| Falha | Detecção | Correção |
|---|---|---|
| Perfil 2+ sai clone do 1º | Auditoria anti-clone do v5 acusa similaridade | Regenerar variando exemplos/ordem; projetos do perfil escritos ANTES de adaptar as aulas |
| Questões regulatórias do perfil liberal (sigilo médico, OAB, LGPD) | Feedback jurídico/ético | Módulo do perfil liberal ganha bloco fixo "o que nunca colocar na IA" + práticas com dados fictícios |
| Sem métricas → sem loop | Nenhum dado após 30 dias | Definir 4 números mínimos ANTES do lançamento: conclusão da isca, conversão isca→compra, % que passa do M5 (a travessia), entregas do M8 |
| Comprador ≠ usuário no perfil operacional | Vendas B2B travadas | Oferta individual primeiro; pacote-empresa como fase posterior, fora deste escopo |

**Critérios de saída:**
- [ ] Perfil 1 no ar com as 4 métricas coletando.
- [ ] Retro após 30 dias: decisão explícita de ajustar vs replicar.
- [ ] Perfis 2–4 publicados em ondas, cada um passando a auditoria anti-clone.

**Orçamento:** replicação de perfil ≤ 1/3 do esforço do perfil 1; se passar, a espinha comum está errada — voltar à Fase 0 e re-decidir a estrutura.

---

## Tabela mestre de cenários de falha

| # | Categoria | Cenário | Detecção | Recuperação |
|---|---|---|---|---|
| 1 | Resistência | "Não sou técnico, isso não é pra mim" | Rejeição na página; não clica em nenhum caminho | Copy pela dor do trabalho, nunca pela ferramenta; seletor de perfil no hero; prova de 15 min antes de pagar |
| 2 | Resistência | Medo de parecer burro (não pergunta, some) | Aluno para sem pedir ajuda | Normalizar o erro como parte do método (aula "o erro é o normal"); canal de dúvida anônima |
| 3 | Resistência | "Já tentei ChatGPT e não mudou nada" | Objeção recorrente em comentários | Posicionar contra o "uso de perguntinha": a formação monta SISTEMA, não conversa; mostrar antes/depois concreto por perfil |
| 4 | Resistência | Medo de ser substituído pela IA | Tom defensivo nas interações | Narrativa "quem opera agentes substitui quem não opera"; projetos que aumentam a pessoa, não a apagam |
| 5 | Resistência | Falta de tempo ("não tenho 3 meses") | Não inicia após comprar | Contrato v5: toda aula com tempo declarado; microações de ≤15 min; trilha mínima viável destacada |
| 6 | Churn técnico | Instalação do terminal/Claude Code falha | Parada em massa no M5 | Rota navegador-primeiro oficial; guia por SO; suporte com prints dos erros comuns |
| 7 | Churn técnico | Primeiro erro vermelho no terminal | "Deu erro" e abandono | Ensinar colar-erro-na-IA antes do 1º comando; cards "se aparecer isso" |
| 8 | Churn técnico | Custos de API inesperados | Reclamação de cobrança | Camada gratuita por padrão; custo estimado antes de cada exercício; alternativa sem cartão |
| 9 | Conteúdo | Genérico com verniz de perfil | Auditoria anti-clone; leitura-teste do perfil | 4 páginas separadas; exemplos por profissão em 100% dos steps (contrato v5) |
| 10 | Conteúdo | Jargão de plataforma sem rampa | Dúvidas de vocabulário | Metáfora do mundo real antes de todo termo técnico (contrato 40+) |
| 11 | Conteúdo | Ferramentas mudam (UI do Claude, preços, n8n) | Prints divergem do real | Aulas ancoradas em conceito + `data-versao` nos blocos-ferramenta; revisão trimestral agendada |
| 12 | Negócio | Promessa inflada → reembolso | Taxa de reembolso alta | Promessas verificáveis por aula; isca honesta que filtra quem não é o público |
| 13 | Negócio | 4 formações = 4× manutenção eterna | Correções quadruplicadas | Espinha comum como fonte única; mudanças estruturais na espinha, só exemplos nas variantes |
| 14 | Negócio | Preço errado pro perfil (operacional ganha menos que liberal) | Conversão díspar entre perfis | Preço por onda/perfil pode divergir; decidir na Fase 5 com dado, não antes |
| 15 | Legal/ético | Aluno cola dados sensíveis (paciente, cliente, processo) na IA | Relato em comunidade | Bloco fixo "o que nunca colocar na IA" em TODOS os perfis; práticas com dados fictícios; LGPD como conteúdo, não rodapé |
| 16 | Atração | Tráfego frio não entende "agente" | CTR baixo em anúncio/Reels | Conteúdo de topo pela dor e pela história (Office→Internet→Agentes); a palavra "agente" só se define com exemplo vivo |
| 17 | Atração | Página converte visita mas isca não converte compra | Funil quebra no meio | A isca deve terminar com vitória + próximo passo explícito; se vitória acontece e não converte, o problema é oferta/preço, não conteúdo |
| 18 | Loop | Nenhuma métrica coletada → melhoria por achismo | 30 dias sem dado | 4 métricas mínimas definidas antes do lançamento (Fase 5); retro mensal no calendário |

---

## Loop de melhoria contínua (mensal)

1. **Coleta:** 4 métricas do funil (conclusão da isca; conversão isca→compra; % que atravessa o M5; entregas do M8) + dúvidas recorrentes dos alunos.
2. **Diagnóstico:** onde o funil quebra? A quebra é de atração (antes de pagar), de travessia (M5–M7) ou de conclusão (M8)?
3. **Correção com trava:** nenhuma mudança estrutural entra sem passar pela auditoria `revisar-curso` e sem aprovação explícita do Nei. Exemplos e cards de erro podem entrar direto.
4. **Registro:** decisões e números no `/09-memoria` do próprio projeto (dogfooding do SO de IA).

---

## Estrutura de arquivos do projeto (na execução)

```
agentes-office/
├── index.html                  # página de lançamento (Fase 1)
├── isca/index.html             # aula aberta de 15 min
├── operacional/index.html      # formação perfil 1 (formato v5)
├── empreendedor/index.html
├── liberal/index.html
├── gestor/index.html
└── doc/                        # este plano + métricas + retros
```

## Metodologia

- **Conteúdo:** skill `formato-curso-v5` (contrato 40+ integral); auditoria com `revisar-curso`; anti-clone entre perfis.
- **Atração:** `estrategia-atracao.md` deste plano; Reels via skill `roteirista-inema`; vídeos do curso via `videos-cursos-inema` (fase posterior).
- **Publicação:** git push (GitHub Pages) + `atualiza-portal`. Deploy não é responsabilidade deste plano.
- **Regra de ouro do war game:** alto esforço no plano, baixo/médio na execução; parar a cada fase, validar critérios de saída, só então avançar.
