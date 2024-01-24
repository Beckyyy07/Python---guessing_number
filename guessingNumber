import random

#O usuário entrará com dois números possíveis para limitar a busca
min_num = int(input('Digite um número mínimo: '))
max_num = int(input('Digite um número máximo: '))
random = random.randint(min_num, max_num)
count = 5

#No bloco lógico, a estrutura while fará o loop do código
while True:
    print(f'O seu número é maior ou menor do que: {random} ?')
    alternativa = input('Maior / Menor / É o meu número\n')
    #No primeiro IF, caso a condição seja atendida, irá somar o numero aleatorio + o próprio e o contador
    if (alternativa == 'Maior'):
        random = random + count
        count -= 1
        if (count == 0):
            count = 5
    #Caso atenda a condição 'menor', procedimento será inverso, subtrairá o numero aleatorio - o contador        
    elif (alternativa == 'Menor'):
        random = random - count
        count -= 1
        if (count == 0):
            count = 5
    #Se o seu número for atendido, o loop se encerrará e o programa efetuará uma pausa forçada
    elif (alternativa == 'É o meu número'):
        print('Parabéns! Se quiser jogar de novo, rode o código mais uma vez.')
        break
    else:
        print(
            'Infelizmente você não acertou! Mas não fique triste, tente novamente.'
        )
