# KEYEVENT - Site Web Professionnel

Site web moderne pour KEYEVENT, société spécialisée dans l'organisation d'événements.

## 🌟 Fonctionnalités

- ✅ Design moderne et responsive (mobile, tablette, desktop)
- ✅ Page d'accueil avec hero section animée
- ✅ Section "À propos" avec statistiques
- ✅ Gestion des événements (à venir / passés)
- ✅ Galerie photo
- ✅ Boutique média (vente de vidéos/photos)
- ✅ Présentation des services
- ✅ Formulaire de contact et demande de partenariat
- ✅ Optimisé pour le référencement Google (SEO)

## 📁 Structure des fichiers

```
keyevent-website/
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # Fonctionnalités JavaScript
└── README.md          # Ce fichier
```

## 🚀 Hébergement GRATUIT

### Option 1 : GitHub Pages (Recommandé)

**Avantages :** 
- 100% gratuit
- HTTPS automatique
- Très simple à mettre en place
- URL : votrecompte.github.io/keyevent

**Instructions :**

1. Créez un compte sur https://github.com (si vous n'en avez pas)

2. Créez un nouveau repository :
   - Cliquez sur "New repository"
   - Nom : `keyevent`
   - Public
   - Cliquez sur "Create repository"

3. Uploadez vos fichiers :
   - Cliquez sur "uploading an existing file"
   - Glissez-déposez `index.html`, `styles.css`, `script.js`
   - Cliquez sur "Commit changes"

4. Activez GitHub Pages :
   - Allez dans Settings > Pages
   - Source : "Deploy from a branch"
   - Branch : "main" + folder "/ (root)"
   - Cliquez sur "Save"

5. Votre site sera disponible à : `https://votrecompte.github.io/keyevent/`

### Option 2 : Netlify

**Avantages :**
- Gratuit
- Très facile (drag & drop)
- HTTPS automatique
- Nom de domaine personnalisé possible

**Instructions :**

1. Allez sur https://www.netlify.com
2. Inscrivez-vous gratuitement
3. Cliquez sur "Add new site" > "Deploy manually"
4. Glissez-déposez votre dossier contenant les 3 fichiers
5. Votre site est en ligne instantanément !
6. URL : random-name.netlify.app (modifiable)

### Option 3 : Vercel

**Instructions :**

1. Allez sur https://vercel.com
2. Inscrivez-vous gratuitement
3. Cliquez sur "Add New" > "Project"
4. Importez votre dossier
5. Site en ligne en quelques secondes !

### Option 4 : 000webhost

**Avantages :**
- Gratuit
- Support PHP (pour formulaire)
- Panneau de contrôle classique

**Instructions :**

1. Créez un compte sur https://www.000webhost.com
2. Créez un nouveau site web
3. Utilisez le File Manager pour uploader vos fichiers
4. Votre site sera accessible à : votrenom.000webhostapp.com

## 🔍 Optimisation pour Google (SEO)

Le site est déjà optimisé pour Google avec :

### 1. Balises Meta incluses
- Title optimisé
- Meta description
- Meta keywords
- Open Graph pour réseaux sociaux

### 2. Structure HTML sémantique
- Balises H1, H2, H3 correctement structurées
- Attributs alt pour les images (à ajouter)
- URLs propres avec ancres (#)

### 3. Pour être référencé sur Google :

**A. Soumettez votre site à Google :**

1. Allez sur https://search.google.com/search-console
2. Connectez-vous avec un compte Google
3. Ajoutez votre propriété (votre URL)
4. Vérifiez la propriété
5. Soumettez votre sitemap (créez un fichier `sitemap.xml`)

**B. Créez un fichier sitemap.xml :**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://votre-site.com/</loc>
    <lastmod>2026-01-28</lastmod>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://votre-site.com/#a-propos</loc>
    <priority>0.8</priority>
  </url>
  <url>
    <loc>https://votre-site.com/#evenements</loc>
    <priority>0.9</priority>
  </url>
  <url>
    <loc>https://votre-site.com/#boutique</loc>
    <priority>0.7</priority>
  </url>
  <url>
    <loc>https://votre-site.com/#contact</loc>
    <priority>0.8</priority>
  </url>
</urlset>
```

**C. Créez un fichier robots.txt :**

```
User-agent: *
Allow: /
Sitemap: https://votre-site.com/sitemap.xml
```

## 📝 Personnalisation

### Remplacer les placeholders d'images

1. **Photos de l'équipe / événements :**
   - Remplacez les `<div class="image-placeholder">` par `<img src="votre-image.jpg" alt="Description">`
   - Utilisez des images optimisées (format WebP, taille < 500KB)

2. **Informations de contact :**
   - Ligne 584-610 : Modifiez email, téléphone, adresse
   - Ajoutez vos vrais liens réseaux sociaux

3. **Contenu des événements :**
   - Modifiez les titres, dates, descriptions des événements
   - Ajoutez de vrais événements

### Ajouter un système de paiement

Pour la boutique média, intégrez :
- **Stripe** : https://stripe.com (facile à intégrer)
- **PayPal** : https://www.paypal.com/buttons
- **Gumroad** : https://gumroad.com (simple pour médias digitaux)

### Formulaire de contact fonctionnel

Le formulaire actuel affiche juste une alerte. Pour le rendre fonctionnel :

**Option 1 : Formspree (Gratuit)**
```html
<form action="https://formspree.io/f/VOTRE_ID" method="POST">
```

**Option 2 : EmailJS**
1. Créez un compte sur https://www.emailjs.com
2. Suivez leur documentation pour intégrer

**Option 3 : Backend PHP** (si hébergeur supporte PHP)
Créez un fichier `contact.php` pour traiter les emails

## 🎨 Couleurs du site

```css
Primaire : #e94560 (Rouge/Rose)
Secondaire : #1a1a2e (Bleu foncé)
Accent : #f39c12 (Orange)
```

Pour changer les couleurs, modifiez les variables CSS dans `styles.css` (lignes 1-12).

## 📱 Réseaux sociaux

Ajoutez vos liens :
- Facebook
- Instagram
- LinkedIn
- Twitter/X

Ligne 629-632 dans `index.html`

## 🔧 Support technique

### Problèmes courants

**Le site ne s'affiche pas correctement :**
- Vérifiez que les 3 fichiers sont dans le même dossier
- Videz le cache de votre navigateur (Ctrl + F5)

**Les animations ne fonctionnent pas :**
- Vérifiez que JavaScript est activé dans votre navigateur

**Le formulaire ne fonctionne pas :**
- Normal, il faut intégrer un service d'envoi d'emails (voir section ci-dessus)

## 📈 Amélioration du référencement

1. **Créez du contenu régulier** : Ajoutez une section blog
2. **Backlinks** : Inscrivez-vous sur des annuaires d'événements
3. **Google My Business** : Créez une fiche entreprise
4. **Réseaux sociaux** : Partagez votre site
5. **Vitesse** : Le site est déjà optimisé, mais compressez vos images

## 🆓 Nom de domaine

Pour avoir `www.keyevent.fr` :

**Gratuit pendant 1 an :**
- Freenom (.tk, .ml, .ga) - gratuit mais moins professionnel

**Payant mais recommandé :**
- OVH : ~10€/an pour un .fr
- Namecheap : ~12$/an pour un .com
- Gandi : ~15€/an pour un .fr

Puis configurez les DNS pour pointer vers votre hébergeur.

## 📞 Besoin d'aide ?

Ce site est prêt à l'emploi et optimisé pour Google. Il vous suffit de :
1. L'héberger gratuitement (GitHub Pages recommandé)
2. Remplacer les textes et images
3. Le soumettre à Google Search Console

Pour toute question, consultez :
- GitHub Pages : https://pages.github.com
- Google Search Console : https://search.google.com/search-console
- SEO Guide : https://developers.google.com/search/docs

---

**Créé avec ❤️ pour KEYEVENT**
