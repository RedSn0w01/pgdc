# utilisation.py
from fct58 import gdc

a = int(input("Entrez le premier entier strictement positif : "))
b = int(input("Entrez le deuxième entier strictement positif : "))

if a <= 0 or b <= 0:
        print("Veuillez entrer des entiers strictement positifs.")
else:
    resultat_gdc = gdc(a, b)
    print(f"Le plus grand diviseur commun de {a} et {b} est : {resultat_gdc}")
