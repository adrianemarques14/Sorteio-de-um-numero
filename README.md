import random
print('Hum, diga o número em que estou pensando entre 0 e 5...')
lista = [0, 1, 2, 3, 4, 5]
escolhido = random.choice(lista)
num = int(input('Digite o número que você acha que é: '))
if num == escolhido:
    print('Parabéns! Você acertou')
else:
    print('Você errou. O número correto era {}'.format(escolhido))
