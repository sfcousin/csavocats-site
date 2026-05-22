# C&S Avocats — Site web statique

Site web du cabinet **Cousin & Sertelon Avocats** (Lyon), reconstruit en HTML/CSS statique pour hébergement sur GitHub Pages.

## Structure

```
├── index.html        # Accueil
├── domaines.html     # Domaines d'activité
├── a-propos.html     # À propos du cabinet
├── presse.html       # Presse & affaires notables
├── honoraires.html   # Honoraires
├── contact.html      # Formulaire de contact
├── style.css         # Feuille de style principale
└── .nojekyll         # Désactive Jekyll (GitHub Pages)
```

## Déploiement sur GitHub Pages

1. Créer un dépôt GitHub (ex: `csavocats-site`)
2. Pousser tous les fichiers sur la branche `main`
3. Aller dans **Settings → Pages**
4. Source : `Deploy from a branch` → `main` → `/ (root)`
5. Le site sera accessible à `https://<votre-username>.github.io/csavocats-site/`

## Formulaire de contact

Le formulaire utilise [Formspree](https://formspree.io) (service gratuit).  
Pour l'activer : créer un compte sur formspree.io et remplacer l'URL d'action dans `contact.html`.
