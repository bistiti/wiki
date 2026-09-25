# wiki.jfdslv - source privee

Source du wiki Datenstrom Yellow publie sur https://wiki.jfdslv.fr

- Contenu editable : content/**/*.md
- Build : GitHub Actions (.github/workflows/deploy.yml) lance `php yellow.php generate`
  puis deploie le dossier `public/` (HTML rendu) vers le depot public `bistiti/wiki` (GitHub Pages).
- Workflow : editer une page -> commit/push sur `main` -> le site se regenere automatiquement.
