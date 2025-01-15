Ce rapport présente le projet de developpement d’une application de 
soutien des personnes en situation de handicap developpé par Abdallah 
DIONGUE dans le cadre du cours de developpement d’application mobile. Ce 
projet vise à développer une application du nom de HandicApp qui offrira des 
solutions concrètes pour améliorer l'inclusion sociale, la mobilité, et faciliter la 
vie des personnes en situation de handicap.
I. Présentation des Fonctionnalités 
Pour la réalisation de mon application, j’ai implémenté 3
fonctionnalités principales à savoir : la cartographie d’accessibilité, 
une guide multilingue en langue des signes et une note de sécurité
personnalisé.
I-1. Cartographie d'accessibilité
La cartographie d’accessibilité permet aux utilisateurs de découvrir 
des lieux accessibles en fonction de leurs besoins spécifiques, tels 
que rampes d'accès, ascenseurs, toilettes adaptées, etc… Cette 
fonctionnalité nécessite l’intégration de l’API google map. J’ai réussi 
à avoir une clé google map mais sans la disposition de carte bancaire 
j’ai pas pu l’intégrer cause pour laquelle j’ai utilisé une photo pour 
représenter du mieux possible la cartographie.
I-2. Guides Multilingues en Langue des Signes
Cette fonctionnalité intègre des guides vidéo en langue des signes 
pour aider les utilisateurs sourds ou malentendants à comprendre les 
informations et les instructions dans différents lieux et à apprendre la 
langue des signes.
I-3. Notes de Sécurité Personnalisées
Elle donne aux utilisateurs la possibilité de créer des notes de sécurité 
personnalisées, fournissant des informations cruciales sur leurs 
besoins spécifiques en cas d'urgence comme le(s) contact(s) 
d’urgence et les informations médicales.
II. Structure et organisation 
Pour l’implémentation de l’application, j’ai utilisé mon propre 
structuration qui consiste à rassembler dans un dossier tous les fichiers qui 
sont utilisés dans une même page comme le montre l’arborescence cidessous :
Le dossier lib contient les dossiers :
• Auth : qui contient le fichier auth.dart qui gère l’authentification 
des utilisateurs, l’inscription, la connexion et la déconnexion
• home_page : contient le dossier FonctionnaliteDeBase regroupant 
l’ensemble des fichiers qui gèrent les fonctionnalités de bases, le 
dossier Profile ou on a les fichiers qui donne accès aux informations 
de l’utilisateur, le fichier home_page.dart pour la page et 
persistent_bottom pour naviguer entre la page d’accueil, de 
recherche et de profile.
• Inscription_connexion : ce dossier referme les fichiers de 
connexion, d’inscription, du mot de passe oublié et d’accueil 
(index.dart) qui permet aux utilisateurs d’avoir le choix entre 
l’inscription 
• main.dart est le fichier principal qui permet de se rediriger vers le 
fichier index.dart
 1 2
 
 3 4
 
 5 6
 
III. Outils utilisés
Afin de réaliser l’application, j’ai utilisés les outils suivants :
• Langage de programmation : Dart
• Framework : Flutter
• Base de données : Firebase (pour l’authentification, stockage et 
récupération des données avec firestore, stockage et récupération 
d’images et vidéos avec Storage)
Conclusion
En conclusion, projet de développement d’une application de soutien 
des personnes en situation de handicap a permis de développer une 
application mobile avec des fonctionnalités clés répondant aux besoins 
des utilisateurs. Ce projet m’a également permis de développer mes 
compétences en matière de développement logiciel
