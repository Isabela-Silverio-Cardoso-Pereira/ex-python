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
