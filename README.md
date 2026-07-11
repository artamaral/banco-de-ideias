# Banco de Ideias

Repositório pessoal para capturar, desenvolver e revisar ideias ao longo do tempo.

O objetivo não é transformar toda ideia imediatamente em tarefa ou projeto. Cada ideia pode permanecer incompleta, em análise ou incubada até que existam evidências e clareza suficientes para decidir seu destino.

## Como usar

A principal interface de uso é o aplicativo do ChatGPT no celular.

Exemplos de comandos:

- `Registre esta ideia no banco de ideias: ...`
- `Aprofunde a ideia sobre ...`
- `Relacione esta ideia aos meus projetos atuais.`
- `Atualize o estado desta ideia para incubada.`
- `Revise o banco e mostre quais ideias merecem nova análise.`

Ao registrar ou atualizar uma ideia, o agente deve seguir as regras de [`AGENTS.md`](AGENTS.md), criar ou editar o arquivo Markdown correspondente e manter o [`INDEX.md`](INDEX.md) atualizado.

## Estrutura

```text
banco-de-ideias/
├── AGENTS.md
├── README.md
├── INDEX.md
├── inbox/
│   └── README.md
├── ideas/
│   └── README.md
├── projects/
│   └── README.md
├── archive/
│   └── README.md
└── templates/
    └── IDEA_TEMPLATE.md
```

### `inbox/`

Ideias recém-capturadas que ainda não receberam análise suficiente.

### `ideas/`

Ideias em análise, incubadas ou prontas para teste. Cada ideia deve ter seu próprio arquivo Markdown.

### `projects/`

Ideias transformadas em novos projetos ou incorporadas formalmente a projetos existentes.

### `archive/`

Ideias arquivadas, descartadas ou fundidas com outras ideias. O histórico deve ser preservado.

### `INDEX.md`

Índice mestre com o estado, resumo, relação com projetos e principal questão em aberto de cada ideia.

### `templates/IDEA_TEMPLATE.md`

Modelo padrão para novas ideias. A captura inicial pode usar apenas as seções essenciais; as demais devem ser preenchidas progressivamente.

## Estados permitidos

- Capturada
- Em análise
- Incubada
- Pronta para testar
- Transformada em projeto
- Incorporada a projeto existente
- Arquivada

## Fluxo básico

```text
Voz ou texto no ChatGPT
        ↓
Captura da ideia no GitHub
        ↓
Análise progressiva no arquivo Markdown
        ↓
Revisões e registro de evidências
        ↓
Projeto existente | Novo projeto | Incubação | Arquivo
```

## Princípios

- Capturar com pouco atrito.
- Preservar a formulação original.
- Não forçar decisões prematuras.
- Separar fatos, hipóteses, suposições, dúvidas e decisões.
- Relacionar ideias a projetos existentes apenas quando houver conexão relevante.
- Manter o histórico de evolução dentro do próprio arquivo e no Git.

## Convenção de nomes

Os arquivos devem usar nomes curtos em `kebab-case`, sem acentos:

```text
ideas/deteccao-antecipada-de-tendencias.md
```

## Fonte de verdade

Os arquivos deste repositório são a fonte de verdade do Banco de Ideias. As conversas no ChatGPT são a interface de captura e análise, não o armazenamento definitivo.
