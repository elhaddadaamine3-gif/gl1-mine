
import random
import string

# Liste de toutes les lettres majuscules et minuscules
letters = string.ascii_letters

# Initialisation de la lettre choisie
c = "" 

# Boucle jusqu'à ce que la lettre 'w' soit choisie
while c != "w":
    c = random.choice(letters)  # Choix aléatoire d'une lettre
    print(f"La lettre choisie est {c}")  # Affichage de la lettre
