# Minicalculadora


print('Bem vindo a mini calculadora!')

num1 = float(input('Digite o primeiro numero:'))
operador = input('digite a operadora:')
num2 = float(input('Digite o segundo numero:'))

if operador == "+":
    resultado = num1 + num2
    print(" O resultado e:", resultado)

elif operador == "-":
    resultado = num1 - num2
    print('O resultado e:', resultado)

elif operador == "*":
    resultado = num1 * num2 
    print('O resultado e:', resultado)

elif operador =="/":
    resultado = num1 / num2
    print('O resultado e:', resultado)

else: 
    print('Operador invalido!')
