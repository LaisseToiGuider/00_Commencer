## Comment fonctionne un ordinateur ?

![02_schemat](https://user-images.githubusercontent.com/107787061/174472468-b0d22d9b-0b2f-40b0-a185-e10c5c43c65e.png)

Un ordinateur est constitué au minimum de 3 éléments
- Une mémoire de stockage (en noir). Cela fonctionne comme un cahier, plus tu as de pages plus tu peux y mettre de choses. Dans cette mémoire on y trouve les instructions et on y stocke les résultats.
- Une mémoire de travail (en vert). C'est l'endroit où l'ordinateur fait ses calculs. C'est comparable à ta feuille de brouillons si tu dois faire des calculs sans calculatrice, tu y poses toutes tes opérations et tu mets le résultat dans ton cahier.
- Une horloge (en rouge). Elle cadence le fonctionnement de l'ordinateur, nous n'en parlerons plus mais elle est bien présente.


Ce n'est pas plus compliqué que cela.

## Les bons termes à connaître

L'ordinateur ne connaît que les Zéro et les Un. On appelle cela des bits.

Comme tu as dû voir dans la vidéo "C'est pas sorcier" on regroupe les bits par 8 cela donne des octets. Ce sont des valeurs binaires.

La mémoire de travail, celle où sont effectués les calculs, s'appelle le registre.

La mémoire de stockage s'appelle la RAM (Random Access Memory) et elle s'efface dès qu'elle n'a plus de courant.

Le microprocesseur à besoin de tout cela pour réussir à exécuter des instructions.


## Comment programmer un ordinateur ?

Celui qui met au point le microprocesseur décide des instructions.

![intel4004](https://user-images.githubusercontent.com/107787061/174473419-284fa517-e6ce-495b-880d-64bbc5419694.jpeg)


Par exemple il va décider que le code 00000001 veut dire additionner registre A + registre B et mettre la réponse dans le registre C.

Comme tu le vois c'est assez compliqué de travailler en binaire et travailler avec les registres.

Rassure-toi, on a inventé des langues et des grammaires bien plus simples.

## Premier exemple

```
1  var prix = 5;
2  var quantite = 6;
3  var valeur = prix * quantite;
4  Console.WriteLine(valeur);
```

Ligne 1 on indique que l'on va utiliser un espace mémoire appelé "prix" pour y stocker la valeur 5.

Ligne 2 on indique que l'on va utiliser un autre espace mémoire appelé "quantité" (sans accents) pour y stocker la valeur 6.

Ligne 3 on indique que l'on va utiliser un autre espace mémoire appelé "valeur". On utilise les capacités de calcul de microprocesseur pour multiplier prix par quantité et stocker le résultat dans l'espace mémoire "valeur".

Ligne 4 on utilise une fonction pour afficher à l'écran ce que contient "valeur".

## A toi de jouer

![02_cap1](https://user-images.githubusercontent.com/107787061/174474388-bb6a4e4f-6881-44c4-88cd-ffa92c469453.png)

[Va sur ce lien](https://dotnetfiddle.net/YRT6wD), tu vas retrouver cet exemple.

Appuie sur le bouton "Run" tout en haut pour demander à démarrer le programme.

Tu dois voir la réponse 30

Change la quantité pour mettre 7 puis "Run". Obtiens-tu 35 ?

## Que se passe-t-il quand tu appuies sur "Run" ?

L'interpréteur va analyser le texte et le transformer en instructions binaires, aussi appelé en code assembleur. C'est la seule langue que comprend le microprocesseur.

## Prochaine étape : les langues.

## Si tu veux voir à quoi ressemble le code assembleur

Réservé aux grands curieux, tu peux voir à quoi ressemble le code assembleur [sur ce site.](https://sharplab.io/)
![2022-06-19 15_25_23-SharpLab](https://user-images.githubusercontent.com/107787061/174483335-daed28f1-65d0-4f11-8504-3a190ca3b685.png)

