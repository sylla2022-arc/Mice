En traitement de données, nous sommes souvent confrontés à un problème de qualité de données surtout quand cela concerne les valeurs manquantes.

Alors quel comportement adopté face à cela ?  Les bonnes pratiques constituent à :
* Identifier ces valeurs manquantes (colonnes, taux de nan, etc.)
* Comprendre la nature de ces valeurs manquantes (hasard ou non)
* Evaluer l’impact de ces valeurs manquantes (à supprimer ou à traiter ou à ignorer)

Dans le cas où les valeurs manquantes sont imputables MICE peut très bien nous faciliter la tâche. Cette méthode puissante est une approche itérative d’imputation de valeurs manquantes.

Contrairement à l’imputation par la médiane, mode, …, MICE s’appuie partiellement sur les relations entre variables du tableau. Ce qui rend plus précises ses estimations en termes de convergence. 

Quelques conditions sur MICE pour augmenter la fiabilité :

*  Pas de forte linéarité ou non linéarité entre les variables (à vérifier avec pairplot(), etc. )  
*  Pas de taux très élevé de valeurs manquantes
