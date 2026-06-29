# Publication Index

Indice simples de publicacoes ja realizadas, com URL publica e data/contexto de chat para preencher quando disponivel.

```yaml
publications:
  - id: pub-001
    title: Motores diferentes: pertencimento, faisca e sentido
    status: published
    repository_file: published/2026-06-23-motores-diferentes-pertencimento-faisca-sentido.md
    published_url: pending
    chat_date: 2026-06-23
    notes: arquivo publicado ja existente no repositorio; URL publica ainda pendente.

  - id: pub-002
    title: A inovacao deixou de ser uma oligarquia
    status: published
    repository_file: pending
    published_url: pending
    chat_date: 2026-06-29
    notes: artigo publicado; registrar URL publica quando Richard enviar.

  - id: pub-003
    title: Qual e o combustivel?
    status: published
    repository_file: pending
    published_url: pending
    chat_date: pending
    notes: artigo citado como publicado antes de 2026-06-24; registrar URL publica e data/contexto de chat quando Richard enviar.
```

## Regra

Quando Richard enviar uma URL de artigo publicado, atualizar este indice com:

```yaml
published_url:
chat_date:
source_chat_or_context:
```

Nao inventar URL publica. Se a URL nao foi fornecida, manter `pending`.
