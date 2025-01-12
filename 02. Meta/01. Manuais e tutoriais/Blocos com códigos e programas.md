---
parent: "[[Markdown - Sintaxe]]"
---
(Fonte das informações abaixo: [aqui](https://github.com/mende1/guia-definitivo-de-markdown/tree/master))

Para colocar algum código sem que ele esteja formatado, então poderá colocar algum código em _Markdown_ dentro dos trechos de códigos e ele não será formatado, será mostrado exatamento como escreveu, é desse jeito que eu consigo mostrar para vocês os códigos como são originalmente antes de serem formatados em _.md_.

Temos o trecho simples, sendo de apenas uma linha, usando uma crase para abrir e outra para fechar:

```
` este é um exemplo `
```

Resultado:

`este é um exemplo`

E também temos a mais completa, que podemos colocar quantas linhas de códigos nós quisermos. Use três crases ( ´´´ ) ou três tils ( ~~~ ) para abrir e três para fechar, desse jeito:

```
    ```
    Este é nosso
    Querido Exemplo
    
    **Teste**
    
    Nota que não irá formatar o negrito!
    ```
```

Vai gerar:

```
Este é nosso
Querido Exemplo
**Teste**
Nota que não irá formatar o negrito!
```

Para especificar qual linguagem seu código é feito, isso ajuda tanto semanticamente como também na coloração do código, basta adicionar o nome da linguagem logo após os três primeiros tils ou crases. Por exemplo:

```
    ~~~python
    s = "Sintaxe do Pythong"
    print s
    ~~~
```

```python
s = "Sintaxe do Python"
print s
```