# calculo_imc
cálculo de imc.

peso = float(input('Digite seu peso'))
h = float(input('Digite sua altura'))

imc = peso / h
if imc < 18.5:
    print('Abaixo do peso')
elif 18.5 <= imc <= 24.9:
    print('Saúdavel')
elif 25.00 <= imc <= 29.9:
    print('Peso em excesso')
elif 30.00 <= imc <= 34.9:
    print('Obesidade grau I')
elif 35.00 <= imc < 39.9:
    print('Obesidade grau II (severa)')
elif imc >= 40.00:
    print('Obesidade grau III (mórbida)')
