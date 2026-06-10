# Workflow: Pipeline Editorial

## Entrada

Ideias podem entrar por:

- conversa com IA;
- anotacao manual;
- artigo antigo;
- debate no LinkedIn;
- aula, pos, livro ou palestra;
- experiencia profissional;
- comentario de terceiro.

## Estados

1. inbox
2. triaged
3. selected
4. drafting
5. reviewing
6. approved
7. ready
8. scheduled
9. published
10. measured
11. learned

## Processo

1. Capturar ideia em `inbox/` ou `backlog/inbox.md`.
2. Triar para tema, serie, post, artigo ou resposta.
3. Criar item com metadados no backlog adequado.
4. Gerar rascunho usando o agente editorial.
5. Revisar com guia de estilo.
6. Aprovar manualmente.
7. Mover para `ready/`.
8. Publicar manualmente ou por ferramenta aprovada.
9. Registrar em `published/`.
10. Registrar metricas e aprendizados.

## Regra

Automacao deve respeitar o estado do item. Nada sai de `drafts/` para publicacao sem passar por aprovacao.
