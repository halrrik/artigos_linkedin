# Grimorio Content Engine

Sistema editorial versionado para criar, amadurecer, revisar e publicar conteudo autoral com apoio de IA, usando uma abordagem de Grimorio.

Este repositorio nao nasce como deposito solto de posts. Ele nasce como um sistema de memoria, estilo, backlog e operacao editorial.

## Entrada canonica

Para tarefas estruturais, validacao como Grimorio, roteamento de contexto, migracao, evolucao arquitetural ou uso por IA, a entrada canonica e:

```text
registry.yaml
```

Para leitura humana inicial, este README continua sendo a porta de entrada explicativa.

Arquivos estruturais principais:

- `registry.yaml`: entrada machine-native do Grimorio filho de conteudo editorial.
- `routes.yaml`: contrato de roteamento entre tipos de pedido e arquivos de contexto.
- `validation/grimorio-identity-check.yaml`: validacao do repositorio contra as hipoteses do Grimorio pai.

## Objetivo

Construir uma maquina editorial pessoal capaz de transformar ideias brutas, conversas, experiencias profissionais, reflexoes e artigos antigos em novos conteudos publicaveis, mantendo coerencia de voz, intencao e qualidade.

O primeiro canal alvo e LinkedIn, mas o sistema nao deve ficar limitado a LinkedIn. O mesmo backlog pode alimentar artigos longos, palestras, newsletters, carrosseis, respostas a debates e materiais futuros.

## Principios

1. A IA nao inventa uma voz do zero. Ela aprende com amostras, contexto, restricoes e decisoes editoriais.
2. O agente nao publica sem governanca. A aprovacao humana vem antes da automacao.
3. O backlog e mais importante que a ferramenta de postagem.
4. Estilo antigo deve orientar, nao aprisionar.
5. Textos criativos podem influenciar densidade e sensibilidade, mas nao devem contaminar indevidamente textos profissionais.
6. O sistema deve registrar decisoes editoriais para reduzir retrabalho e repeticao.
7. Conteudo pronto deve ser distinguido de ideia bruta.

## Estrutura

- `registry.yaml`: entrada canonica para IA e validacao estrutural.
- `routes.yaml`: roteamento operacional para consultas e tarefas editoriais.
- `context/`: contexto operacional do sistema editorial.
- `grimoire/`: memoria viva do sistema: nucleo, estilo, rituais e aprendizados.
- `agent/`: prompts e regras para agentes editoriais.
- `backlog/`: ideias, temas, series, artigos e posts futuros.
- `inbox/`: captura rapida de ideias ainda nao organizadas.
- `writing-samples/`: artigos e textos antigos usados como referencia de escrita.
- `templates/`: modelos reutilizaveis.
- `drafts/`: textos em desenvolvimento.
- `ready/`: textos aprovados para publicacao.
- `published/`: historico de publicacoes.
- `metrics/`: resultados e aprendizados depois da publicacao.
- `decisions/`: decisoes editoriais versionadas.
- `workflows/`: processos operacionais.
- `validation/`: validacoes de identidade, qualidade e aderencia ao Grimorio.

## Modo de uso inicial

1. Adicionar artigos antigos em `writing-samples/`, separados por categoria.
2. Preencher o backlog inicial em `backlog/themes.md`, `backlog/series.md`, `backlog/articles.md` e `backlog/linkedin-posts.md`.
3. Usar `agent/editorial-agent.md` para transformar itens aprovados em rascunhos.
4. Revisar rascunhos em `drafts/`.
5. Mover textos aprovados para `ready/`.
6. Depois da publicacao, registrar em `published/` e atualizar `metrics/`.

## Nota importante

Este repositorio e operacional. Ele pode usar Shade/Grimorio como abordagem, mas nao deve virar deposito caotico de tudo. A separacao entre ideia, rascunho, texto aprovado e texto publicado deve ser preservada.

Pela validacao atual, este repositorio passa condicionalmente como um Grimorio filho editorial. As principais lacunas restantes sao importar ou referenciar amostras reais de escrita, analisar essas amostras e preencher a memoria editorial com aprendizados aprovados.