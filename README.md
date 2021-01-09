Projet qui a pour but de comparer les estimations de pi réaliser avec Numpy et Spark

Afin de lancer la comparaison :
- Ouvrir le terminal 
- Se placer dans le bon répertoire 
- Taper `./comp.py`

Si cela, ne fonctionne pas, veillez à rendre le script comp exécutable, pour cela : 
- `chmod +x comp.py`

Ensuite recommencer la dernière étape

Comparaison des résultats :

| n=100000 | numpy | spark | |----------|:-------------:|------:| | tps d'exécution | 0.0367 | 2.6760 | |----------|:-------------:|------:| | valeur de pi | 3.144320 | 3.13920 |
 
