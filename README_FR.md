# 1BETWIN — prototype de démonstration

Prototype mobile-first noir et vert pour Android. Il comprend :
- matchs et cotes **fictifs** ;
- filtres par sport ;
- ticket de pari simulé ;
- compte démo avec solde fictif de 100 000 FCFA ;
- historique local des tickets ;
- aucune API de paris, aucun dépôt/retrait, aucun paiement réel.

## Tester immédiatement
Ouvrir `index.html` dans un navigateur moderne. Les interactions principales fonctionnent côté navigateur.

## Installer comme application depuis Android (PWA)
Pour que Chrome propose « Installer l'application » / « Ajouter à l'écran d'accueil », héberger ces fichiers sur un site HTTPS (par exemple un hébergement statique gratuit compatible HTTPS). Le service worker nécessite HTTP(S), et non un simple fichier local.

1. Déployer le contenu de ce dossier sur un hébergement statique HTTPS.
2. Ouvrir l'URL depuis Chrome sur Android.
3. Menu ⋮ → « Installer l'application » ou « Ajouter à l'écran d'accueil » (le libellé peut varier).

## Limites
Ce dossier est un prototype web installable (PWA), pas un APK Android natif. Il n'a pas été testé sur un appareil physique. Les données sont fictives et les tickets restent locaux au navigateur. La validation ne contacte aucun bookmaker et ne constitue pas un pari réel.

Pour une application en argent réel, demander d'abord l'autorisation applicable au Bénin, puis utiliser des fournisseurs de données sportives et de paiement contractuellement autorisés, ainsi qu'un backend sécurisé.
