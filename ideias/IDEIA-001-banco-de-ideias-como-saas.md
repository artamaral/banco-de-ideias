# IDEIA-001 — Transformar o Banco de Ideias em SaaS

## Metadados

- **Estado:** Capturada
- **Origem:** Conversa no ChatGPT
- **Data de captura:** 11/07/2026
- **Tipo inicial:** Possível novo produto
- **Issue relacionada:** [#1](https://github.com/artamaral/banco-de-ideias/issues/1)
- **Decisão atual:** Manter em incubação e aprofundar antes de transformar em projeto

## Ideia original

Transformar o próprio **Banco de Ideias** em um SaaS.

O produto permitiria capturar ideias por voz ou texto no celular, preservá-las ainda incompletas e desenvolvê-las ao longo do tempo com apoio de IA. A finalidade não é transformar toda ideia imediatamente em tarefa ou projeto, mas ajudar o usuário a decidir se ela deve continuar em análise, permanecer incubada, ser arquivada, integrar um projeto existente ou originar um novo projeto.

## Problema percebido

Ideias surgem em momentos diferentes e acabam espalhadas entre conversas, notas e áudios. As ferramentas tradicionais geralmente apenas armazenam notas, organizam tarefas, promovem brainstorming ou exigem que a ideia já esteja desenvolvida para ser validada como negócio.

Falta uma experiência simples para a etapa anterior: quando a ideia ainda é vaga, precisa ser retomada várias vezes e não deve ser tratada como compromisso de execução.

## Usuário inicial imaginado

Pessoa que tem muitas ideias profissionais ou pessoais, usa principalmente o celular e quer capturá-las sem fricção, conversando com uma IA para desenvolvê-las gradualmente.

## Proposta de valor preliminar

> Um lugar para falar ou escrever uma ideia e deixá-la amadurecer com a ajuda da IA até ser possível decidir se ela merece virar projeto.

## Fluxo mais simples possível

1. O usuário fala ou escreve uma ideia.
2. O sistema cria o registro automaticamente.
3. A ideia mantém conversa e histórico próprios.
4. A IA faz perguntas e análises progressivas.
5. O estado da ideia é atualizado.
6. Quando houver maturidade, a ideia pode ser associada a um projeto existente ou originar um novo projeto.

## Estados iniciais sugeridos

- Capturada
- Em análise
- Incubada
- Incorporada a projeto
- Convertida em novo projeto
- Arquivada

## Funções essenciais do MVP

- Captura por voz ou texto pelo celular.
- Lista única de ideias.
- Histórico de evolução de cada ideia.
- Conversa com IA no contexto da ideia.
- Perguntas progressivas para amadurecimento.
- Identificação de ideias relacionadas ou duplicadas.
- Estado explícito da ideia.
- Ação principal: **Analisar esta ideia**.
- Associação futura com projetos existentes.

## Fora do MVP

- Gestão completa de projetos.
- Kanban configurável.
- Colaboração empresarial.
- Votação, campanhas e gamificação.
- Planejamento financeiro completo.
- Dashboards corporativos.
- Automação complexa.
- Transformação automática de toda ideia em tarefa.

## Concorrentes e alternativas

| Produto | Funções principais | Diferença para nossa proposta |
|---|---|---|
| [Ideanote](https://ideanote.io/feature) | Coleta corporativa, colaboração, scoring, Kanban, automações e métricas | Plataforma ampla de inovação para equipes; muito mais complexa |
| [IdeaBuddy](https://ideabuddy.com/features/idea-validation/) | Canvas, desenvolvimento de negócio, planejamento e validação | Pressupõe que a ideia já esteja caminhando para virar negócio |
| [Voicenotes](https://voicenotes.com/) | Voz, transcrição, resumo e consulta por IA | Resolve captura e memória, não um processo específico de maturação e decisão |
| [TalkNotes](https://talknotes.io/) | Converte áudio em textos estruturados, listas e roteiros | Prioriza transformação do áudio, não acompanhamento da ideia |
| [Ideamap](https://ideamap.ai/) | Brainstorming visual, geração, análise e duplicidades | Orientado a sessões visuais de brainstorming |
| [MyMap](https://www.mymap.ai/) | Mapas mentais, fluxos e ideias conectadas | Prioriza visualização em canvas |
| [DimeADozen](https://www.dimeadozen.ai/) | Validação de startup, mercado e concorrência | Atua depois que a ideia já foi formulada como negócio |

## Hipótese de diferenciação

Os concorrentes concentram-se em anotar, fazer brainstorming, administrar inovação, planejar negócios ou validar startups. O espaço a explorar está entre **anotar** e **decidir transformar em projeto**.

A vantagem pretendida não é ter mais funções, mas reduzir o caminho:

> “Tive uma ideia” → “Entendi se vale continuar pensando nela”.

## Princípios do projeto aplicados

- Mobile-first.
- Captura imediata por voz ou texto.
- ChatGPT/IA como parte central da experiência.
- Simplicidade antes de automação.
- Ideias podem permanecer incompletas por tempo indeterminado.
- Uma ideia não vira tarefa ou projeto automaticamente.
- Usar ferramentas gratuitas ou já conhecidas na validação inicial.
- Evolução incremental, sem infraestrutura complexa antes de comprovar o uso.

## Questões para amadurecimento

- O produto será pessoal, para equipes ou ambos?
- Qual será a diferença prática entre uma conversa comum no ChatGPT e uma ideia persistente?
- Como fazer uma ideia reaparecer no momento certo sem incomodar?
- Quais sinais indicam que uma ideia amadureceu?
- A IA recomenda mudanças de estado ou pode executá-las?
- Como relacionar ideias a projetos existentes?
- O usuário pagaria pela organização, análise, memória de longo prazo ou validação?
- O que deve ser testado manualmente no ChatGPT antes da construção?

## Próxima análise recomendada

Usar o próprio Banco de Ideias manualmente pelo celular por algumas semanas e observar frequência de captura, ideias retomadas, perguntas úteis, mudanças de estado, limitações da memória persistente e funções pelas quais faria sentido pagar.

> Este registro está em estágio inicial. Ele não autoriza a criação de backlog técnico nem o início do desenvolvimento.
