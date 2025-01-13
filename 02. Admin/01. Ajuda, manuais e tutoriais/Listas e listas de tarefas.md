---
parent: "[[Markdown - Sintaxe]]"
---
> [!tip] Dica
> Este template já tem configurado um atalho (Ctrl + Enter) para alternar entre:
> 
> - Item de lista simples não ordenada.
> - Item de lista de tarefas não marcado.
> - Item de lista de tarefas marcado.

(Fonte das informações abaixo: [aqui](https://github.com/mende1/guia-definitivo-de-markdown/tree/master))

Você pode organizar listas, podendo ser ordenadas ou não.

## Listas Ordenadas

Usando (número)(ponto) você pode ordenar as listas numericamente, como por exemplo:

```markdown
1. Primeiro
2. Segundo
3. Terceiro
4. Quarto
```

Vai gerar o seguinte resultado:

1. Primeiro
2. Segundo
3. Terceiro
4. Quarto

Itens da lista de aninhamento

Para aninhar itens de linha em uma lista ordenada, recue os itens quatro espaços ou uma guia.

```markdown
1. Primeiro item
2. Segundo item
3. Terceiro item
    1. Indentado item
    2. Indentado item
4. Quarto item
```
Irá gerar:

1. Primeiro item
2. Segundo item
3. Terceiro item
    1. Indentado item
    2. Indentado item
4. Quarto item

## Listas não Ordenadas

Para criar uma lista não ordenada, adicione traços (-), asteriscos (*) ou sinais de adição (+) na frente de
itens de linha.
```markdown
- Exemplo 1

* Exemplo 2

+ Exemplo 3
```

Vai gerar:

- Exemplo 1

* Exemplo 2

+ Exemplo 3

## Lista de tarefas

Podemos criar também uma lista de tarefas, com a CheckBox preenchida ou não. Vejamos o exemplo:

```markdown
- [ ] Esta é uma CheckBox não marcada
- [x] Esta é uma CheckBox marcada
```

- [ ] Esta é uma CheckBox não marcada
- [x] Esta é uma CheckBox marcada


