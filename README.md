a = float(input("Digite o valor do lado a: "))
b = float(input("Digite o valor do lado b: "))
c = float(input("Digite o valor do lado c: "))

if a + b > c and a + c > b and b + c > a:
   
    if a == b and b == c:
        print(f"Os lados {a}, {b} e {c} formam um triângulo Equilátero.")
    else:
        if a == b or a == c or b == c:
            print(f"Os lados {a}, {b} e {c} formam um triângulo Isósceles.")
        else:
            print(f"Os lados {a}, {b} e {c} formam um triângulo Escaleno.")
else:
    print(f"Os lados {a}, {b} e {c} não podem formar um triângulo.")
