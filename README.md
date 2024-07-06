# Fortnite Leaderboard

Ce projet est une application Web simple pour afficher un classement en temps réel des joueurs de Fortnite. Le front-end est entièrement développé en HTML, CSS et JavaScript vanilla.

## Fonctionnalités

- Affichage du classement des joueurs de Fortnite avec leur rang, points et nombre de parties jouées.
- Mise à jour automatique des données toutes les 30 secondes.
- Animation des changements de classement (montée et descente des joueurs).
- Séparation visuelle des joueurs ayant moins de 10 000 points.

## Structure du Projet

```plaintext
Fortnite-Leaderboard/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── script.js
├── index.html
└── README.md
```

### Fichiers

- `index.html`: Fichier HTML principal contenant la structure de la page.
- `assets/css/styles.css`: Feuille de style pour le design de l'application.
- `assets/js/script.js`: Script JavaScript gérant la logique de l'application, y compris la récupération et l'affichage des données.
- `README.md`: Ce fichier, décrivant le projet.

## Instructions d'Installation

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/LeKyuFr/LeaderboardFortnite-Front.git
   ```

2. **Naviguer vers le répertoire du projet :**
   ```bash
   cd LeaderboardFortnite-Front
   ```

3. **Ouvrir `index.html` dans votre navigateur préféré :**
   Vous pouvez simplement double-cliquer sur le fichier `index.html` ou l'ouvrir avec un serveur web local.

## Fonctionnement

1. **Chargement de la page :**
   Lorsque la page est chargée, le script JavaScript récupère les données depuis l'URL `https://*******.*******.**/res.json`.

2. **Affichage du classement :**
   Les données des joueurs sont triées par rang et affichées sous forme de cartes de joueurs dans le div `leaderboard`.

3. **Mise à jour automatique :**
   Toutes les 30 secondes, les données sont récupérées à nouveau et le classement est mis à jour. Les changements de position des joueurs sont animés.

## Dépendances

Le projet utilise uniquement des technologies web standard :
- HTML
- CSS
- JavaScript

Aucune bibliothèque ou framework externe n'est requis.

## Contribution

Les contributions sont les bienvenues ! Pour proposer des modifications, veuillez créer une branche à partir de `main`, apporter vos modifications, puis ouvrir une pull request.

1. **Créer une branche de fonctionnalité :**
   ```bash
   git checkout -b ma-nouvelle-fonctionnalite
   ```

2. **Committer vos modifications :**
   ```bash
   git commit -am 'Ajouter une nouvelle fonctionnalité'
   ```

3. **Pousser la branche :**
   ```bash
   git push origin ma-nouvelle-fonctionnalite
   ```

4. **Ouvrir une Pull Request :**
   Ouvrez une Pull Request sur le dépôt GitHub.

## Licence

Ce projet est sous licence GNU General Public License v3.0. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

Merci d'utiliser Fortnite Leaderboard ! Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une issue sur GitHub.

**Auteur :** Kyufr

---

Ceci est un projet éducatif et n'est pas affilié à Fortnite ou Epic Games.
