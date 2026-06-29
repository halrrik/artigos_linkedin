# Backlog - Ativos visuais

Este arquivo guarda imagens, capas, chamadas visuais, imagens para feed e conceitos de HQ/caricatura associados a conteudos editoriais.

Nao misturar aqui o texto final do post ou artigo. O objetivo deste backlog e controlar o que precisa ser construido visualmente e qual funcao editorial cada imagem cumpre.

## Modelo de item

```yaml
id:
content_item_id:
titulo_interno:
status: idea
content_format:
visual_asset_type:
visual_asset_policy:
canal:
objetivo_visual:
relacao_com_texto:
publico:
tema:
tese_ou_mensagem:
image_brief:
riscos:
proxima_acao:
```

## Tipos aceitos

- `call_image`: imagem de chamada, capa ou abertura visual.
- `feed_image`: imagem para feed que reforca ou carrega parte da mensagem.
- `hq_caricature`: imagem em estilo HQ/caricatura para representar uma cena, tensao ou antipadrao.

## Itens

```yaml
id: visual-001
content_item_id: article-002
titulo_interno: Capa editorial - A inovacao deixou de ser uma oligarquia
status: rejected_learning
content_format: article_post
visual_asset_type: call_image
visual_asset_policy: recommended
canal: linkedin_article
objetivo_visual: criar capa editorial autoral para artigo longo sobre IA, acesso e materializacao de ideias
relacao_com_texto: a imagem deve cristalizar a ferida central do artigo, nao resumir o argumento inteiro
publico: LinkedIn profissional
tema: IA, inovacao, acesso, ideias invisiveis, prototipagem
tese_ou_mensagem: uma ideia invisivel pede permissao; um prototipo comeca a pedir avaliacao
image_brief: desenho manual em lapis e lapis de cor, paleta suave de papel e fim de tarde, metafora unica de ideia bruta ganhando forma visivel
riscos:
  - gerar proporcao errada e tentar adaptar depois
  - cortar topo ou base no LinkedIn
  - criar moldura artificial ao encaixar imagem alta em formato panoramico
  - cair em poster generico de IA, startup ou infografico
  - usar cores neon ou estetica de template
proxima_acao: se for refazer, criar nativamente no formato final exigido pelo LinkedIn antes de gerar a arte; nao redimensionar imagem aprovada em proporcao inadequada
```
