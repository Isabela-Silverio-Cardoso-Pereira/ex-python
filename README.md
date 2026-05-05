# ex-python
Leia dois valores inteiros, neste caso, as variáveis ​​A e B. Em seguida, calcule a soma entre eles e atribua o resultado à variável SOMA. Escreva o valor dessa variável.

Entrada
O arquivo de entrada contém 2 números inteiros.

Saída
Imprima a mensagem "SOMA" em letras maiúsculas, com um espaço em branco antes e depois do sinal de igual, seguido do valor correspondente à soma de A e B. Como em todos os problemas, não se esqueça de imprimir o final da linha, caso contrário, você receberá um erro de apresentação.

A = int(input())
B = int(input())

SOMA = A + B

print(f"SOMA = {SOMA}")

----------------------------

DECIMAL 

Leia dois valores inteiros. Em seguida, calcule o produto entre eles e armazene o resultado em uma variável chamada PROD. Imprima o resultado como no exemplo abaixo. Não se esqueça de imprimir a quebra de linha após o resultado, caso contrário, você receberá um erro de apresentação.

Entrada
O arquivo de entrada contém 2 números inteiros.

Saída
Imprima a mensagem "PROD" e PROD de acordo com o exemplo a seguir, com um espaço em branco antes e depois do sinal de igual.

A = int(input())
B = int(input())

PROD = A * B


---------------------------

Ler 2 números decimais (A e B)
Calcular a média ponderada:
A tem peso 3.5
B tem peso 7.5

# -*- coding: utf-8 -*-

A = float(input())
B = float(input())

MEDIA = (A * 3.5 + B * 7.5) / 11

print("MEDIA = %.5f" % MEDIA)

print("PROD = %d" % PROD)

#%d pra forçar que entre só decimal no % PROD 

-------------------------------

Leia três notas (A, B e C), calcule a média ponderada com pesos 2, 3 e 5, respectivamente, e exiba o resultado no formato: MEDIA = valor.

A = float(input())
B = float(input())
C = float(input())

MEDIA = (A * 2 + B * 3 + C * 5) / 10

print("MEDIA = %.1f" % MEDIA)


------------------------------
Leia quatro valores inteiros (A, B, C e D), calcule a diferença entre os produtos (A × B − C × D) e imprima no formato: DIFERENCA = valor.
'''
Escreva a sua solução aqui
Code your solution here
Escriba su solución aquí
'''
A = int(input())
B = int(input())
C = int(input())
D = int(input())
DIFERENCA = (A*B) - (C*D)
print("DIFERENCA = %d" % DIFERENCA)
--------------------------

Escreva um programa que leia o número de um funcionário, o número de horas trabalhadas no mês e o valor recebido por hora. Imprima o número do funcionário e o salário que ele receberá no final do mês, com duas casas decimais.
Não se esqueça de imprimir a quebra de linha após o resultado, caso contrário, você receberá um erro de apresentação.
Não se esqueça do espaço antes e depois do sinal de igual e depois do cifrão ($).
Entrada
O arquivo de entrada contém 2 números inteiros e 1 valor de ponto flutuante, representando o número, o número de horas trabalhadas e o valor que o funcionário recebe por hora trabalhada.
Saída
Imprima o número e o salário do funcionário, de acordo com o exemplo fornecido, com um espaço em branco antes e depois do sinal de igual.

numero = int(input())
horas_trabalhadas = int(input())
valor_por_hora = float(input())
salario = horas_trabalhadas*valor_por_hora
print(f"NUMBER = {numero}")
print(f"SALARY = U$ {salario:.2f}")

---------------------------------------------

Crie um programa que leia o nome de um vendedor, seu salário fixo e o total de vendas realizado por ele no mês (em dinheiro). Considerando que este vendedor recebe 15% sobre todos os produtos vendidos, escreva o salário final (total) deste vendedor no final do mês, com duas casas decimais.
- Não se esqueça de imprimir o final da linha após o resultado, caso contrário, você receberá um erro de apresentação.
- Não se esqueça dos espaços em branco.
Entrada
O arquivo de entrada contém um texto (primeiro nome do funcionário) e dois valores de dupla precisão, que são o salário do vendedor e o valor total das vendas realizadas por ele.
Saída
Imprima o salário total do vendedor, de acordo com o exemplo fornecido.

# -*- coding: utf-8 -*-

'''
Escreva a sua solução aqui
Code your solution here
Escriba su solución aquí
'''

nome = input()
salario_fixo = float(input())
total_vendas = float(input())
salario_final = salario_fixo + (total_vendas*0.15)
print(f"TOTAL = R$ {salario_final:.2f}")




