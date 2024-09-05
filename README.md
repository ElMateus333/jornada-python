# jornada-python
minha jornada no universo de python
# calculos de circunferencia
raio = float(input("Digite o valor do raio: "))

pi = 3.14159 

circunferencia = 2 * pi * raio

print("A circunferência do círculo é: {circunferencia:.2f}")
# Converter real em dolar
n1 = float(input("quantos reais voce tem? R$"))

n2 = n1 / 5.23

print("você pode comprar {:.2f} dolares".format(n2))
# Calculo de media
n1 = float(input("Digite sua nota: "))

n2 = float(input("Digite mais uma nota: "))

m = (n1 + n2)/2

print("Sua media foi {:.2f}".format((m)))

if m >= 6:

    print("Você passou")
else:

    print("Você reprovou")
# radar de velocidade e multa
velocidade = float(input("Qual a velocidade o veiculo atingiu? "))

n1 = velocidade - 80

n2 = n1 * 7

if velocidade > 80:

    print("Você foi multado") 
    
    print("o valor da multa será R${:.2f} por causa de {:.0f}km/h a mais que o permitido ".format(n2 , n1))
    
else:

    print("continue sendo um bom cidadão")
# Calculo de ano bissexto
ano = int(input("Digite um ano com 4 digitos: "))

if ano % 4 == 0 and ano % 100 != 0 or ano % 400 == 0:

    print("Esse é um ano bissexto")
    
else:

    print("Esse é um ano normal")
# Verificando se forma um triangulo
n1 = float(input("Primeiro segmento:"))

n2 = float(input("segundo segmento:"))

n3 = float(input("terceiro segmento:"))

if n1 > n2 + n3 and n2 < n1 + n3 and n3 < n1 + n2:

    print("podem formar um triangulo")
    
else:

    print("Não podem formar um triangulo")
# PROJETO PESSOAL DE SISTEMA DE EU NUNCA
    
    from random import choice
lista = [

    "Eu nunca virei a noite vendo anime",
    "Eu nunca chorei por um personagem de anime",
    "Eu nunca me apaixonei por um personagem de anime",
    "Eu nunca criei fanfic",
    "Eu nunca comprei coisas de anime"
    "Eu nunca maratonei uma série de ficção científica",
    "Eu nunca me vesti como um personagem de filme ou anime",
    "Eu nunca fiquei até tarde jogando videogame",
    "Eu nunca escrevi teorias sobre filmes de super-heróis",
    "Eu nunca joguei RPG de mesa com amigos",
    "Eu nunca colecionei quadrinhos",
    "Eu nunca fiquei obcecado por um universo cinematográfico",
    "Eu nunca aprendi uma língua fictícia, tipo Elfico ou Klingon",
    "Eu nunca participei de um fórum de discussão sobre filmes ou séries",
    "Eu nunca desenhei fanart de um personagem que gosto",
    "Eu nunca discuti quem é o melhor super-herói",
    "Eu nunca fiquei na fila para a estreia de um filme de franquia famosa",
    "Eu nunca comprei uma action figure de um personagem",
    "Eu nunca tive um pôster de anime ou série no quarto",
    "Eu nunca joguei cartas colecionáveis como Magic ou Yu-Gi-Oh",
    "Eu nunca tive uma discussão sobre Star Wars vs. Star Trek",
    "Eu nunca assisti a um filme ou anime legendado em vez de dublado",
    "Eu nunca fui a um evento de cultura geek, como Comic Con",
    "Eu nunca zerei um jogo 100% para desbloquear todos os troféus ou conquistas",
    "Eu nunca criei uma playlist com trilhas sonoras de filmes, séries ou jogos",
    
]

en = choice(lista)

print(en)

# PROJETO PESSOAL, ADIVINHE O PERSONAGEM DA BIBLIA
from random import choice

dificuldade = int(input("Selecione a dificuldade: 1 para fácil, 2 para médio, 3 para difícil: "))

facil = [

    "Adão",
    "Eva",
    "Noé",
    "Abraão",
    "Moisés",
    "Davi",
    "Salomão",
    "Sansão",
    "Josué",
    "Elias",
    "Isaías",
    "Jeremias",
    "Maria",
    "José",
    "João Batista",
    "Pedro",
    "Paulo",
    "Judas Iscariotes",
    "Jesus",
    "Lázaro",
]

medio = [

    "Abigail",
    "Balaão",
    "Barnabé",
    "Boaz",
    "Débora",
    "Enoque",
    "Esaú",
    "Estêvão",
    "Filemom",
    "Geazi",
    "Habacuque",
    "Jael",
    "Jetro",
    "Jonas",
    "Lia",
    "Melquisedeque",
    "Mical",
    "Onésimo",
    "Raabe",
    "Zaqueu",
]

dificil = [

    "Abimeleque",
    "Agur",
    "Ananias",
    "Asael",
    "Basemate",
    "Bezalel",
    "Chulda",
    "Diná",
    "Dorcas",
    "Ehud",
    "Eliseu",
    "Gomer",
    "Hulda",
    "Icabode",
    "Jedidias",
    "Lo-Debar",
    "Mefibosete",
    "Naás",
    "Priscila",
    "Quedorlaomer",
]


if dificuldade == 1:

    print(choice(facil))
elif dificuldade == 2:

    print(choice(medio))
elif dificuldade == 3:

    print(choice(dificil))
else:

    print("Dificuldade inválida. Selecione 1, 2 ou 3.")
