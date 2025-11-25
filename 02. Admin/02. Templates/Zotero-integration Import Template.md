---
title: {{title}}
authors: {{authors}}
year: {{date | format ("YYYY")}}
tags: 
book / journal: {{publicationTitle}}
aliases:
{% set authlist = authors %}{%- if creators.length>2 %}{%- set authlist = creators[0].lastName+' et al.'-%} {% endif -%} {%- if creators.length == 1 %} {%- set authlist = creators[0].lastName-%} {% endif -%} {%- if creators.length == 2 %} {%- set authlist = creators[0].lastName+' & '+creators[1].lastName-%} {% endif -%}- {{authlist}} ({{date | format("YYYY")}})
- ({{authlist}}, {{date | format("YYYY")}})
- {{citekey}}
Link Zotero: {{desktopURI}}
---

> [!tldr] Resumo geral
> 

- PDF: {{pdfLink}}

{% for annotation in annotations %}{% if annotation.annotatedText %}
> {{annotation.annotatedText}} ({{authlist}}, {{date | format("YYYY")}}, p. {{annotation.pageLabel}}){% endif %}
{% if annotation.imageBaseName %}![[{{ annotation.imageBaseName }}]]
*Screenshot from p. {{annotation.pageLabel}}*{% endif %}
{% if annotation.comment %}
{{annotation.comment}}{% endif %}{% endfor %}

## Referência

- {{bibliography}}