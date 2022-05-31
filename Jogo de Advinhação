from random import randint

#Programa Principal
computador = randint(0,10)
soma= 0
print('Sou seu computador...')
print('Acabei de pensar em um número entre 0 e 10.')
print('Será que você consegue advinhar qual foi ?')

acertou = False
while not acertou:
    palpite = int(input('Qual é o seu palpite ?'))
    soma+=1
    if palpite == computador:
        acertou= True
    else:
        if palpite < computador:
            print('Mais...tente mais uma vez')
        elif palpite > computador:
            print('Menos...tente mais uma vez')
print('Acertou com {} tentativas. Parabéns!'.format(soma))
