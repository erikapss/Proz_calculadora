# Proz_calculadora
# Atividade referente ao curso da Proz
# python

operacao = "$"
a = 10
b = 10


def soma(n1, n2):
  so = (n1 + n2)
  print (so)


def subtracao (n1, n2):  
  su = (n1 - n2)
  print (su)


def multiplicacao (n1, n2):
  mu = (n1 * n2)
  print (mu)


def divisao (n1, n2):
  di = (n1 / n2)
  print (di)


#programa principal
if operacao == ("+"):
  soma(a, b)
elif operacao == ("-"): 
  subtracao(a, b) 
elif operacao == ("*"): 
  multiplicacao(a, b)
elif operacao == ("/"): 
  divisao(a, b)  
else:
  print("Operação não identificada. Tente novamente.")
