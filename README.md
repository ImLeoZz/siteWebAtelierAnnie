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
- Page de contact (coordonnées, sans formulaire).
- Site responsive adapté aux mobiles.
- Optimisation SEO de base.

## Technologies

- HTML
- CSS
- JavaScript (sans framework, sans étape de build)

## Utilisation en local

```bash
git clone https://github.com/ImLeoZz/siteWebAtelierAnnie.git
cd siteWebAtelierAnnie
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## Structure du projet

La racine du dépôt correspond exactement au contenu à placer dans `public_html/` sur o2switch.

```text
/
├── index.html
├── prestations.html
├── galerie.html
├── contact.html
├── 404.html
├── robots.txt
├── .htaccess
├── assets/
├── css/
└── js/
```

`README.md` et `LICENSE` ne sont pas nécessaires en ligne.

## Déploiement sur o2switch (cPanel)

1. Se connecter au cPanel o2switch.
2. Envoyer le contenu du dépôt (pas le dossier lui-même) dans `public_html/` :
   - via le Gestionnaire de fichiers (zip puis extraction),
   - ou en FTP/SFTP,
   - ou via Git Version Control (clone du dépôt public, puis copie vers `public_html/` avec un fichier `.cpanel.yml`).
3. Ne pas envoyer le dossier `.git`.
4. Vérifier que `index.html` est directement dans `public_html/`.
5. Activer AutoSSL (certificat HTTPS) ; le `.htaccess` force ensuite la redirection HTTPS.
6. Vérifier la casse des noms de fichiers (le serveur est sous Linux : `Logo.png` ≠ `logo.png`).
7. Après une mise à jour, vider le cache navigateur (Ctrl+Shift+R).

## À faire

- Compléter les coordonnées (adresse, téléphone, horaires) et le lien Facebook.
- Ajouter les mentions légales (hébergeur : o2switch).
- Optimiser les images (WebP, redimensionnées).
- Optimiser le référencement local.

## Licence

- **Code source** : licence **PolyForm Noncommercial 1.0.0**. Utilisation, modification et distribution autorisées à des fins non commerciales uniquement. Voir le fichier `LICENSE` pour les termes complets.
- **Contenu visuel et textuel** (design, photos, textes) : licence [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).
