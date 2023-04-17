Trabalho sobre Controle de decisão

Autor: Herbert Schildt
Nome do livro: Java para iniciantes 6° edição, Crie, compile, execute programas Java rapidamente
Capitulo 3: Intruções de controle de programa
Página: 67

Código em Python: 

resp = 5

print("Adivinhe a letra uma letra de 0 a 10 \n")

num = int(input("Digite o número que você acha que é: \n"))

if(num == resp):
  print(f'\n Você está certo a resposta é: {resp}')

elif(num != resp):
  if(num <= 4):
    print("\n Você está longe, muito baixo, tente de novo")

  elif(num >= 6):
    print("\n Você está longe, muito alto, tente de novo")