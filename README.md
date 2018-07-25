# 
# Projet 3 -  SimpleTweet 

 SimpleTweet  est une application Android qui permet à un utilisateur de consulter son calendrier Twitter et poster un nouveau tweet. L'application utilise [Twitter REST API] (https://developer.twitter.com/fr/docs/api-reference-index).

Temps passé:  72 heures passées au total

## Histoires d'utilisateurs

La fonctionnalité requise suivante est terminée:

* [] L'utilisateur peut ** se connecter à Twitter ** en utilisant le login OAuth
* [] L'utilisateur peut ** afficher les tweets à partir de la chronologie de sa maison **
  * [] L'utilisateur affiche le nom d'utilisateur, le nom et le corps de chaque tweet
  * [] L'utilisateur affiche [horodatage relatif] (https://gist.github.com/nesquena/f786232f5ef72f6e10a7) pour chaque tweet "8m", "7h"
  * [] L'utilisateur peut voir plus de tweets en faisant défiler avec [pagination infinie] (http://guides.codepath.com/android/Endless-Scrolling-with-AdapterViews-and-RecyclerView). Le nombre de tweets est illimité.
    Cependant, il existe [Twitter Api Rate Limits] (https://developer.twitter.com/en/docs/basics/rate-limiting) en place.
* [] L'utilisateur peut ** composer et poster un nouveau tweet **
  * [] L'utilisateur peut cliquer sur une icône "Composer" dans la barre d'action en haut à droite
  * [] L'utilisateur peut alors entrer un nouveau tweet et le poster sur twitter
  * [] L'utilisateur est ramené à la ligne de temps à la maison avec ** nouveau tweet visible ** dans la chronologie

Les fonctionnalités ** optionnelles ** suivantes sont implémentées:

* [] L'utilisateur peut ** voir un compteur avec le nombre total de caractères laissés pour tweet ** sur la page de rédaction de tweet
* [] L'utilisateur peut ** cliquer sur un lien dans un corps de tweet ** sur la vue détaillée des tweets. Le clic lancera le navigateur Web avec la page appropriée ouverte.
* [] L'utilisateur peut ** tirer vers le bas pour actualiser le calendrier des tweets **
* [] L'utilisateur peut ** ouvrir l'application Twitter hors ligne et voir les derniers tweets chargés **. Persisté dans les tweets SQLite sont actualisés à chaque lancement d'application. Alors que "live data" est affiché lorsque l'application peut l'obtenir à partir de l'API Twitter, elle est également enregistrée pour une utilisation en mode déconnecté.
* [] L'utilisateur peut appuyer sur un tweet pour ** ouvrir une vue détaillée sur les tweets **
* [] L'utilisateur peut ** sélectionner "répondre" à partir de la vue détaillée pour répondre à un tweet **

## Procédure pas à pas vidéo

Voici une présentation des user stories implémentées:

<img src = 'https://imgur.com/a/Nxe1AXm' title = 'Vidéo Procédure pas à pas' width = '' alt = 'Vidéo Procédure pas à pas' />

GIF créé avec [LiceCap] (http://www.cockos.com/licecap/).

## Remarques

probleme d'IDE mon ordinateur n'est pas assez puissant pour lancer l'app

## Bibliothèques open-source utilisées

- [HTTP asynchrone Android] (https://github.com/loopj/android-async-http) - Requêtes HTTP asynchrones simples avec analyse JSON
- [Picasso] (http://square.github.io/picasso/) - Le chargement des images et de la bibliothèque de mise en cache pour Android

## Licence

    Droit d'auteur [yyyy] [nom du titulaire du droit d'auteur]

    Sous licence Apache, Version 2.0 (la "Licence");
    Vous ne pouvez pas utiliser ce fichier sauf en conformité avec la licence.
    Vous pouvez obtenir une copie de la licence à

        http://www.apache.org/licenses/LICENSE-2.0

    Sauf si requis par la loi applicable ou accepté par écrit, logiciel
    distribué sous licence est distribué "TEL QUEL",
    SANS GARANTIE OU CONDITION D'AUCUNE SORTE, expresse ou implicite.
    Voir la licence pour la langue spécifique régissant les autorisations et
    limitations en vertu de la licence.
