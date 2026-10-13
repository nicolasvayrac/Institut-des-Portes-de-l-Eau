# 🚀 SEO Phase 1 — Institut des Portes de l'Eau

Modifications préparées le 13 octobre 2026.

## 📦 Fichiers à uploader dans le repo GitHub

### Nouveaux fichiers (à ajouter)
- `robots.txt` — guide les robots Google (explique les 297 requêtes dans tes stats)
- `sitemap.xml` — plan du site pour Google
- `mentions-legales.html` — page obligatoire RGPD/LCEN
- `site.webmanifest` — meta pour PWA / iOS
- `_headers` — règles de cache (Netlify)
- `_redirects` — URLs amicales SEO (/soins-visage, /rdv, etc.)
- `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png` — favicons

### Fichiers remplacés
- `index.html` — version SEO-optimisée
- `elodie.jpg` + `elodie.webp` + `elodie.png` — photo d'Élodie (format transparent)
- `institut.jpg` — façade optimisée (476 KB au lieu de 1 MB)
- `og-image.jpg` — image 1200×630 pour les partages réseaux sociaux
- `logo.png` — logo optimisé

## ✅ Améliorations SEO appliquées

### Balises meta
- **Title** : `Institut de beauté bio à Louviers | Soins Phyt's & Épilation — Portes de l'Eau` (optimisé pour "institut beauté Louviers")
- **Description** enrichie avec mots-clés géolocalisés
- **Keywords, author, geo, canonical** ajoutés
- **Robots** : `index, follow, max-image-preview:large`

### Open Graph & réseaux sociaux
- URL corrigée : `institutdesportesdeleau.fr` (plus `sunny-daffodil-8fc719.netlify.app`)
- Image dédiée 1200×630 pour les partages (WhatsApp, Facebook, LinkedIn)

### Données structurées (3 blocs JSON-LD)
1. **BeautySalon** enrichi : géoloc exacte, zones desservies (Louviers, Val-de-Reuil, Le Vaudreuil, Pont-de-l'Arche…), catalogue complet des 68 prestations avec prix structurés, action de réservation Planity
2. **FAQ** : 6 questions-réponses pour apparaître en rich snippet Google
3. **Breadcrumb** : fil d'Ariane

### Images
- Photo d'Élodie **intégrée** (plus de placeholder "renommer votre photo")
- `<picture>` avec format WebP (84 KB) + fallback JPG
- Attributs `width`, `height`, `loading`, `fetchpriority` sur toutes les images
- Attributs `alt` enrichis en mots-clés géolocalisés

### Favicons
- Favicon à partir de ton logo (plus de 404 dans tes stats)
- Icône iOS/Android, manifest PWA

### Fichier _redirects (Netlify)
URLs amicales qui aideront le SEO :
- `/soins-visage-louviers` → ancre #services
- `/kobido-louviers` → ancre #services
- `/rdv` → Planity directement
- `/contact` → ancre #contact

### Fichier _headers (Netlify)
- Cache long sur assets (perf Google PageSpeed)
- Headers de sécurité (X-Frame-Options, Referrer-Policy)

### Footer
- Lien **Mentions légales** ajouté (obligation légale)

## 🎯 À faire après le déploiement

1. **Push sur GitHub** → Netlify redéploie automatiquement en 1-2 min

2. **Soumettre le sitemap à Google** :
   - Aller sur [Google Search Console](https://search.google.com/search-console)
   - Ajouter la propriété `institutdesportesdeleau.fr`
   - Sitemaps → ajouter `sitemap.xml`

3. **Compléter les mentions légales** :
   Dans `mentions-legales.html`, les champs `[à compléter]` :
   - Nom complet d'Élodie
   - SIRET
   - Forme juridique (EI / EURL / SASU)
   - N° TVA si applicable

4. **Vérifier la fiche Google Business Profile** :
   - [business.google.com](https://business.google.com)
   - Compléter 100% : horaires, photos (20+), services avec prix
   - Collecter des avis clients

5. **Tester le résultat** :
   - [Rich Results Test Google](https://search.google.com/test/rich-results) → paste `institutdesportesdeleau.fr`
   - Doit valider BeautySalon + FAQ + Breadcrumb

## 📊 Score SEO estimé

| Avant | Après Phase 1 |
|---|---|
| 4/10 | **8/10** |

Prochaines phases possibles :
- **Phase 2** : vraies pages dédiées par service (soins visage, épilation, Kobido…)
- **Phase 3** : blog avec articles mensuels pour trafic longue traîne
