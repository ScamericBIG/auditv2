# DallAudit PWA — Version navigateur

Application d'audit de dallage industriel. Fonctionne entièrement dans le navigateur, sans serveur.

## Mise en ligne sur GitHub Pages

### Étape 1 — Créer un repo GitHub
1. Aller sur https://github.com → "New repository"
2. Nom : `dallaudit` (ou ce que vous voulez)
3. Public ✓
4. Créer

### Étape 2 — Uploader les fichiers
Glisser-déposer ces fichiers dans le repo GitHub (via l'interface web) :
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

### Étape 3 — Activer GitHub Pages
1. Aller dans Settings du repo
2. "Pages" dans le menu gauche
3. Source : "Deploy from a branch"
4. Branch : `main` / `/ (root)`
5. Save

Votre app est disponible sur :
`https://VOTRE-NOM.github.io/dallaudit/`

## Installer sur smartphone

**iPhone / iPad :**
Safari → ouvrir l'URL → Partager → "Sur l'écran d'accueil"

**Android :**
Chrome → ouvrir l'URL → Menu ⋮ → "Ajouter à l'écran d'accueil"

## Données

Les données sont stockées **sur chaque appareil** (IndexedDB).
Exportez régulièrement via "À propos → Exporter les données".
