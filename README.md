# Application Flutter de News

Une application mobile Flutter pour afficher des articles provenant de l'API Hacker News, permettant aux utilisateurs de lire les articles, les commentaires, et de gérer les articles favoris localement.

## Fonctionnalités

- **Affichage des Articles:** Affichez une liste d'articles avec leurs titres, auteurs et nombres de commentaires.
- **Lecture d'un Article:** Permet aux utilisateurs de lire le contenu complet d'un article et de suivre le lien de l'article.
- **Affichage et Gestion des Commentaires:** Affichez les commentaires de manière hiérarchique et imbriquée.
- **Sauvegarde Locale des Articles:** Stocke localement les articles en utilisant SQLite pour réduire la dépendance à une connexion internet.
- **Gestion des Favoris:** Permet aux utilisateurs de marquer des articles comme favoris et de les gérer de manière persistante.

## Installation

Assurez-vous d'avoir Flutter et Dart installés sur votre machine.

1. Clonez le projet depuis GitHub : `git clone https://github.com/votre-utilisateur/examen-flutter.git`
2. Accédez au répertoire du projet : `cd examen-flutter`
3. Exécutez l'application avec Flutter : `flutter run`

## Utilisation

1. Lancez l'application sur un émulateur ou un périphérique physique.
2. Explorez les articles, lisez les commentaires et marquez vos favoris.
3. Profitez de l'expérience de lecture des nouvelles!

## Dépendances

Les principales dépendances utilisées dans votre projet.

```yaml
dependencies:
  flutter:
    sdk: flutter

  cupertino_icons: ^1.0.2
  provider: ^6.0.5
  http: ^1.1.0
  sqflite: ^2.3.0 
  path_provider: ^2.1.2
  shared_preferences: ^2.2.2
  url_launcher: ^6.0.9
  flutter_widget_from_html: ^0.14.11
  

dev_dependencies:
  flutter_test:
    sdk: flutter
