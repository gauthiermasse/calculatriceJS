Salut cher correcteur,

Tu trouveras les 3 petites fonctions de préchauffe: 

- une fonction my_max() qui prend une array et qui retourne le nombre maximum 
=> je crée une boucle for qui balaye toutes les données du tableau entré, en mettant à jour au fur et à mesure la valeur max, que j'affiche à la fin

- une fonction vowel_count() qui prend un string et qui retourne le nombre de voyelles
=> je crée une boucle qui balaye le tableau contenant toutes les lettres du texte entré, dans laquelle une autre boucle balaye chaque voyelle du tableau vowels, si les 2 lettres sont égales je compte une voyelle en plus dans la variable nb, que j'affiche à la fin

- une fonction reverse() qui prend un string et qui renvoie les caractères en position inverse. 
=>2 méthodes: 
	1=> avec une boucle: après avoir décomposé le texte en lettres distinctes dans un tableau, on balaye toutes ces lettres pour les replacer dans l'ordre inverse dans la variable newtext qu'on affiche à la fin
	2=> on m'a expliqué après que c'était possible directement avec la fonction .reverse, la flemme était meilleure conseillère


La calculette: https://cdn.rawgit.com/gauthiermasse/calculatriceJS/d9c3f169/calculette.html
Je crée un array qui stocke les valeurs tapées par le user, il suffit ensuite de les joindre et d'utiliser la fonction eval qui interprète un string composé de chiffres et d'opérateurs et est capable de le calculer. DOnc pas besoin des fonctions de calculs, que j'ai quand même laissé (ce coup ci la flemme a bien marché)!