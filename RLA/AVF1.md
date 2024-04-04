# Questão 1
```
def TrocaValores():
    A = input('Digite A: ')
    B = input('Digite B: ')
    Mem = B
    B = A
    A = Mem
    print(f'{A}, {B}')
``` 
# Questão 2
```
def ContaAprovação():
    Aprov = 0
    Qn = int(input('Digite a quantidade de notas que voce quer avaliar: '))
    while Qn > 0:
        Nota = int(input('Digite a nota: '))
        if Nota >= 70 and Nota <= 100:
            Qn = Qn - 1
            Aprov = Aprov + 1
        else:
            Qn = Qn - 1
    print(f'O numero de aprovados é {Aprov}')
```
# Questão 3
```
def SomaConjunto():
    Sum = 0
    Ns = int(input('Digite o número de elementos do conjunto que você quer somar: '))
    while Ns > 0:
        Num = float(input('Digite um número: '))
        Sum = Sum + Num
        Ns = Ns - 1
    print(f'A soma do conjunto de números fornecidos é {Sum}')
```
# Questão 4
```
# Insira seu código-fonte aqui.
def SomaTermos():
    sum = 0
    k = 1
    nTermo = int(input('Digite o número de termos que você quer calcular: '))
    while nTermo > 0:
        nTermo = nTermo - 1
        sum = sum + (2 * k - 1)/(2 * k)
        k = k + 1
    print(f'A soma dos termos é {sum:.2f}')
```
