SITE PERSO QUARTO — VERSION MISE À JOUR

CONTENU
- photo placée sur la page d'accueil, à droite du texte
- image déjà redimensionnée pour le web : assets/img/photo-enzo.jpg
- structure complète du site prête à ouvrir dans VS Code

UTILISATION
1. Ouvre ce dossier dans VS Code.
2. Ouvre un terminal dans ce dossier.
3. Lance : quarto preview
4. Le site s'ouvrira en local.
5. Modifie les fichiers .qmd puis enregistre.
6. Quarto mettra l'aperçu à jour automatiquement.

SI TU VEUX REMPLACER TON ANCIEN PROJET
- copie-colle simplement ces fichiers par-dessus l'ancien dossier
- ou remplace complètement l'ancien dossier par celui-ci

FICHIERS PRINCIPAUX
- _quarto.yml : configuration générale du site
- styles.css : style visuel
- index.qmd : page d'accueil
- publications.qmd : publications
- enseignement.qmd : enseignement
- cv.qmd : CV web
- contact.qmd : contact
- assets/img/photo-enzo.jpg : ta photo

POUR PUBLIER SUR GITHUB PAGES
1. Lance : quarto render
2. Pousse le dossier sur GitHub
3. Va dans Settings > Pages
4. Source : Deploy from a branch
5. Branch : main
6. Folder : /docs

À MODIFIER CHEZ TOI
- remplace VOTRE-USERNAME dans _quarto.yml
- ajoute tes liens HAL / ORCID / Google Scholar plus tard si besoin
