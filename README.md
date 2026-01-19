# 50-dias-de-código

nota1 = float(input("Digite a 1ª nota: "))
nota2 = float(input("Digite a 2ª nota: "))
media = (nota1+nota2)/2

if media < 5:
    print(f"\nREPROVADO com média: {media:.1f}")
elif media < 7:
    print(f"\nRECUPERAÇÃO com média: {media:.1f}")
else:
    print(f"\nAPROVADO com média: {media:.1f}")
