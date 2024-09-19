# desafio_python
menu = """
-------------- menu --------------
[d] depositar
[s] sacar
[e] extrato 
[q] sair 

=> """

saldo = 0 
limite = 500
extrato = ""
numero_saques = 0 
LIMITE_SAQUES = 3
     
     
while True:
        opcao = input(menu)

        if opcao == "d":
            print("Deposito")
            deposito = float(input("Qual e o valor do deposito:"))
            if deposito > 0:
                 saldo += valor 
                 extrato += f"Deposito: R$ {deposito:.2f}\n"
            else: 
                 print("Operação falhou! Valor informado é invalido")
            
        elif opcao == "s":
            print("Saque")
            
        elif opcao == "e":
            print("Extrato")
    
        elif opcao == "q":
            break

        else:
            print("Operação inválida, por favor selecione novamente a operação desejada.")
