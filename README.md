# Jogos-
Projetos divertido 
import random

numero_secreto = random.randint(1, 10)

print("🎮 Jogo de Adivinhação!")
print("Tente acertar o número entre 1 e 10")

tentativa = 0

while tentativa != numero_secreto:
    tentativa = int(input("Digite seu palpite: "))

    if tentativa != numero_secreto:
        print("❌ Errado, tente novamente!")

print("🎉 Parabéns! Você acertou!")
