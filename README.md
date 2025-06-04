# Python-2.0

# Leia seu nome e a sua idade

nome= input("digite seu nome:")
ano_nascimento= int(input("digite seu ano de nascimento:"))
idade= 2025-ano_nascimento

print(f"seu nome é {nome} e a sua idade é {idade} anos.")

# Média da sua nota 

nota1 = float(input("digite a primeira nota:"))
nota2 = float(input("digite a segunda nota:"))
nota3 = float(input("digite a terceira nota:"))
media = (nota1*2+nota2*3+nota3*5)/10
print(f"a média é {media}")

# Gasto de combustivel 

distancia = float(input("digite a distancia percorrida em km:"))
consumo = float(input("digite o consumo do veículo em km/l:"))
preco = float(input("digite o preço do combustível em R$/l:"))
gasto = (distancia/consumo)*preco
print(f"o gasto em combustível é de R${gasto}")

# Tempo para baixar um arquivo 

horas = float(input("digite o tempo em horas:"))
minutos = float(input("digite o tempo em minutos:"))
segundos = float(input("digite o tempo em segundos:"))
mb = float(input("digite o tamanho do arquivo em MB:"))
velocidade = float(input("digite a velocidade da conexão em MB/s:"))
tempo = (mb/velocidade)*3600
print(f"o tempo necessário para baixar o arquivo é de {tempo} segundos")


