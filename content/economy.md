---
layout: post
title: Economie
categories: plugins
---

# Fonctionnement de l'économie

Système très hasardeux, on risque de se retrouver avec des prix ridicules et une monnaie qui ne vaut plus rien, mais essayons...
La monnaie est basée sur le diamant. Le bloc de référence est le bloc de minerai de diamant (obtenu avec silk touch), qui vaut 1$.
Pour convertir vos diamants en $ et vice-versa, dirigez vous vers un des stands de l'Organisation disponible dans chaque ville reconnue du jeu.

Chaque joueur commence avec 1$ (richesse, vous voilà).

# Economie

- `/money` : voir votre argent
- `/money <joueur>` : voir l'argent de *joueur*
- `/pay <joueur> <somme>` : donner *somme* d'argent à *joueur*
- `/balancetop` : voir le classement des joueurs les plus riches

# QuickShop

Commandes utilisateur
- `/qs find <item>` : trouves tous les shop vendant des *item*s proches de vous

Commandes de création/édition de shop
- `/qs create <prix> <item> <quantité>` : en regardant un coffre, crée un shop de vente d'*item* pour *prix* les *quantité* items
- `/qs sell` : en regardant un shop, en fait un magasin de vente
- `/qs buy` : en regardant un shop, en fait un magasin d'achat
- `/qs price <prix>` : en regardant un shop, change le prix du shop en *prix*
- `/qs item` : en regardant un shop, change son type d'item en ce que vous tenez en main