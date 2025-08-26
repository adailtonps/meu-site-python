#mensagem de boas vindas e cardápio para o cliente
def realce ():
    print('|', '-' * 57, '|')
realce()
print('   SEJA BEM-VINDO A LOJA DE MARMITAS DO ADAILTON PEREIRA :)')
realce()
print('                         CARDÁPIO ')
realce()
print('|  TAMANHO  |   BIFE ACEBOLADO (BA) |   FILÉ DE FRANGO (FF) |')
print('|    P      |        R$ 16.00       |       R$ 15.00        |')
print('|    M      |        R$ 18.00       |       R$ 17.00        |')
print('|    G      |        R$ 22.00       |       R$ 21.00        |')
realce()

#variável que irá acumular os valores dos pedidos
valor = 0

#estruturas de repetição dos sabores, tamanhos e prints do que foi pedido e o valor
while True:
    while True: #Enquanto o usúario não digitar BA ou FF, o programa não continua
      sabor = input(f'Entre com o sabor desejado (BA/FF): ').upper()
      if sabor == 'BA' or sabor == 'FF':
          break
      else:
         print('Sabor inválido. Tente novamente.')
         print('                                                           ')

    while True: #Enquanto o usuário não digitar um dos tamanhos disponíveis, o programa não continua
      tamanho_marmita = input('Entre com o tamanho desejado (P/M/G): ').upper()
      if tamanho_marmita == 'P' or tamanho_marmita == 'M' or tamanho_marmita == 'G':
          break
      else:
          print('Tamanho inválido. Tente novamente.')

#Aqui é onde o valor é somado dependendo do sabor e tamanho escolhido pelo usuário
    if sabor == 'BA':
        if tamanho_marmita == 'P':
            valor += 16.00
            print(f'Você pediu um Bife Acebolado no tamanho P: R$ 16.00')
        elif tamanho_marmita == 'M':
            valor += 18.00
            print(f'Você pediu um Bife Acebolado no tamanho M: R$ 18.00')
        elif tamanho_marmita == 'G':
            valor += 22.00
            print(f'Você pediu um Bife Acebolado no tamanho G: R$ 22.00')
    elif sabor == 'FF':
        if tamanho_marmita == 'P':
                valor += 15.00
                print(f'Você pediu um Filé de Frango no tamanho P: R$ 15.00')
        elif tamanho_marmita == 'M':
                valor += 17.00
                print(f'Você pediu um Filé de Frango no tamanho M: R$ 17.00')
        elif tamanho_marmita == 'G':
                valor += 21.00
                print(f'Você pediu um Filé de Frango no tamanho G: R$ 21.00')
    print('                                                           ')

    #input perguntando se deseja mais alguma coisa
    repetir_tudo = input('Deseja pedir mais alguma coisa? (S/N): ').upper()
    if repetir_tudo == 'S':
     continue
    else:
     break
     
  #print com o valor final de tudo
print(f'O valor total a pagar é: R$ {valor}')
print('OBRIGADO PELA PREFERÊNCIA, VOLTE SEMPRE! :)')
