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
9. Atualizar o INDEX.md sempre que uma ideia for criada, movida, renomeada ou tiver seu estado alterado.
10. Nunca apagar uma ideia apenas porque foi descartada; mover para archive/ e registrar o motivo.

## Estrutura obrigatória

inbox/ para ideias recém-capturadas; ideas/ para ideias em análise, incubadas ou prontas para testar; projects/ para ideias transformadas ou incorporadas; archive/ para ideias arquivadas, fundidas ou descartadas; templates/ para modelos; INDEX.md como índice mestre.

## Estados e localização

- Capturada → inbox/
- Em análise → ideas/
- Incubada → ideas/
- Pronta para testar → ideas/
- Transformada em projeto → projects/
- Incorporada a projeto existente → projects/
- Arquivada → archive/

O estado inicial padrão é **Capturada**. Ao mudar o estado, mover o arquivo quando necessário e corrigir todos os links no INDEX.md.

## Convenção de nomes

Usar nomes curtos, descritivos e em kebab-case, sem acentos. Evitar nomes genéricos.

## Captura rápida

Quando o usuário pedir para registrar uma ideia:

1. Criar um título curto.
2. Criar um arquivo em inbox/.
3. Preservar a descrição original.
4. Identificar em uma frase o problema ou oportunidade.
5. Registrar o estado como Capturada.
6. Identificar possíveis relações com projetos existentes sem forçar associação.
7. Registrar no máximo três dúvidas importantes.
8. Adicionar a entrada ao INDEX.md.
9. Registrar a criação no histórico.
10. Não iniciar análise extensa, exceto quando solicitado.

## Desenvolvimento de uma ideia

Quando o usuário pedir para desenvolver ou analisar uma ideia:

1. Localizar o arquivo existente antes de criar outro.
2. Apresentar o entendimento atual.
3. Identificar o problema.
4. Explicitar premissas.
5. Explorar interpretações e aplicações.
6. Verificar projetos relacionados.
7. Identificar evidências favoráveis e contrárias.
8. Mostrar lacunas.
9. Definir a próxima análise.
10. Registrar a análise no histórico.
11. Atualizar o INDEX.md quando necessário.

Não criar plano técnico completo, backlog ou arquitetura sem solicitação.

## Relação com projetos existentes

Considerar especialmente social_media-analytics, Hermes, n8n, análises automotivas, produção de conteúdo e dados de YouTube, Instagram, TikTok, Google Trends e Fenabrave. Não decidir automaticamente se uma ideia pertence a algum deles.

## Promoção, arquivamento e fusão

Uma ideia somente deve virar projeto quando problema, usuário, benefício, evidências, riscos, recursos e experimento inicial estiverem suficientemente compreendidos. Registrar a decisão, mover o arquivo e atualizar o INDEX.md.

Ao arquivar, registrar motivo, preservar histórico, mover para archive/ e atualizar o índice. Ao fundir, preservar origem, criar referências cruzadas e arquivar a ideia incorporada.

## Índice e histórico

O INDEX.md deve conter título e link, estado, resumo, projeto relacionado, principal questão em aberto e data de atualização. O arquivo individual prevalece em caso de divergência.

Cada ideia deve ter uma seção Histórico no formato:

### AAAA-MM-DD — Tipo da atualização

Descrição objetiva do que foi capturado, analisado ou decidido.

## Uso de fontes externas

Quando uma análise depender de fatos externos, pesquisar fontes atuais e confiáveis, registrar links, separar fatos de inferências e não apresentar estimativas como fatos.

## Commits e sincronização remota obrigatória

Usar commits pequenos e descritivos, por exemplo:

- docs: add idea about automotive trend detection
- docs: expand analysis of comment mining idea
- docs: move trend detection idea to projects
- docs: update idea index

Quando uma alteração envolver uma única ideia e o índice, ambos devem preferencialmente fazer parte do mesmo commit.

**Todo novo item, alteração ou modificação realizada por um agente deve obrigatoriamente ser registrado no repositório remoto ao final do trabalho do agente.**

Um trabalho somente é considerado concluído quando o agente:

1. cria ou atualiza os arquivos correspondentes;
2. cria commit descritivo;
3. envia a alteração para a branch remota aplicável;
4. verifica que o commit está disponível no GitHub.

Conteúdo existente apenas no ambiente local, na conversa, na memória do agente ou em uma GitHub Issue não é considerado registrado nem concluído.

## Estilo de interação

- Responder em português, salvo solicitação diferente.
- Ser direto e organizado.
- Fazer poucas perguntas por vez.
- Priorizar uso pelo celular.
- Aceitar entradas informais ou ditadas por voz.
- Corrigir erros de transcrição sem mudar o significado.
- Não exigir formulários rígidos.
- Não afirmar que um arquivo foi alterado sem concluir e verificar a gravação.
