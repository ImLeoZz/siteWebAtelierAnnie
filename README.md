# Atelier Annie

Site vitrine professionnel pour présenter le savoir-faire d'une tapissière spécialisée dans la restauration de canapés, chaises et fauteuils.

## À propos

Ce projet a pour objectif de créer un site vitrine clair, élégant et moderne afin de mettre en valeur :
- les réalisations avant/après,
- les services proposés,
- l'expertise artisanale,
- les coordonnées de contact.

## Fonctionnalités

- Présentation de l'activité.
- Galerie de réalisations.
- Section prestations.
- Mise en avant des avant/après.
- Page de contact.
- Site responsive adapté aux mobiles.
- Optimisation SEO de base.

## Technologies

- HTML
- CSS
- JavaScript (sans framework, sans étape de build)

## Installation

```bash
git clone https://github.com/ImLeoZz/siteWebAtelierAnnie.git
cd siteWebAtelierAnnie
```

## Utilisation en local

Le site est statique : il suffit d'ouvrir `index.html` dans un navigateur.

Pour un rendu plus proche de la production (chemins relatifs, etc.), lancer un petit serveur local :

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## Structure du projet

```text
/
├── index.html
├── galerie.html
├── prestations.html
├── contact.html
├── assets/
├── css/
├── js/
├── LICENSE
└── README.md
```

## Déploiement

Le site étant statique, il peut être hébergé gratuitement, par exemple via GitHub Pages :

1. Sur GitHub, aller dans **Settings → Pages**.
2. Dans **Source**, choisir **Deploy from a branch**.
3. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.
4. Le site est disponible après quelques minutes sur `https://imleozz.github.io/siteWebAtelierAnnie/`.

Un nom de domaine personnalisé peut ensuite être configuré dans la même page.

## À faire

- Ajouter les photos des réalisations.
- Rédiger les textes des prestations.
- Préparer les informations de contact.
- Ajouter les mentions légales.
- Optimiser le référencement local.
- Déployer le site en ligne.

## Licence

- **Code source** : licence **PolyForm Noncommercial 1.0.0**. Utilisation, modification et distribution autorisées à des fins non commerciales uniquement. Voir le fichier `LICENSE` pour les termes complets.
- **Contenu visuel et textuel** (design, photos, textes) : licence [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).
