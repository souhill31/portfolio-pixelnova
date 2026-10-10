# Portfolio Souhill D-RUSH

Page portfolio de Souhill D-RUSH, monteur vidéo et créateur de miniatures YouTube. Première version en HTML/CSS, générée avec une IA dans le cadre du challenge PixelNova.

## Objectif du challenge

PixelNova est une agence créative spécialisée dans les sites vitrines modernes et accessibles. Pour lancer un nouveau portfolio de démonstration, l'équipe a besoin d'un environnement Frontend opérationnel et d'une première page (générée via IA) pour itérer rapidement avec les clients.

Ce dépôt contient cette première page, ainsi que le prompt utilisé pour la générer.

## Installation locale

1. Télécharger ou cloner ce dépôt.
2. Ouvrir le dossier dans VS Code.
3. Installer l'extension Live Server si besoin.
4. Faire un clic droit sur `index.html`, puis « Open with Live Server ».

La page s'ouvre dans le navigateur à l'adresse `http://127.0.0.1:5500`.

## Technologies utilisées

- HTML5
- CSS3
- IA générative : Claude

## Prompt IA utilisé

Le prompt est aussi disponible dans le fichier `prompts/IA_prompt.md`.

```
Crée une page web portfolio pour Souhill D-RUSH, monteur vidéo.

CONTENU (dans cet ordre, textes en français) :
1. Un header avec le nom "Souhill D-RUSH" et le sous-titre "Monteur vidéo".
2. Un menu de navigation : Accueil, Réalisations, Miniatures,
   Compétences, Contact.
3. Une section d'accueil avec une phrase d'accroche mettant en avant
   que j'ai travaillé comme monteur et créateur de miniatures pour
   des youtubeurs connus de plus d'1 million d'abonnés, pour des
   millions de vues cumulées.
4. Une section Réalisations : 3 cartes de vidéos (titre, courte
   description, miniature remplacée par un bloc de couleur).
5. Une section Miniatures : une grille de 6 miniatures YouTube
   que j'ai créées pour de grands youtubeurs (chaque miniature
   remplacée par un bloc de couleur au format 16:9).
6. Une section Compétences : Adobe Premiere Pro, After Effects,
   DaVinci Resolve, Photoshop.
7. Une section Contact avec une adresse e-mail.
8. Un footer avec le copyright.

CONTRAINTES TECHNIQUES :
- HTML5 sémantique (header, nav, main, section, footer).
- CSS dans un fichier séparé nommé style.css.
- Page responsive, lisible sur téléphone.
- Aucun framework et aucun JavaScript.
- Aucune image externe.
- Donne deux fichiers complets : index.html et style.css.

STYLE :
- Thème sombre inspiré de l'interface d'un logiciel de montage vidéo.
- Couleur d'accent : un bleu moyen, ni clair ni trop foncé.
- Références au montage : une barre décorative évoquant une timeline,
  des timecodes (ex. 00:01:24) pour numéroter les sections,
  des boutons en forme de bouton lecture.
- Design simple et moderne.
```

## Liens utiles

- Dépôt GitHub : https://github.com/souhill31/portfolio-pixelnova