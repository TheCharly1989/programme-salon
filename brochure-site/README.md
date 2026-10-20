# Programme du salon — brochure en ligne

Page web qui affiche la brochure et permet seulement de la feuilleter
(clic sur la page, flèches, flèches du clavier ou balayage sur mobile).

## Remplacer les pages d'exemple

1. Exportez chaque page A5 du graphiste en image (JPG conseillé, environ 1500 px de large).
2. Nommez-les `01.jpg`, `02.jpg`, `03.jpg`… dans l'ordre de lecture.
3. Remplacez le contenu du dossier `pages/`.
4. Dans `index.html`, en haut du fichier, ajustez `titre` et `nombreDePages`.

## Mettre en ligne avec GitHub Pages

1. Créez un dépôt sur GitHub (par ex. `programme-salon`), public.
2. Déposez-y `index.html` et le dossier `pages/` (bouton **Add file → Upload files**, ou `git push`).
3. Dans le dépôt : **Settings → Pages → Build and deployment**,
   Source : *Deploy from a branch*, Branch : `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, la brochure est en ligne à l'adresse
   `https://<votre-compte>.github.io/programme-salon/`.

Chaque nouveau push met le site à jour automatiquement.
