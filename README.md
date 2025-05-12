Python - Comando de seleção: if ... else ... 
					    if ... elif ... else ...
OBJETIVO - 
Criar um programa simples que utiliza estruturas condicionais (if, elif, else) para informar a fase da vida de uma pessoa com base na idade digitada

TECNOLOGIAS UTILIZADAS - 
Python 
Editor de texto (PyCharm)

COMO FUNCIONA - 
O usuário informa sua idade, e o programa responde com uma das seguintes mensagens:

"Você é menor de idade" para idade menor que 18.

"Você é um adulto" para idade entre 18 e 59.

"Você é idoso" para idade 60 ou mais.

CODIGO - 
idade = int(input("Digite sua idade: "))

if idade < 18:
    print("Você é menor de idade.")
elif idade < 60:
    print("Você é um adulto.")
else:
    print("Você é idoso.")
