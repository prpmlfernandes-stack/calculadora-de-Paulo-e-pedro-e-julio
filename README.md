# calculadora-de-Paulo-e-pedro-e-julio
num1 = float(input(&quot;Digite o primeiro número: &quot;))
num2 = float(input(&quot;Digite o segundo número: &quot;))
print(&quot;Operações&quot;)
print(&quot;1:adição&quot;)
print(&quot;2:subtração&quot;)
print(&quot;3:multiplicação&quot;)
print(&quot;4:divisão&quot;)
operacao = input(&quot;Escolha uma operação: &quot;)
if (operacao == &quot;1&quot;):
resultado = num1 + num2
print(resultado)
elif (operacao == &quot;2&quot;):
resultado = num1 - num2
print(resultado)
elif (operacao == &quot;3&quot;):
resultado = num1 * num2
print(resultado)
elif (operacao == &quot;4&quot;):
resultado = num1 / num2
if (num2 != 0):
print(resultado)
else:
print(&quot;erro: número é zero&quot;)
else:
print(&quot;números inválidos&quot;)
