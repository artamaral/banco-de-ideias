# Posts automáticos para grupo de ofertas

## Metadados

- **Estado:** Em análise
- **Origem:** Conversa no ChatGPT
- **Data de captura:** 2026-07-12
- **Projeto relacionado possível:** Grupo de mensagens / grupo de ofertas
- **Decisão atual:** Analisar o processo de seleção dos itens e o nível adequado de automação antes da implementação

## Descrição original

Precisamos, para o projeto de grupo de mensagens e grupo de ofertas, criar automaticamente uma ou duas vezes por dia posts para Instagram e TikTok com base nas informações da página. O fluxo deve ser executado pelo n8n e definir para quais itens os posts serão criados.

A seleção do item não precisa necessariamente ser totalmente automática. Ela poderá ocorrer por processo automático baseado em score, por definição humana ou por um modelo híbrido. O objetivo é chegar a um processo confiável que permita gerar de um a dois posts por dia.

## Entendimento atual

A ideia é criar uma rotina diária de conteúdo para Instagram e TikTok aproveitando os produtos, ofertas e demais informações já disponíveis no projeto. O n8n seria o orquestrador do fluxo, mas ainda precisa ser definido como os itens serão escolhidos e se haverá aprovação humana antes da publicação.

## Problema ou oportunidade

As ofertas e informações já disponíveis no projeto podem ser reaproveitadas como conteúdo recorrente para Instagram e TikTok, reduzindo trabalho manual e criando uma rotina diária de divulgação dos itens mais relevantes.

## Hipóteses iniciais

- O n8n pode orquestrar a seleção, geração e publicação ou preparação dos posts.
- As informações existentes na página são suficientes para gerar o conteúdo básico.
- A escolha do produto pode combinar score automático e aprovação humana.
- A frequência inicial desejada é de um a dois posts por dia.
- O desempenho dos posts poderá futuramente ajudar a ajustar os critérios de seleção.

## Alternativas em análise

### Seleção automática

O sistema escolhe os produtos usando um score baseado em critérios como atratividade da oferta, desconto, comissão, disponibilidade, novidade e potencial de engajamento.

### Seleção humana

Uma pessoa escolhe previamente os produtos que poderão virar posts, e o n8n automatiza somente a criação e a publicação ou preparação do conteúdo.

### Seleção híbrida

O sistema apresenta uma lista priorizada por score e uma pessoa aprova ou substitui o item antes da geração e publicação. Esta alternativa reduz o trabalho manual sem entregar totalmente a decisão ao algoritmo.

## Dúvidas principais

1. Quais critérios ou sinais devem compor o score de seleção dos itens?
2. A primeira versão deve publicar automaticamente ou exigir aprovação humana antes da postagem?
3. Instagram e TikTok receberão o mesmo conteúdo adaptado ou formatos criativos diferentes?

## Próxima análise

Definir quais dados de produto e desempenho já existem no projeto e verificar quais deles poderiam sustentar um score simples. Depois, comparar os fluxos automático, humano e híbrido para escolher o experimento inicial de menor risco.

## Relações possíveis

- Projeto de grupo de mensagens e grupo de ofertas.
- Automação por n8n.
- Produção automatizada de conteúdo para Instagram e TikTok.
- Possível uso futuro de métricas de desempenho para retroalimentar o score de seleção.

## Histórico

### 2026-07-12 — Mudança de estado

Ideia movida de **Capturada** para **Em análise**. Foram acrescentados o entendimento atual, as três alternativas de seleção e a próxima análise recomendada.

### 2026-07-12 — Captura

Ideia registrada a partir de descrição por voz. Foi preservada a possibilidade de seleção automática, humana ou híbrida dos itens, sem definir prematuramente a arquitetura ou transformar a ideia em tarefa de implementação.
