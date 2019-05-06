# prjekt

def pobierz_dane(liczba_cyfr):
    lista=[]
    for i in range(liczba_cyfr):
        podaj=int(input("Podaj cyfry: "))
        lista.append(podaj)
    return lista
nliczb=int(input("podaj z ilu cyf ma sie skladac lista: "))
wynik=pobierz_dane(nliczb)
print(wynik)

def parzysta(liczba):
    if liczba%2==0:
        return "prawda"
    else:
        return "fałsz"

for i in wynik:
    print(parzysta(i))
