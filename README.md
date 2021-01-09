Projet qui a pour but de comparer les estimations de pi réaliser avec Numpy et Spark

Afin de lancer la comparaison :
- Ouvrir le terminal 
- Se placer dans le bon répertoire 
- Taper `./comp.py`

Si cela, ne fonctionne pas, veillez à rendre le script comp exécutable, pour cela : 
- `chmod +x comp.py`

Ensuite recommencer la dernière étape

Comparaison des résultats :

| n=100000          | numpy    | spark   |
|-------------------|----------|---------|
| temps d'exécution | 0.03648  | 1.41378 |
| valeur de pi      | 3.150880 | 3.147760 |
| Ecart             | 0.2956         | 0.1963        |
 
Si l'on passe à une estimation avec 1000000 d'itérations, nous observons une plus grande précision de pi pour les deux méthodes, mais nous remarquons que le temps d'exécution augmente plus significativement pour la méthode numpy, alors que la méthode spark a un temps d'exécution à peine plus élevé.
