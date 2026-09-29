 Sistema de Notas do Aluno

Programa desenvolvido em Python para calcular a média de duas notas e informar se o aluno foi aprovado ou reprovado.

 Tecnologias utilizadas

 Python 3

Instalação e demonstração

Instale o Python 3.

Baixe ou clone este repositório.

Abra o terminal na pasta do projeto.

Execute o arquivo main.py:

python main.py

Código
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2


print("=== Sistema de notas do aluno ===")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Aprovado")
else:
    print("Reprovado")

Exemplo de uso
=== Sistema de notas do aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 7

A média final é: 7.50
Aprovado

Regra de aprovação
Média	Resultado
>= 7.0	✅ Aprovado
< 7.0	❌ Reprovado
👨‍💻 Autor

Seu Nome


**campo do código**

````markdown
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2


print("=== Sistema de notas do aluno ===")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Aprovado")
else:
    print("Reprovado")



