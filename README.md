# FITD — Site web bilingue

Site vitrine statique en HTML5, CSS3 et JavaScript Vanilla. Aucune installation ni compilation n’est nécessaire.

## Lancer le site
1. Décompresser le dossier `FITD`.
2. Ouvrir `index.html` dans un navigateur récent.
3. Pour publier : envoyer le contenu du dossier sur GitHub puis importer le dépôt dans Vercel.

## Pages incluses
- `index.html` — Accueil
- `about.html` — À propos
- `services.html` — Services
- `products.html` — Catalogue indicatif
- `projects.html` — Galerie de démonstration
- `industries.html` — Secteurs
- `contact.html` — Contact
- `quote.html` — Demande de devis

## Bilingue
Le français est la langue par défaut. Le sélecteur FR / EN traduit les textes via `js/translations.js` et mémorise le choix dans `localStorage` (`fitd-language`). Les nouveaux textes doivent être ajoutés aux deux dictionnaires.

## Catalogue
Les familles de produits sont définies dans `js/products.js`. Chaque entrée contient une catégorie, un titre et une description FR/EN ainsi qu'une image. Ajoutez ou modifiez les entrées pour faire évoluer le catalogue.

## Images
Les photographies sont chargées depuis des URL d'images Unsplash (`images.unsplash.com`) et nécessitent une connexion Internet. Elles sont illustratives et ne représentent pas des références FITD. Pour une publication hors ligne, téléchargez des images dont vous détenez les droits et remplacez les URL dans les pages HTML et `js/products.js`.

## Formulaires — important
Les formulaires valident les champs dans le navigateur mais **n'envoient aucune donnée**. Aucun backend ni service d'e-mail n'a été configuré. Connectez un backend sécurisé ou un fournisseur de formulaires avant de recevoir des demandes réelles.

## Informations à compléter avant publication
- Adresse, téléphone, e-mail et WhatsApp officiels de FITD.
- Logo officiel et éventuelle charte graphique.
- Liste réelle des services et produits proposés.
- Secteurs effectivement couverts.
- Projets, photos, références et autorisations de publication.
- Mentions légales, politique de confidentialité et informations relatives au traitement des données.

Aucune date de création, statistique, certification, référence client, adresse ou coordonnée n'a été inventée. Les pages Services, Produits, Secteurs et Réalisations contiennent des contenus indicatifs ou de démonstration à valider.

