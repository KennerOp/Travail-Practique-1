# Auteurs: Stanley, Laurent-Charles, Ajathan, Jeff
# Date: 2017/02/14
# Un jeu de coffre-fort où il faut déviner les trois chiffres pour pouvoir l'ouvrir

#Python va trouver la librairie "random", qui permet d'avoir des données aléatoires
#car ce n'est pas démarré avec le démarrage de Python
#Les trois variables vont prendre des valeurs aléatoires entre 100 jusqu'à 999 car
#1000 est exclu de la liste.
import random
premier_chiffre = random.randrange(100,1000)
deuxième_chiffre = random.randrange(100,1000)
troisième_chiffre = random.randrange(100,1000)


numero_de_tentative = 0

print("Veuillez taper uniquement des numéros pour les chiffres de trois digits du coffre-fort")
entrée_pour_chiffre_1 = int(input(end=""))
print("-", end="")
entrée_pour_chiffre_2 = int(input())
print("-", end="")
entrée_pour_chiffre_3 = int(input())


