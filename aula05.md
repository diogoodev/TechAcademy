# Classes e ID

- Tipos de seletores
- ELEMENTOS : Nesta seleção o CSS estiliza todos os elementos de mesma categoria
- CLASSE: Aqui ocorre a diferenciação de um grupo de elementos, assim o CSS irá estilizar todo esse grupo
- ID: Os identificadores(ID) permite a seleção e estilização única para o elemento específico

## Classes

1 - Nos definimos uma classe quando queremos agrupar elementos sob alguma caracteristica.

2 - A mesma classe pode ser definida em varios elementos html

3 - Os seletores de classes são precedidos pelos simbolo .

## ID

1 - Nos defimos um id quando queremos distinguir um elemento, por isso, um elemento com id deve possuir um valor unico

2 - Não podemos definir umid em carios elementos HTML

3 - Os seletore de IDs são precedidos pelo simbolo #

### Outros seletores em CSS

- [ * ] Seletor Universal:
  1 - Seleciona todos elementos de um documento
  2 as regras serão elementos de um documento
  3 - Seu simbolo é \*

  - Seletores Combinados

  1 - É possivel definir a mesma regra para diferentes seletores
  2 - Basta separa os seletores por virgula:

  ```css
  h1,
  title,
  #cards {
    ...;
  }
  ```

- Seletores de descendente e filho:
  1 - O combinador seleciona os noss que são descendendes ou filhos diretos de outros elementos
  2 - Para desdencia basta utilizar um espaço entre os seletores:

```css
#principal cards {
  ...;
}
p span {
  ..;
}
```

3 - Para o filho direto basta utilizar um simbolo de maior > entre os seletores

```css
#principal > cards {
  ...;
}
p > span {
  ...;
}
```
