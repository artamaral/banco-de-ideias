# Banco de Ideias — Regras do Projeto

## Objetivo

Este repositório funciona como um banco de ideias pessoal.

Seu objetivo é permitir que ideias sejam capturadas rapidamente por voz ou texto, preservadas e desenvolvidas ao longo do tempo, sem que sejam transformadas prematuramente em tarefas ou projetos.

Os arquivos Markdown deste repositório são a fonte de verdade. Conversas no ChatGPT, Codex, Hermes ou outros agentes são interfaces de captura, análise e manutenção.

## Princípios

1. Uma ideia pode permanecer incompleta, incerta ou em análise por tempo indeterminado.
2. Não transformar automaticamente uma ideia em projeto, tarefa, produto ou plano de implementação.
3. Preservar a descrição original da ideia sempre que possível.
4. Separar claramente:
   - fatos;
   - hipóteses;
   - suposições;
   - dúvidas;
   - decisões.
5. Relacionar a ideia a projetos já conhecidos somente quando houver uma conexão relevante.
6. Não forçar classificações detalhadas durante a captura.
7. Evitar respostas excessivamente longas quando o usuário estiver apenas registrando uma ideia.
8. Manter o histórico de evolução da ideia no próprio arquivo.
9. Atualizar o `INDEX.md` sempre que uma ideia for criada, movida, renomeada ou tiver seu estado alterado.
10. Nunca apagar uma ideia apenas porque foi descartada; mover para `archive/` e registrar o motivo.

## Estrutura obrigatória

```text
inbox/       ideias recém-capturadas
ideas/       ideias em análise, incubadas ou prontas para testar
projects/    ideias transformadas em projetos ou incorporadas a projetos
archive/     ideias arquivadas, fundidas ou descartadas
templates/   modelos de documentos
INDEX.md     índice mestre
```

## Estados permitidos

Cada ideia deve utilizar exatamente um dos seguintes estados:

- Capturada
- Em análise
- Incubada
- Pronta para testar
- Transformada em projeto
- Incorporada a projeto existente
- Arquivada

O estado inicial padrão é **Capturada**.

## Regras de localização dos arquivos

- `Capturada` → `inbox/`
- `Em análise` → `ideas/`
- `Incubada` → `ideas/`
- `Pronta para testar` → `ideas/`
- `Transformada em projeto` → `projects/`
- `Incorporada a projeto existente` → `projects/`
- `Arquivada` → `archive/`

Ao mudar o estado, mover o arquivo quando necessário e corrigir todos os links no `INDEX.md`.

## Convenção de nomes

Usar nomes curtos, descritivos e em `kebab-case`, sem acentos.

Exemplo:

```text
ideas/deteccao-antecipada-de-tendencias.md
```

Evitar nomes genéricos como:

```text
ideia-1.md
nova-ideia.md
teste.md
```

## Captura rápida

Quando o usuário disser “nova ideia”, “guarde esta ideia”, “registre esta ideia” ou equivalente:

1. Criar um título curto.
2. Criar um arquivo em `inbox/`.
3. Preservar a descrição original.
4. Identificar, em uma frase, o problema ou oportunidade.
5. Registrar o estado como `Capturada`.
6. Identificar possíveis relações com projetos existentes, sem forçar uma associação.
7. Registrar no máximo três dúvidas importantes.
8. Adicionar a entrada ao `INDEX.md`.
9. Registrar a criação no histórico da ideia.
10. Não iniciar análise extensa, exceto quando solicitado.

Na captura inicial, não é obrigatório preencher todas as seções do template.

## Desenvolvimento de uma ideia

Quando o usuário pedir para desenvolver ou analisar uma ideia:

1. Localizar o arquivo existente antes de criar outro.
2. Apresentar o entendimento atual.
3. Identificar o problema que ela pretende resolver.
4. Explicitar as principais premissas.
5. Explorar diferentes interpretações ou aplicações.
6. Verificar se ela cabe em um projeto existente.
7. Identificar evidências favoráveis e contrárias.
8. Mostrar o que ainda precisa ser descoberto.
9. Definir uma próxima pergunta ou análise.
10. Registrar a nova análise no histórico.
11. Atualizar o resumo ou a questão principal no `INDEX.md` quando necessário.

Não criar um plano técnico completo, backlog ou arquitetura sem solicitação.

## Relação com projetos existentes

Considerar especialmente os projetos já conhecidos do usuário, incluindo:

- `social_media-analytics`;
- Hermes;
- automações com n8n;
- análises do mercado automotivo;
- produção de conteúdo;
- dados de YouTube, Instagram, TikTok, Google Trends e Fenabrave.

Uma ideia pode:

- ser uma funcionalidade de um projeto existente;
- complementar um projeto;
- substituir uma solução existente;
- permanecer independente;
- tornar-se um novo projeto.

Não decidir automaticamente entre essas opções.

## Promoção para projeto

Uma ideia somente deve ser considerada pronta para projeto quando houver entendimento suficiente sobre:

- problema;
- usuário ou beneficiário;
- benefício esperado;
- evidências;
- principais riscos;
- dados ou recursos necessários;
- experimento inicial possível.

Antes de promover uma ideia:

1. Apresentar as informações existentes.
2. Evidenciar as lacunas restantes.
3. Registrar a decisão.
4. Mover o arquivo para `projects/`.
5. Atualizar o estado e o `INDEX.md`.
6. Incluir link para o repositório ou projeto relacionado, quando existir.

## Arquivamento e fusão

Ao arquivar:

1. Registrar o motivo.
2. Manter o histórico.
3. Mover o arquivo para `archive/`.
4. Atualizar o estado para `Arquivada`.
5. Atualizar o `INDEX.md`.

Ao fundir ideias:

1. Escolher uma ideia principal.
2. Transferir para ela os elementos relevantes.
3. Registrar a origem das informações.
4. Arquivar a ideia incorporada.
5. Criar links cruzados entre os arquivos.
6. Atualizar o `INDEX.md`.

## Revisão do banco

Quando o usuário pedir uma revisão:

1. Ler o `INDEX.md`.
2. Conferir os arquivos relevantes antes de concluir.
3. Organizar as ideias por estado.
4. Identificar ideias semelhantes ou complementares.
5. Destacar ideias sem análise recente.
6. Mostrar ideias relacionadas aos projetos ativos.
7. Sugerir quais ideias merecem investigação adicional.
8. Não recomendar arquivamento apenas por falta de atividade recente.

## Índice de ideias

O `INDEX.md` deve conter, para cada ideia:

- título com link para o arquivo;
- estado atual;
- resumo em uma frase;
- projeto relacionado, quando houver;
- principal questão em aberto;
- data da última atualização relevante.

Não manter no índice informações que contradigam o arquivo da ideia. O arquivo individual prevalece em caso de divergência, e o índice deve ser corrigido.

## Histórico

Cada arquivo de ideia deve ter uma seção `Histórico`.

Formato:

```markdown
### AAAA-MM-DD — Tipo da atualização

Descrição objetiva do que foi capturado, analisado ou decidido.
```

Não reescrever o histórico para fazer parecer que uma decisão antiga já era conhecida antes.

## Uso de fontes externas

Quando uma análise depender de fatos externos:

1. Pesquisar fontes atuais e confiáveis.
2. Registrar os links na seção `Fontes e referências`.
3. Separar fatos confirmados de inferências.
4. Informar quando uma fonte estiver incompleta, desatualizada ou incerta.
5. Não apresentar estimativas como fatos.

## Commits

Usar commits pequenos e descritivos.

Exemplos:

```text
docs: add idea about automotive trend detection
docs: expand analysis of comment mining idea
docs: move trend detection idea to projects
docs: update idea index
```

Quando uma alteração envolver uma única ideia e o índice, ambos devem preferencialmente fazer parte do mesmo commit.

## Estilo de interação

- Responder em português, salvo solicitação diferente.
- Ser direto e organizado.
- Fazer poucas perguntas por vez.
- Priorizar o uso pelo celular.
- Aceitar entradas informais, fragmentadas ou ditadas por voz.
- Corrigir erros de transcrição pelo contexto sem alterar o significado.
- Não exigir formulários ou estruturas rígidas do usuário.
- Não afirmar que um arquivo foi alterado sem concluir e verificar a gravação.
