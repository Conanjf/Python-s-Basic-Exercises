# Python-s-Basic-Exercises
Initial codes in Python

#Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.
#Calcule os devidos descontos

x=float(input("Quanto vc ganha por hora? "))
y=float(input("Quantas horas você trabalhou no mês? "))

a = (x*y)
b = (a*0.11)
c = (a*0.08)
d = (a*0.05)

print('Salário Bruto : R$', (a))
print('IR (11%) : R$', (b))
print('INSS (8%) : R$', (c))
print('Sindicato ( 5%) : R$', (d))
print('Salário Liquido : R$', (a-b-c-d))
