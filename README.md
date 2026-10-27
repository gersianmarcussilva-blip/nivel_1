compras = []

while True:
    valor = float(input("Digite o valor da compra (0 para sair): R$ "))

    if valor == 0:
        break

    if valor < 0:
        print("Valor inválido! Digite novamente.")
        continue

    idade = int(input("Digite a idade do cliente: "))

    if idade < 0:
        print("Idade inválida! Vamos começar novamente.")
        continue

    valor_final = valor
    desconto = 0

    if idade >= 65:
        valor_final = valor_final * 0.8

    if valor_final > 100:
        valor_final = valor_final * 0.9

    desconto = valor - valor_final

    compras.append({
        "valor": valor,
        "desconto": desconto,
        "final": valor_final
    })

    print(f"Valor final: R$ {valor_final:.2f}")

print("\n--- RESUMO DO DIA ---")

total_bruto = 0
total_descontos = 0
total_final = 0

for compra in compras:
    total_bruto += compra["valor"]
    total_descontos += compra["desconto"]
    total_final += compra["final"]

print(f"Quantidade de compras: {len(compras)}")
print(f"Total bruto: R$ {total_bruto:.2f}")
print(f"Total de descontos: R$ {total_descontos:.2f}")
print(f"Total final: R$ {total_final:.2f}")