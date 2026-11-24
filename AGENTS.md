# Instructions pour les agents

## Projet

Site vitrine statique de **L'Art en Lunettes**, opticien créateur à Péruwelz.

## Règles de sécurité

- Ce dépôt est public.
- Ne jamais ajouter de mot de passe, clé API, token, accès FTP ou donnée personnelle sensible.
- Ne jamais modifier les enregistrements DNS, les accès GitHub ou les réglages de messagerie depuis ce dépôt.
- Ne pas supprimer les fichiers média sans vérifier leurs références dans `index.html`.
- Ne pas ajouter de dépendance ou de framework pour une modification HTML/CSS simple.

## Structure

- `index.html` : page complète, contenu, CSS et JavaScript.
- `logo-face.png`, `logo-full.png`, `logo-text.png` : logos.
- `media/` : photos, affiches et vidéos du site.
- `.github/workflows/static.yml` : publication automatique sur GitHub Pages.

## Développement

- Le site ne possède pas de backend, base de données ou formulaire serveur.
- Ouvrir `index.html` dans un navigateur pour un aperçu local.
- Conserver les chemins relatifs des fichiers : `media/nom-du-fichier.ext`.
- Préserver le responsive mobile, les textes français et l'accessibilité existante.
- Tester les liens, les vidéos, le menu mobile et l'affichage sur mobile après chaque changement important.

## Publication

Un push sur `main` lance le workflow GitHub Pages. Le domaine public est configuré dans GitHub Pages, pas dans ce fichier.

Avant publication :

1. Vérifier que `index.html` existe à la racine.
2. Vérifier les références aux images et vidéos.
3. Vérifier qu'aucun secret n'est présent dans les fichiers modifiés.
4. Vérifier l'action **Deploy static content to Pages** dans GitHub.

## Domaine

Le site utilise un domaine personnalisé. Ne pas changer la balise `canonical`, les URLs Open Graph ou le domaine GitHub Pages sans vérifier la configuration du domaine.

