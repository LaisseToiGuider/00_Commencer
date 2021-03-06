![Allura - UI Windows](https://user-images.githubusercontent.com/107787061/174484834-95f8fb5b-dd6a-4aae-9fb1-33813a243090.png)

## Les langages

Comme tu l'as vu à l'étape précédente, nous avons utilisé une certaine syntaxe pour exprimer ce que nous voulons faire faire à l'ordinateur.

```
var prix = 5;
```

> On appelle application ou app un programme informatique que tu utilises sur ton ordinateur ou smartphone.

Il existe de nombreux langages. Je vais t'apprendre à utiliser le langage C# qui se prononce 'C-Sharp'. Pourquoi ce choix ? C'est un langage assez universel qui permet de faire tout type d'application : des applications avec des dessins, des sites web, des app Android ou iPhone, des jeux vidéo...

Les outils avancés pour écrire des applications C# sont gratuits, la documentation très complète est en français.

Enfin la communauté francophone est assez importante, une grosse communauté c'est l'assurance de trouver plus facilement une réponse à une question que tu te poses.

## La grammaire

La grammaire représente les règles d'écriture.

## Mots-clés

Les mots-clés sont des mots réservés. Ils servent à pouvoir transformer ce que tu écris en code assembleur.

```
var
```

Par exemple var signifie réserver de l'espace mémoire.

## Exemple de programme sur cahier

Imaginons que nous ayons un cahier constitué de pages et 25 lignes par page. Je veux donner des instructions pour calculer le prix TTC en partant d'un prix hors taxes, d'une quantité et d'un taux de TVA.

### Avec une grammaire que j'invente cela pourrait donner.

```
écrire page 2 ligne 1 le nombre de tomates en stock
écrire page 2 ligne 2 le prix des tomates hors taxe
écrire page 2 ligne 3 le taux de TVA
prendre la valeur de la page 2 ligne 1 et la multiplier par la valeur de page 2 ligne 2, écrire la réponse page 2 ligne 10
prendre la valeur de la page 2 ligne 10 et la multiplier par la valeur de page 2 ligne 3 puis la diviser par 100, écrire la réponse page 2 ligne 11
prendre la valeur de la page 2 ligne 10 et ajouter la valeur de page 2 ligne 11, écrire la réponse page 2 ligne 12
afficher "le stock de tomate TTC est valorisé à " puis la valeur de la page 2 ligne 12
```

Vous avez compris assez vite cette grammaire. Les instructions permettent de faire le calcul et de l'afficher.

## Grammaire C#

```
var quantiteTomate = 5;
```

var est un diminutif de variable. quantiteTomate est le nom de cette variable. Ici la gestion de l'emplacement mémoire est masquée et automatique, tu n'as pas à t'en soucier.

Le nom de la variable ne peut pas contenir d'espace mais peut contenir majuscules, minuscules, tiret bas, chiffre mais pas en premier caractère. En C# tu peux utiliser les accents, ce n'est pas toujours possible dans d'autres langages.

Les majuscules et minuscules sont importantes, quantite ce n'est pas la même chose que Quantite. On dit que c'est [sensible à la casse](https://fr.wikipedia.org/wiki/Sensibilit%C3%A9_%C3%A0_la_casse).

Le point-virgule est un séparateur d'instruction. Tu peux donc mettre plusieurs instructions sur la même ligne.

Le séparateur décimal est le point.

```
var prix_HT = 4.5; var TVA = 5.5;
```

## Les grammaires les plus connues

Dans la liste des grammaires ou langages tu as peut-être entendu parler de Python, Java, Javascript, PHP, C, C++, Basic... Il en existe des milliers avec chacun ses particularités.

> Si tu veux continuer avec un autre langage tu peux le faire, je vais continuer avec des exemples en C#

Le langage Python masque la notion de type (typage dynamique) et je pense que c'est plus compliqué pour toi bien comprendre cette notion. Si tu veux faire du Python je te conseille de commencer le TP en C# puis le refaire en Python.

## Préparons ton espace de travail

Assez parlé, il est temps de passer au concret et de voir comment obtenir de l'aide.

[Étape 4 les outils](04_Outils.md)
