# Appolinaire Adouabou — Portfolio

> Portfolio personnel d’un étudiant en réseaux et systèmes, orienté Linux, administration système et cybersécurité.

[![Live website](https://img.shields.io/badge/Website-appolinaire.me-0969da?style=flat-square&logo=google-chrome&logoColor=white)](https://appolinaire.me)
[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)](https://astro.build/)
[![Styled with Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Deployed with GitHub Pages](https://img.shields.io/badge/Deployed%20with-GitHub%20Pages-22272E?style=flat-square&logo=github&logoColor=white)](https://pages.github.com/)

## Aperçu

Ce projet est le portfolio professionnel d’**Appolinaire Adouabou**. Il présente son parcours, ses compétences, ses projets pratiques et ses objectifs professionnels dans les domaines des réseaux informatiques, des systèmes Linux et de la cybersécurité.

Le site est accessible en ligne :

**[https://appolinaire.me](https://appolinaire.me)**

## Objectifs

- Présenter mon profil et mon parcours.
- Documenter mes projets techniques.
- Mettre en avant mes compétences en réseaux et systèmes.
- Faciliter le téléchargement de mon CV.
- Fournir un moyen de contact professionnel.
- Construire progressivement une vitrine technique évolutive.

## Sections du portfolio

- **About** — présentation personnelle et objectifs.
- **Skills** — compétences techniques et outils utilisés.
- **Projects** — projets pratiques et documentés.
- **Education** — parcours académique.
- **Contact** — liens GitHub, e-mail et moyens de contact.
- **Download CV** — téléchargement du CV au format PDF.

## Technologies utilisées

- [Astro](https://astro.build/) — framework de génération de sites rapides et statiques.
- [Tailwind CSS](https://tailwindcss.com/) — framework CSS utilitaire.
- [Vite](https://vite.dev/) — outil de développement et de build.
- [Git](https://git-scm.com/) — gestion de versions en local.
- [GitHub](https://github.com/) — hébergement du code source.
- [GitHub Actions](https://github.com/features/actions) — automatisation du build et du déploiement.
- [GitHub Pages](https://pages.github.com/) — hébergement du site statique.

## Architecture du projet

```text
portfolio/
├── public/                 # Fichiers statiques accessibles directement
│   ├── images/             # Images du portfolio
│   ├── cv.pdf              # CV téléchargeable
│   ├── favicon.svg         # Icône du site
│   └── CNAME               # Domaine personnalisé
│
├── src/
│   ├── components/         # Composants Astro réutilisables
│   ├── layouts/            # Structures communes des pages
│   ├── pages/              # Pages et routes du site
│   ├── content/            # Contenu structuré, si nécessaire
│   ├── data/               # Données des projets et compétences
│   └── styles/             # Styles globaux
│
├── .github/
│   └── workflows/
│       └── deploy.yml      # Workflow de déploiement GitHub Pages
│
├── astro.config.mjs        # Configuration Astro
├── package.json            # Scripts et dépendances
├── package-lock.json       # Versions verrouillées des dépendances
└── README.md               # Documentation du projet
```

## Installation locale

Cloner le dépôt :

```bash
git clone git@github.com:Appolinaire226/portfolio.git
cd portfolio
```

Installer les dépendances :

```bash
npm install
```

Lancer le serveur de développement :

```bash
npm run dev
```

Le site sera disponible sur une adresse similaire à :

```text
http://localhost:4321
```

## Commandes disponibles

| Commande | Description |
| --- | --- |
| `npm install` | Installe les dépendances du projet |
| `npm run dev` | Lance le serveur de développement |
| `npm run build` | Génère la version de production dans `dist/` |
| `npm run preview` | Prévisualise la version construite localement |

## Workflow de développement

Les modifications sont développées localement, testées, enregistrées avec Git, puis envoyées vers GitHub :

```bash
npm run build
git status
git add .
git commit -m "Description de la modification"
git push origin main
```

Après le push sur `main`, GitHub Actions construit automatiquement le projet et GitHub Pages publie la nouvelle version du site.

```text
Modification locale
        ↓
Git commit
        ↓
git push origin main
        ↓
GitHub Actions
        ↓
npm run build
        ↓
GitHub Pages
        ↓
https://appolinaire.me
```

## Domaine et déploiement

Le site utilise le domaine personnalisé :

```text
https://appolinaire.me
```

Le déploiement est effectué automatiquement avec GitHub Actions. Le workflow se trouve dans :

```text
.github/workflows/deploy.yml
```

Astro est configuré pour utiliser le domaine personnalisé :

```js
site: "https://appolinaire.me"
```

Aucun `base: "/portfolio"` n’est nécessaire lorsque le site est servi directement depuis le domaine personnalisé.

## Évolution prévue

Ce portfolio est conçu pour évoluer progressivement :

- améliorer le design inspiré de GitHub ;
- ajouter un mode sombre et un mode clair ;
- améliorer l’expérience mobile ;
- ajouter des pages détaillées pour chaque projet ;
- structurer les projets avec des collections de contenu Astro ;
- ajouter des captures d’écran et des démonstrations ;
- ajouter les certifications et expériences ;
- améliorer le référencement SEO ;
- renforcer l’accessibilité et les performances ;
- ajouter éventuellement un blog technique.

## Auteur

**Appolinaire Adouabou**

- Portfolio : [appolinaire.me](https://appolinaire.me)
- GitHub : [@Appolinaire226](https://github.com/Appolinaire226)

## Statut

Le portfolio est actuellement en ligne et continue d’être amélioré au fil du temps.

```text
Status: Online and evolving
```
