# aulas-python
desenvolvimento do conteúdo visto nas aulas de python

## tipos primitivos: string, number (int/float), boolean
### Operadores aritméticos (soma,subtração, divisão, porcentagem)
- operadores lógicos/comparativos
- **estruturas _condicionais_ (if/elif/else)**
- para edição das documentações no github: <br/> guia básico de [markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
- salvar para referências de tipos primitivos em python: <br/>
  [dev.to](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

  ![dollynho_chamando_vamos_la](https://static.wikia.nocookie.net/nn-games/images/1/13/Doas.jpg/revision/latest?cb=20200721172336&path-prefix=pt-br)

  # exercicios de fixação:
  ## prática de exercícios com estruturas condicionais
  Escreva um programa que pergunte o nome de um usuário. Se o nome for "Alice" ou "Bob", o programa deve imprimir uma saudação especial: (f"Olá, {nome}! Como está você?"). Caso contrário, deve imprimir uma saudação comum: (f"olá {nome}!")


```py
nome = input("qual o seu nome?")
if nome== "Alice":
  print (f"Olá, {nome}! Como está você?")

elif nome== "Bob":
  print(f"Olá {nome}! Como está você? ")

else:
  print(f"olá {nome}!")
```

Aqui, expliquei que se o nome inserido pelo usuário for Alice ou se for Bob, ele deve imprimir a saudação especial. Para qualquer outro resultado, deveria ser impressa a saudação normal.

## prática de exercícios com operadores aritméticos:
Crie um programa que peça ao usuário para digitar um número **inteiro**. Em seguida, o programa deve verificar se o número é par ou impar e imprimir a mensagem correspondente

```py


  
