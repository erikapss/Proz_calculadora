# Proz
# Atividade referente ao curso da Proz
# python

def calculadora (n1, n2, op):
  if (op == 1 ):
    return n1 + n2
  elif (op == 2):
    return n1 - n2
  elif (op == 3):
    return n1 * n2    
  elif (op == 4):
    return n1 / n2    
  else:
    return 0
    
op = 1000

while op != 0:
  print("Informe o que deseja fazer: 1 - Soma | 2 - Subtração | 3 - Multiplicação | 4 - Divisão | 0 - Saír")
  op = int(input())
  if (op != 1) and (op != 2) and (op != 3) and (op != 4) and (op != 0):
      print("Essa opção não existe. Escolha uma opção válida")
  elif (op == 0):
      break
  else:    
      print("Informe o primeiro número")  
      a = int(input())
      print("Informe o segundo número")  
      b = int(input())
      resultado = calculadora (a, b, op)
      print ("O resultado da operação é: " +str(resultado))
