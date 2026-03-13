# VerifyNews

Site web de présentation pour une extension de navigateur qui aide les utilisateurs à évaluer la fiabilité de l'information politique en ligne.

## Description

VerifyNews est une extension de navigateur pensée pour faciliter la vérification de l'information politique. Elle analyse automatiquement les contenus consultés, affiche un score de fiabilité et donne accès à des sources et explications pour aider l'utilisateur à comprendre avant de croire ou partager.

## Caractéristiques du site

- **Design moderne et professionnel** : Interface claire et épurée avec une hiérarchie visuelle forte
- **Responsive** : Optimisé pour tous les appareils (mobile, tablette, desktop)
- **Sections complètes** :
  - Hero avec proposition de valeur claire
  - Présentation du problème
  - Explication de la solution
  - Détail du fonctionnement
  - Système de score expliqué
  - Démo visuelle interactive
  - Section pour les jeunes utilisateurs
  - Principes de confiance et transparence
  - FAQ interactive
  - Appel à l'action
- **Interactions fluides** : Navigation smooth scroll, accordéon FAQ, hover states
- **Performance** : Site statique léger, compatible GitHub Pages

## Structure du projet

```
VerifyNews/
├── index.html          # Page principale
├── css/
│   └── style.css       # Styles complets et responsive
├── js/
│   └── script.js       # Interactions (FAQ, navigation)
├── assets/
│   ├── icons/          # Icônes et favicon
│   ├── images/         # Images du site
│   └── mockups/        # Mockups produit
├── docs/               # Documentation du projet
└── README.md           # Ce fichier
```

## Technologies utilisées

- HTML5 sémantique
- CSS3 avec variables et grid/flexbox
- JavaScript vanilla (ES6+)
- Google Fonts (Inter)
- Design system cohérent

## Déploiement

Ce site est compatible avec GitHub Pages. Pour déployer :

1. Poussez le code sur GitHub
2. Activez GitHub Pages dans les paramètres du repository
3. Sélectionnez la branche `main` et le dossier racine `/`
4. Le site sera accessible à `https://username.github.io/repository-name/`

## Utilisation locale

Aucune installation nécessaire. Ouvrez simplement `index.html` dans un navigateur moderne.

Pour un meilleur résultat en développement, utilisez un serveur local :

```bash
python3 -m http.server 8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## Principes de design

- **Clarté** : Communication directe et accessible
- **Confiance** : Design professionnel et civic-tech
- **Pédagogie** : Explications progressives et visuelles
- **Neutralité** : Ton équilibré sans militantisme
- **Modernité** : Interface contemporaine et fluide

## Palette de couleurs

- Background : `#F8FAFC`
- Texte principal : `#0F172A`
- Texte secondaire : `#475569`
- CTA Primaire : `#2563EB`
- Score Fiable : `#16A34A`
- Score À vérifier : `#F59E0B`
- Score Douteux : `#DC2626`

## Licence

MIT License - Voir le fichier [LICENSE](LICENSE)

## Contexte

Projet développé dans le cadre d'un prototype pour faciliter la vérification de l'information politique destiné aux jeunes utilisateurs.
