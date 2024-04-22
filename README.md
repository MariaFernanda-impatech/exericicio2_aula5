# exericicio2_aula5

num1 = float(input("de o primeiro numero: "))
num2 = float(input("de o segundo numero: "))
num3 = float(input("de o terceiro numero: "))

def menu ():
	print ("Vamos calcular o desvio padrão dos 3 números")

def variancia (num1, num2, num3):
	media = (num1 + num2 + num3)/3
	var = ((num1 - media)**2 + (num2 - media)**2 + (num3 - media)**2)/3
	print(f"A varianca é de {var}")
	return var
def desvio_padrao(num1, num, num3):
	desvio = variancia(num1, num2, num3)**0.5
	print(f"A desvio padrão é {desvio}")
	
menu ()
desvio_padrao (num1, num2, num3)
