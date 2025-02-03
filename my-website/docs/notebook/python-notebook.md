---
sidebar_position: 1
---

# Python notebook

## Cheet Sheet

Principais métodos de um objeto lista

Método | Descrição | Exemplo
:----- | :-------- | :------
append | Adiciona um elemento no final da lista | `lista.append(5)`
clear  | Apaga todos os elementos de uma lista | `lista.clear()`
copy | Retorna uma cópia dos elementos da lista | `copia = lista.copy()`
count | Retorna a quantidade de ocorrências de um elemento na lista | `qt = lista.count(5)`
extend | Adiciona os elementos de outra lista passada por parâmetro | `lista.extend(outra_lista)`
index | Retorna o índice do elemento passado por parâmetro (primeira posição) | `pos5 = lista.index(5)`
insert | Adiciona um elemento em uma posição passada por parâmetro (adiciona no final caso a posição não exista)| `lista.insert(3, "João")`
pop | Remove o elemento na posição passada por parâmetro (provoca um erro caso a posição não exista)| `elemento = lista.pop(3)`
remove | Remove o elemento passado por parâmetro (provoca um erro caso o elemento não exista)| `lista.remove(5)`
reverse | Inverte a ordem dos elementos de uma lista | `lista.reverse()`
sort | Ordena os objetos de uma lista | `lista.sort()`
 | | `lista.sort(reverse=True)`

### Outras funções

Função | Descrição | Exemplo
:----- | :-------- | :------
len | Retorna a quantidade de elementos de uma lista | `print(len(lista))`
max  | Retorna o maior elemento de uma lista | `maior = max(lista)`
min | Retorna o menor elemento de uma lista | `menor = min(lista)`
sum | Retorna o somatório dos elementos de uma lista | `soma = sum(lista)`

### Funções detalhadas

- **Acessar - lista[x]**

Acessa o item da posição específica.

lista[2]

- **Adicionar - ammend()**

Adiciona um item ou uma lista inteira ao final da lista

`numeros.ammend([4,5])`

`numeros.ammend(27)`

- **Adicionar - append()**

Adiciona os itens de uma lista ao final da lista (apenas os itens)

`numeros.append([4,5])`

- **Adiionar - extend()**

Adiciona novos elementos de uma lista, a partir de outra lista.

```
numeros = [1, 2, 3]
numeros.extend([4,5])
```

- **Adicionar - insert()**

Adiciona o item na posição determinada.

`lista.insert(2, "ABC")`

- **Copiar - copy()**

`lista.copy()`

- **Limpar - clear()**

`lista_reais.clear()`

- **Maior ou menor elemento - max() / min ()**

`max` mostra o maior elemento da lista, independente da posição que ele esteja.

`max(lista)`

`min` mostra o menor elemento da lista, independente da posição que ele esteja.

`min(lista)`

- **Modificar - lista[x] = y**

Modificar o elemento da posição x pelo elemento Y.

`lista[3] = 15`

- **Ordenar - sort()**

Ordena os itens da lista.

`lista.sort()`

Também posso ordenam em ordem decrescente:

`lista.sort(reverse=True)`

- **Posição - index()**

Mostra a posição do elemento na lista, sendo que mostra a primeira ocorrência quando há mais de um.

`lista.index(“Nome”)`
    
   Podemos guardar esse valor em uma variável: 
   
   `posicao8 > lista.index(8)`

- **Quantidade - len()**

Mostra a quantidade de elementos de uma lista.

`len(lista)`

- **Remover - pop()**

Apagar uma posição da lista

`valor = lista.pop(2)`

- **Remover - remove()**

Apagar um item específico da lista.

`lista_strings.remove("Rodrigo")`

- **Somar - sum()**

Soma os elementos de uma lista numérica.

`sum(lista)`

