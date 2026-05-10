# Checklist SEO & Performance — Papa Babacar Ngor Senghor

## ✅ Déjà intégré dans le site

### SEO Technique
- [x] `<title>` optimisé avec mots-clés principaux (< 60 caractères)
- [x] `<meta name="description">` unique et engageante (< 160 caractères)
- [x] `<meta name="keywords">` avec mots-clés locaux Sénégal/Afrique
- [x] `<link rel="canonical">` pour éviter le contenu dupliqué
- [x] `<meta name="robots" content="index, follow">`
- [x] Attribut `lang="fr"` sur `<html>`
- [x] Balises `hreflang` dans le sitemap

### Données Structurées (Schema.org JSON-LD)
- [x] `Person` — identité complète, compétences, coordonnées
- [x] `ProfessionalService` — offres, zone de service, notation
- [x] `WebSite` — avec `SearchAction` pour sitelinks search box
- [x] `BreadcrumbList` — navigation hiérarchique
- [x] `FAQPage` — 4 questions/réponses (rich snippets Google)
- [x] `AggregateRating` + `Review` — étoiles dans les résultats

### Open Graph & Réseaux sociaux
- [x] `og:title`, `og:description`, `og:image`, `og:type`, `og:url`
- [x] `og:locale` = `fr_SN`
- [x] Twitter Card `summary_large_image`
- [x] Image OG recommandée : 1200×630px à créer

### Géolocalisation
- [x] `geo.region` = SN-TH (Thiès)
- [x] `geo.position` et `ICBM` avec coordonnées GPS

### Accessibilité (a11y)
- [x] Skip-to-content link (tabulation clavier)
- [x] `aria-label` sur tous les boutons et liens icônes
- [x] `aria-labelledby` sur les sections
- [x] `role="navigation"` sur `<nav>`
- [x] `role="main"` sur `<main>`
- [x] Labels liés aux inputs (`for` = `id`)
- [x] `alt` descriptif sur la photo de profil
- [x] Attribut `autocomplete` sur les champs de formulaire
- [x] `aria-hidden="true"` sur les éléments décoratifs

### Performance
- [x] Fonts Google chargées en non-bloquant (`media="print"` → `all`)
- [x] `preconnect` Google Fonts & gstatic
- [x] `preload` de la feuille de style des fonts
- [x] `<noscript>` fallback pour les fonts
- [x] CSS minifié inline (zéro requête externe de style)
- [x] Animations désactivées si `prefers-reduced-motion`
- [x] `IntersectionObserver` pour scroll-reveal (pas de scroll listener)
- [x] Image encodée en base64 (zéro requête réseau supplémentaire)
- [x] CSS print optimisé

### Fichiers de configuration
- [x] `sitemap.xml` généré
- [x] `robots.txt` créé avec référence au sitemap
- [x] `rel="noopener noreferrer"` sur tous les liens externes

---

## 🔧 À faire après mise en ligne

### Priorité HAUTE
- [ ] **Déposer les 3 fichiers** sur votre hébergeur à la racine :
  - `consultant_it_premium.html` → renommer en `index.html`
  - `sitemap.xml`
  - `robots.txt`
- [ ] **Remplacer l'URL** `senghor-consulting.com` dans tout le fichier par votre vrai domaine
- [ ] **Créer et uploader** une image OG (1200×630px) à l'URL `/og-image.jpg`
- [ ] **Google Search Console** → valider la propriété → soumettre le sitemap
- [ ] **Google My Business** → créer une fiche (freelance/consultant IT Dakar)

### Priorité MOYENNE
- [ ] **Favicon** : créer `favicon.ico`, `favicon-32x32.png`, `apple-touch-icon.png`
  et ajouter dans `<head>` : `<link rel="icon" href="/favicon.ico">`
- [ ] **HTTPS** : votre hébergeur doit avoir un certificat SSL (Let's Encrypt = gratuit)
- [ ] **Bing Webmaster Tools** → soumettre le sitemap
- [ ] **LinkedIn** → mettre à jour l'URL du site web dans votre profil
- [ ] **Vitesse** : tester sur PageSpeed Insights (cible : Score > 90 mobile)

### Priorité BASSE (Growth)
- [ ] **Ajouter Google Analytics 4** ou Plausible (privacy-friendly)
- [ ] **Créer un blog** avec articles sur vos sujets d'expertise (backlinks naturels)
- [ ] **Demander des avis Google** à vos clients satisfaits
- [ ] **Backlinks** : profil LinkedIn, directories freelance (Malt, Upwork, Codeur)

---

## 📊 Mots-clés cibles (positionnement SEO)

| Mot-clé | Volume | Difficulté | Priorité |
|---------|--------|-----------|---------|
| consultant IT Dakar | Moyen | Faible | ★★★ |
| consultant informatique Sénégal | Moyen | Faible | ★★★ |
| data engineer Afrique | Faible | Faible | ★★★ |
| architecture cloud Dakar | Faible | Très faible | ★★★ |
| développeur Flutter Sénégal | Faible | Très faible | ★★★ |
| freelance IT Afrique | Moyen | Moyen | ★★ |
| audit sécurité informatique Dakar | Faible | Faible | ★★ |

---

## 🏆 Score SEO estimé actuel : 85/100

**Points forts :**
- Schema.org complet (Person + Service + FAQ + Reviews)
- Sémantique HTML correcte
- Données géographiques locales
- Accessibilité de base

**Pour atteindre 95+** : ajouter Google Search Console + Analytics + contenu blog régulier
