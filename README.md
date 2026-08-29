[calculadora 00.py](https://github.com/user-attachments/files/31588704/calculadora.00.py)
numero1 = float(input("digite o primeiro número: "))
numero2 = float(input("digite o segundo número: "))

print("Escolha a operação desejada:")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

operacao = input("Digite o número da operação desejada: ")

if operacao == "1":
    resultado = numero1 + numero2
    print(f"Resultado da soma:{resultado}")
elif operacao == "2":
    resultado = numero1 - numero2
    print(f"Resultado da subtração:{resultado}")
elif operacao == "3":
    resultado = numero1 * numero2
    print(f"Resultado da multiplicação:{resultado}")
elif operacao == "4":
    resultado = numero1 / numero2
    print(f"Resultado da divisão:{resultado}")
