# Teste-Triangulo-Python

la = int(input("Digite o lado A: "))
lb = int(input("Digite o lado B: "))
lc = int(input("Digite o lado C: "))

if ((la + lb >lc) and (la + lc >lb) and (lc + lb > la)) >0:
    if (la==lb) or (la==lc):
        print("Equilatero")
    elif la!=lb and la!=lc and lb!=lc:
        print("Escaleno")
    else:
        print("Isosceles")
else:
    print("Não é um triângulo")
