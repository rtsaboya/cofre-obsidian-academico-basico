- [[Zotero-integration Import Template]]

```
{% set authlist = authors %} {%- if creators.length>2 %} {%- set authlist = creators[0].lastName+' et al.'-%} {% endif -%} {%- if creators.length == 1 %} {%- set authlist = creators[0].lastName-%} {% endif -%} {%- if creators.length == 2 %} {%- set authlist = creators[0].lastName+' & '+creators[1].lastName-%} {% endif -%}{{authlist}} ({{date | format("YYYY")}}) {{title}}.md
```

Ele testa quantos autores há:
- Se for mais que dois, pega o primeira e acrescente et al.
- Se forem dois, lista os sobrenomes dos dois autores separados por ' & '.
- Se for só 1, lista só o sobrenome.

Fonte: [aqui](https://www.reddit.com/r/ObsidianMD/comments/16cekwd/zotero_integration_templating_formatting_author/).