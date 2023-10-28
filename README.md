# Aula-de-POP
# #Aula12
# #conjunto1 = {2,3,6,5,9}
# #conjunto2 = {10,7,6,979}


# #v = conjunto2.union(conjunto1)
# #print(v)


# #print(conjunto1.difference(conjunto2))
# #print(conjunto2.difference(conjunto1))


# #conjunto1.add(789)
# #conjunto2.add(17)

# #print(conjunto1)
# #print(conjunto2)

# #conjunto2.discard(17)
# #print(conjunto2)

# #1 - Crie uma função lambda que retorne o dobro de um número.
# #dobro = lambda x: x*2
# #print(dobro(10))




# # 2 - Crie uma função lambda que calcule a soma de dois números.
# #soma = lambda x: x ** 2
# #print(soma(2))


# #3 - Crie uma função lambda que verifique se um número é par.
# #numeros = [1,2,3,4,5,6,7,8,9,10]
# #impares = list(filter(lambda x: x % 2== 1,numeros))
# #print(impares)

# #4 - Crie uma função lambda que converta uma string em maiúsculas
# #converter_maiusculas = lambda texto: texto. upper()
# #resultado = converter_maiusculas("olá, mundo!")
# #print(resultado) 

# #5 - Crie uma função lambda que calcule o produto de três números.
# #x = lambda char: char.upper()
# #print('Letra maiuscula', x('olha'))



# #4: Crie um conjunto chamado "frutas" com as seguintes frutas: maçã, banana, 
# #laranja, pêra e abacaxi. Em seguida, imprima o número de 
# #elementos no conjunto.

# # frutas = {'maçã', 'banana', 'laranja', 'pêra', 'abacaxi'}
# # print( len(frutas))




# #5: Crie dois conjuntos, "conjunto1" e "conjunto2", 
# #com alguns números inteiros. 
# #Imprima a união desses dois conjuntos
 
# # c1={12,36,9}
# # c2 = {12,6,78} 
# # c3= c1.union(c2)
# # print(c3)


# #6: Dado o conjunto "cores" com cores diferentes, remova a cor 
# #"vermelho" do conjunto.
# # cores = {'azul', 'vermelho', 'verde'}
# # cores.remove('vermelho')
# # print(cores)


# #7: Crie um conjunto chamado "numeros" com os números de 1 a 10. 
# #Em seguida, crie um novo conjunto chamado "pares" 
# #contendo apenas os números pares do conjunto "numeros".
# # todos_os_alunos = {'d', 'e', 'g'}
# # alunos_aprovados = {'a', 'b', 'c'}
# # todos_os_alunos .intersection(alunos_aprovados)
# # print(todos_os_alunos)


# #8: Verifique se o conjunto "alunos_aprovados" contém todos os alunos do 
# #conjunto "todos_alunos". Os conjuntos devem ser definidos com nomes 
# #apropriados.





# #AULA 13



# # cidade = 'São Carlos'
# # endereco = 'Rua Cândido Padim, 25 - Vila Prado'
# # completo = cidade + endereco
# # print(cidade.startswith('São'))
# # print(cidade.endswith('los'))

# # print('Rua' in completo)
# # print('Padim' not in completo)
# # Preciso de sistema que verifique se existe, 
# # no texto a palavra gmail
# # se existir, printe-as


# # email = "senai@gmail.com"

# # # print("senai@gmail.com" in email )

# # if "senai@gmail.com" in email: 
# #     print("O e-mail é ", email) 
# # else: 
# # #     print("Não existe")

# # texto = 'Python é uma linguagem de programação. Python é simples. Python é organizado. Python é uma excelente linguagem.'
# # print(texto.count('é'))
# # print(texto.find('Python', 25,50))

# # print(texto.rfind('lingua'))
# # print(texto.index('é'))
# # print(texto.rindex('é'))


# # texto = 'Olá Mundo!'
# # print(texto)
# # # texto_centro = texto.center(150)
# # # texto_centro_2 = texto.center(20,'.')
# # texto_esquerda = texto.ljust(10)
# # texto_direita = texto.rjust(150)
# # # print(texto_direita)
# # print(f'**{texto_esquerda}*{texto_direita}**')

# # exemplo 1


# # texto= 'Python é uma linguagem de programação.Python é simples. Python é organizado. Python é uma excelente linguagem.'
# # print(texto.count('é'))
# # print(texto.find('Python',25,50))
# # print(texto.rfind('lingua'))
# # print(texto.index('é'))
# # print(texto.rindex('é'))
# # texto = 'Olá Mundo!'
# # print(texto)
# # texto_centro = texto.center(15)
# # texto_centro_2 = texto.center(20,'.')
# # texto_esquerda = texto.ljust(10)
# # texto_direita = texto.rjust(150)
# # print(texto_direita)
# # print(f'**{texto_esquerda}*{texto_direita}**')

# # #separação de strings

# # nomes = 'João Carlos/Maria Paula /Ana beatriz /José Pedro'
# # print(nomes.split('/'))


# # Exercício 1: Escreva um programa que verifique se a palavra "python" 
# # está presente na string "Estou aprendendo Python".

# # frase = 'Estou aprendendo Python'
# # if frase.endswith('Python'):
# #     print("A palavra 'Python' está presente na string.")
# # else:
# #     print(" A frase contém a palavra 'Python'")


# # exercício 2: Escreva um programa que peça ao usuário para digitar 
# # seu nome e verifique se o nome começa com a letra "A" 
# # (maiúscula ou minúscula).

# nome = input('Digite seu nome ' )
# if  nome.startswith('a'):
#     print('seu nome é', name)
# else:
#     print('não começa com a letra A')

# nome = "digite o nome"
# tamanho = len(nome)
# print(tamanho)

# Exercício 3: Escreva um programa que peça ao usuário para digitar uma 
# senha e verifique se a senha contém pelo menos 8 caracteres.


# Exercício 4: Escreva um programa que peça ao usuário para digitar 
# um número e verifique se o número é uma representação numérica 
# (não contém letras ou símbolos).


# Exercício 5: Escreva um programa que peça ao usuário para 
# digitar uma frase e conte quantas vezes a letra "a" 
# (maiúscula ou minúscula) aparece na frase.
# ]
# Aula 14 POP

# list = [1,3,6,9,612]
# n1 = list.pop(0)
# print(n1)
# # print(list)
# d= {
#     'a':12,
#     'b':14
#     }

# r = d.pop('a')
# print('removido:', r,'lista:', d)

nota1 = float(input ("Digite a sua nota" ))
nota2 = float(input ("Digite a sua nota" ))
nota3 = float(input ("Digite a sua nota" ))
media = (nota1 + nota2 + nota3) / 3

if 0 <= media <= 10:
    if media >= 7:
        resultado = "Aprovado"
    elif media >= 5:
        resultado = "Recuperação"
    else:
        resultado = "Reprovado"

    print(f"Sua média é {media} e você está em {resultado}.")
else:
    print("As notas devem estar entre 0 e 10.")

# text = 'Olá bom dia como vai?'
# char = text[3:7]
# print(char)

# Exercício 1: Remova o último elemento de uma lista e imprima a lista resultante.
# list = [1, 2, 3, 4, 5]
# n1 = list.pop(4)
# print(list)

# Exercício 2: Remova o elemento de índice 2 de uma lista e imprima a lista resultante
# list = [10, 20, 30, 40, 50]
# n1 = list.pop(1)
# print(list)

# dicionario = {"chave1": "valor1", "chave2": "valor2", "chave3": "valor3"}
# item_removido = dicionario.pop("chave2")  # Remove o item com chave "chave2"
# print(dicionario)  # O dicionário agora é {"chave1": "valor1", "chave3": "valor3"}
# print("Item removido:", item_removido) 

# Exercício 3: Crie uma lista e implemente a operação pop().
# frutas = ["maçã", "banana", "laranja", "uva"]
# fruta_removida = frutas.pop(1)  # Remove o elemento com índice 1 (banana)
# print(frutas)  # A lista agora é ["maçã", "laranja", "uva"]
# print("Fruta removida:", fruta_removida)  # Isso imprimirá "Fruta removida: banana"

# Exercício 4: Remova o primeiro elemento de uma lista e o último elemento usando pop() e imprima a lista resultante.

# list = [1,3,6,9,612]
# n1 = list.pop(0)
# print(n1)
# # print(list)
# d= {
#     'a':12,
#     'b':13
#     }

# r = d.pop('a')
# print('removido:', r,'lista:', d)

# Exercício 5: Acesse os três primeiros caracteres de uma string.
# text = 'Vai dar tudo certo'
# char = text[0:2]
# print(char)

# # Exercício 4: Remova o primeiro elemento de uma lista e o último elemento usando pop() e imprima a lista resultante.
# frutas = ["maçã", "banana", "laranja", "uva"]
# fruta_removida = frutas.pop(0)  # Remove o elemento com índice 1 (banana)
# print(frutas)  # A lista agora é ["maçã", "laranja", "uva"]
# print("Fruta removida:", fruta_removida)  
# frutas = ["maçã", "banana", "laranja", "uva"]
# fruta_removida = frutas.pop(3)  # Remove o elemento com índice 1 (banana)
# print(frutas)  # A lista agora é ["maçã", "laranja", "uva"]
# print("Fruta removida:", fruta_removida)
