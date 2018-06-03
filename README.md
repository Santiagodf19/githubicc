# githubicc Trabajo de cachimbos de la utec
frase=str(input("Ingrese la frase: "))
print(len(frase))
print()
c=0
for i in (frase):
    if i=="a" or i=="e" or i=="i" or i=="o" or i=="u":
        c=c+1
print(c)
print()
for i in range(len(frase)-1,-1,-1):
        print(frase[i], end="")
