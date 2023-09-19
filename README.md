# banco_while

opc = -1

while opc != 0:
    opc = int(input("Informe uma opção: \n[1]Sacar \n[2] Extrato:"))

    if opc == 1:
        print(input("sacando... "))
    elif opc == 2:
        print("Exibindo o extrato...")
