# L'Art en Lunettes

Site vitrine de L'Art en Lunettes, opticien créateur à Péruwelz.

Site : [lartenlunettes.be](https://lartenlunettes.be)

## Modifier le site

- `index.html` contient la page, les textes, les styles et les liens.
- `media/` contient les photos et vidéos.
- Les logos sont à la racine du projet.

Pour changer le contenu, modifie `index.html`. Pour remplacer une image ou une vidéo, conserve son nom ou mets à jour son chemin dans `index.html`.

## Mise à jour automatique du site

Chaque modification validée sur la branche `main` lance automatiquement un job GitHub Actions.

Le job **Deploy static content to Pages** :

1. récupère les fichiers du dépôt ;
2. prépare le site statique ;
3. le déploie sur GitHub Pages ;
4. met à jour [lartenlunettes.be](https://lartenlunettes.be).

Il n'y a pas de bouton de publication à cliquer. Après chaque mise à jour du dépôt :

1. ouvre l'onglet **Actions** sur GitHub ;
2. vérifie que le job est terminé avec une coche verte ;
3. attends quelques instants, puis recharge le site.

Si le job échoue, le site reste sur la dernière version publiée. Ouvre le job en erreur pour voir le problème.

## Sécurité

Le dépôt est public. Ne jamais y ajouter de mot de passe, clé API, token, accès FTP, fichier `.env` ou document privé.

Les réglages DNS et le domaine se gèrent chez le fournisseur du domaine. Les accès et la publication se gèrent dans GitHub.

