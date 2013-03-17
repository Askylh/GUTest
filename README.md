GUTest
======

Gambas Unit Test

Voila le principe:

Pendant le développement on rajoute l'unité GUTest(Gambas Unit Test), 
elle contient l'ihm pour les tests, et le code propre à l'ihm.

On rajoute GUTEST.show dans le open de la form principale(/ex, ou ouverture par un btn dédié...)

On crée une classe (test.class) dans lequel les fonctions de test seront écrites par le dev et qui appelle les procédures et fonctions du prog principal, le résult de la fonction étant fonction du bon déroulement du test.

Dans l'IHM de GUTest, un treeview permet de lister et lier les F° du prog principal et les fonctions de test associées qui sont décrites dans test.module (vraisemblablement par analyse du code).

Le déroulement du test consiste à lancer tout ou en partie l'arbre de test, cad pour chaque ligne du treeview la fonction décrite dans module.test.
