O código abaixo é usado nas configurações do plugin Zotero Integration para definir o título que a nota de literatura terá. 

Ele é longo porque precisa determinar o número de autores e selecionar a opção correta entre:

- Sobrenome (ano) título - um(a) autor(a);
- Sobrenome 1 & Sobrenome 2 (ano) título - dois(duas) autores(as); ou
- Sobrenome 1 et al (ano) título - três ou mais autores(as).

```
{% set authlist = authors %} {%- if creators.length>2 %} {%- set authlist = creators[0].lastName+' et al.'-%} {% endif -%} {%- if creators.length == 1 %} {%- set authlist = creators[0].lastName-%} {% endif -%} {%- if creators.length == 2 %} {%- set authlist = creators[0].lastName+' & '+creators[1].lastName-%} {% endif -%}{{authlist}} ({{date | format("YYYY")}}) {{title}}.md
```

O código está incluído aqui como referência apenas, uma vez que essa configuração já está incluída no template.