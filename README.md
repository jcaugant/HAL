Vérif doublons Aurehal.ipynb
Ce script a pour fonction de calculer la volumétrie des doublons en lien avec AureHAL. 
Cela peut être utile pour les gestionnaires qui travaillent avec un grand nombre de laboratoires.
Avant de lancer ce script, il convient d'effectuer l'opération suivante :
- création un fichier .txt appelé "liste.txt" (il est possible de le faire directement dans Jupyter)
- ajouter l'acronyme des labos dont vous souhaitez controler la présence ou non de doublons. A chaque acronyme, faites un retour à la ligne
- une fois cela fait, enregistrer votre fichier " liste.txt "
- lancer ensuite votre script

Pour chaque acronyme, le nombre d'occurence apparaitra : s'il n'y en a qu'une, c'est que l'acronyme ne possède pas de doublons.
Si le résultat est supérieur à 1, c'est donc qu'il y a des doublons et qu'il convient de controler via AureHAL les doublons en question.

Ce script en est pour le moment à sa version Alpha, je vais tenter de l'améliorer, merci d'être indulgent :)
