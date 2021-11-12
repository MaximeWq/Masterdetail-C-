# Masterdetail-C-sharp

Projet de 1ère année de DUT informatique réalisé en C# et en XAML.

Description:

Notre projet est composé d'une liste des créatures du jeu Minecraft à gauche de la fenêtre.
On a en haut à gauche 3 boutons et une combobox permettant d'appliquer des filtres à notre liste.
La créature est affichée au centre de la fenêtre.
On a un bouton "connexion" qui permet de se connecter à un compte ou de créer un compte et un bouton de déconnexion et haut à droite.
On a une barre de recherche en dessous (non fonctionnelle faute de temps).
Encore en dessous, on a un bouton "favoris" qui permet d'afficher une fenêtre avec la liste des créatures en favoris.
On a enfin un autre bouton, sous le bouton de favoris qui permet d'ajouter la créature sélectionnée dans la liste à la liste de favoris.
La barre de recherche n'est pas fonctionnelle, nous n'avons pas eu le temps de l'incorporer au projet comme prévu même si la méthode 
correspondante fonctionne.

Lancer l'application:

Le fichier "projet_mc_Setup.msi" permet d'installer l'application.
Pour que les éléments utilisant de la persistance (ajout / suppression de favoris et création de comptes) fonctionnent, il faut démarrer 
l'application en tant qu'administrateur.

Description du fonctionnement de l'application:

Pour filtrer la liste, il faut double cliquer sur les boutons en haut à gauche et les éléments de la combobox juste en dessous.
On obtient les détails des créatures en cliquant dessus.
Pour ajouter / consulter / supprimer des favoris, il faut se connecter à l'aide du bouton "connexion".
Une fois connecté on peut ajouter des créatures à la liste de favoris en cliquant sur le bouton en forme de coeur.
On peut consulter la liste en cliquant sur le bouton "favoris".
Dans la fenêtre d'affichage des favoris, on peut ajouter un commentaire à une créatures en utilisant le bouton "Ajouter commentaire".
On peut également retourner sur la fenêtre pricipal sans rien modifier avec le bouton "retour liste".
En appuyant sur le coeur dans la fenêtre d'affichage des favoris, on supprime le favoris de la liste.
