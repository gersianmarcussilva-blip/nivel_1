#  __PDV com Descontos__ 

>__Sobre o projeto:__

_Esse projeto foi feito em Python e serve para simular um sistema de vendas. O programa pede o valor da compra e a idade do cliente, depois calcula os descontos e mostra o valor final. Também é possível fazer várias compras e, no final, ver um resumo de todas elas._

>__Regras dos descontos:__

- Clientes com 65 anos ou mais recebem 20% de desconto.
- Se o valor depois desse desconto ficar maior que R$ 100,00, recebe mais 10% de desconto.
- Se o valor ficar em R$ 100,00 ou menos, não recebe o desconto extra.
- Para encerrar o programa, basta digitar "0" no valor da compra.

>__Como o código funciona__

1. Primeiro, o programa pede o valor da compra.
2. Se o valor for "0", o programa para e mostra o resumo.
3. Se o valor for negativo, aparece uma mensagem de erro.
4. Depois, o programa pede a idade do cliente.
5. Se o cliente tiver 65 anos ou mais, recebe 20% de desconto.
6. Se o valor continuar maior que R$ 100,00, recebe mais 10% de desconto.
7. O programa guarda os valores de cada compra em uma lista.
8. No final, mostra a quantidade de compras, o total bruto, os descontos e o total final.

>__Como executar__

1. Salve o código com o nome "pdv.py".
2. Abra o terminal na pasta onde o arquivo está.
3. Digite o comando abaixo:

"python pdv.py"

4. Digite os valores das compras e as idades quando o programa pedir.
5. Quando quiser terminar, digite "0" no valor da compra.

Exemplo
Se um cliente de 65 anos fizer uma compra de R$ 200,00, o programa vai calcular os descontos assim:__

- Valor da compra: R$ 200,00.
- Desconto de 20%: R$ 40,00.
- Valor depois do primeiro desconto: R$ 160,00.
- Desconto extra de 10%: R$ 16,00.
- Valor final: R$ 144,00.

Quando o programa terminar, ele mostra:

- Quantidade de compras realizadas.
- Total bruto das compras.
- Total de descontos.
- Total final depois dos descontos.

