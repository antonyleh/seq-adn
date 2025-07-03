### Introduction du Projet : Analyse de Séquences ADN en Programmation Fonctionnelle

Ce projet a pour objectif de manipuler et d'analyser des séquences d'ADN en utilisant la programmation fonctionnelle en OCaml. Les séquences d'ADN, composées de quatre bases nucléiques (cytosine, guanine, adénine, thymine), codent les protéines nécessaires aux activités biochimiques des cellules. Le projet se divise en plusieurs parties, dont l'extraction de gènes à partir de brins d'ADN, le calcul de séquences consensus, et l'utilisation d'expressions régulières pour l'analyse de données génomiques.


## Installation d'`opam`

Pour commencer, installez le gestionnaire de paquets [`opam`](https://opam.ocaml.org/) en suivant les instructions données [ici](https://opam.ocaml.org/doc/Install.html).

## Installation des paquets

Placez-vous dans le répertoire cloné.
De là, exécutez la commande suivante, qui crée un switch `opam` local en y installation les paquets nécessaires :

```
opam switch create . -y --deps-only
```

## Compilation

Pour compiler le projet, exécutez la commande `make`.

## Toplevel

Afin de vous-même tester et déboguer, vous pouvez utiliser le toplevel `utop` qui a été installé.
Pour le lancer, exécutez la commande `make top`.

## Tests

**Tous les tests n'ont pas encore été publiés.**
Pour lancer tous les tests disponibles, exécutez `make test`.
Pour tester seulement les fonctions de l'exercice *i*, exécutez `make test-i`.

## Auteur 
Antony Lehmann


