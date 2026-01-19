# Crei um programa que ler duas notas entre 0 a 10 de um aluno e calcula sua média, mostrando uma mensagem no final, de acordo com a média atingida.

nota1 = float(input("Digite a 1ª nota: "))
nota2 = float(input("Digite a 2ª nota: "))
media = (nota1+nota2)/2

if media < 5:
    print(f"\nREPROVADO com média: {media:.1f}")
elif media < 7:
    print(f"\nRECUPERAÇÃO com média: {media:.1f}")
else:
    print(f"\nAPROVADO com média: {media:.1f}")
