---
parent: "[[Markdown - Sintaxe]]"
---
> [!tip] Dica
> Este template já tem configurado um atalho (Ctrl + Shift + >) para alternar entre um parágrafo normal e um parágrafo marcado como citação (blockquote):

Para criar uma citação em bloco, adicione um '>' na frente de um parágrafo.

As citações em bloco podem conter vários parágrafos. Adicione um '>' nas linhas em branco entre os parágrafos

Sintaxe:

```markdown
Para citações em uma linha:
> Esta é uma citação

Em várias linhas:
> Citação 1
>
> Citação 2
```

Resultado:

Para citações em uma linha:

> Esta é uma citação

Em várias linhas:

> Citação 1
> 
> Citação 2

As cotações em bloco podem ser aninhadas. Adicione um '>>' na frente do parágrafo que você deseja aninhar ou com "tabs". Por exemplo:

```markdown
> Citação 1
>
>> Citação 2
>
> 	Citação 3
```

E assim temos:

> Citação 1
> 
> > Citação 2
>
> 	Citação 3

As citações de bloco podem conter outros elementos no formato Markdown. Nem todos os elementos podem ser usados, você precisará experimentar para ver quais funcionam. Exemplo:

```markdown
> ## The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going **well**.
```

Resultado:

> ## The quarterly results look great!
> 
> [Teste de URL](https://github.com/mende1/guia-definitivo-de-markdown/blob/master/README.md#the-quarterly-results-look-great)
> 
> - Revenue was off the chart.
> - Profits were higher than ever.
> 
> _Everything_ is going **well**.
