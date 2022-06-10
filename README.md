# SQL_introduction

## Exercice Requetes SQL
Entrez le code suivant dans le cadre gauche de https://sqlize.online/ :
```
CREATE TABLE IF NOT EXISTS `users` (
  `id` INT PRIMARY KEY NOT NULL AUTO_INCREMENT,
  `firstname` varchar(200) NOT NULL,
  `lastname` varchar(200) NOT NULL,
  `age` int unsigned NOT NULL
) DEFAULT CHARSET=utf8;

INSERT INTO `users` (`firstname`, `lastname`, `age`) VALUES
  ('ada', 'lovelace', 36),
  ('grace', 'hopper', 85),
  ('nicole-Reine', 'lepaute', 65),
  ('maria', 'mitchell', 70);
```

A la suite, ecrivez des requetes SQL (les requetes devront etre sauvegardée dans un fichier)
pour afficher :

* toutes les colonnes de la table users
* tout les prenoms de la table users
* toute les noms et prenoms de la table users, limiter le resultat à 2 lignes
* toutes les colonnes dont l'age est supérieur à 65
* toutes les colonnes dont l'age est compris entre 60 et 80
* toutes les colonnes classées par age en ordre croissant
* toutes les colonnes classées par age en ordre décroissant
* tout les noms commençant par la lettre l
* tout les prenoms qui ne contiennent pas la lettre a
* ajouter meg whitman 55 ans à la table users
* modifier l'age de meg whitman à 65
* toute les colonne du user meg whitman
* supprimer meg whitman
