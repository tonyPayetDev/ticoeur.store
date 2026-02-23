# 🌹 Cœur de Velours - Chocolatier d'Exception

Un site web luxueux et professionnel pour une chocolaterie d'exception spécialisée dans les boîtes de chocolats en forme de cœur accompagnées de roses.

![Version](https://img.shields.io/badge/version-2.0-gold)
![Status](https://img.shields.io/badge/status-production-green)

## ✨ Caractéristiques Premium

### 🎨 Design & Branding
- **Identité visuelle sophistiquée** : Logo "Cœur de Velours" avec typographie élégante
- **Palette de couleurs luxueuse** : Tons chocolat, or et rose pour une ambiance raffinée
- **Typographie premium** : Playfair Display pour les titres, Montserrat pour le corps
- **Navigation moderne** : Menu sticky avec effets de hover animés

### 📸 Images & Contenu
- **Images réelles de produits** : Photos haute qualité depuis Unsplash
- **Galerie interactive** : Affichage des créations en lightbox modale
- **3 collections signature** :
  - Boîte Passion (45€) - Bestseller
  - Boîte Romance (65€) - Premium
  - Boîte Éternelle (95€) - Exclusive

### 🎭 Animations & Interactivité
- **Animations au scroll** : Apparition progressive des éléments avec Intersection Observer
- **Effet parallax** : Mouvement subtil sur l'image hero
- **Particules animées** : Cœurs, roses et chocolats lors des interactions
- **Notifications élégantes** : Messages de confirmation avec animations fluides
- **Compteurs animés** : Statistiques qui s'incrémentent au scroll
- **Hover effects** : Zoom, rotation et transformations sur les cartes

### 📱 Sections Complètes
1. **Hero Premium** : Section d'accueil avec call-to-action
2. **Collection Signature** : Cartes produits détaillées avec badges
3. **Galerie** : Showcase des créations en images
4. **Notre Histoire** : Section about avec statistiques animées
5. **Caractéristiques** : 4 points forts de la marque
6. **Contact** : Formulaire complet avec coordonnées
7. **Footer riche** : Navigation, infos légales, newsletter

### 🎯 UX/UI Optimisé
- **Design responsive** : Adaptation parfaite mobile, tablette, desktop
- **Performance optimisée** : Chargement rapide et fluide
- **Accessibilité** : Structure sémantique HTML5
- **Smooth scroll** : Navigation fluide entre sections
- **Feedback visuel** : Animations et états de hover partout

## 🛠️ Technologies Utilisées

```
├── HTML5 - Structure sémantique
├── CSS3 - Design moderne avec variables CSS
│   ├── Flexbox & Grid Layout
│   ├── Animations & Transitions
│   ├── Media Queries
│   └── Custom Properties
└── JavaScript ES6+
    ├── Intersection Observer API
    ├── Event Listeners
    ├── DOM Manipulation
    └── Animations dynamiques
```

## 📁 Structure du Projet

```
chocolat-rose-coeur/
├── index.html              # Page principale
├── css/
│   └── style.css          # Styles complets (810 lignes)
├── js/
│   └── script.js          # Interactivité (405 lignes)
├── images/                # Dossier pour images locales
└── README.md              # Documentation
```

## 🚀 Installation & Utilisation

### Démarrage Rapide
1. Ouvrez `index.html` dans votre navigateur
2. Aucune installation ou dépendance requise
3. Tout fonctionne directement!

### Pour le Développement
```bash
# Cloner ou télécharger le projet
cd chocolat-rose-coeur

# Ouvrir avec un serveur local (optionnel)
python -m http.server 8000
# ou
npx serve
```

## 🎨 Palette de Couleurs

| Couleur | Hex | Usage |
|---------|-----|-------|
| Chocolat Principal | `#8B4513` | Éléments principaux |
| Chocolat Foncé | `#5D2E0F` | Texte & footer |
| Or | `#D4AF37` | Accents & labels |
| Rose | `#E91E63` | Boutons d'action |
| Crème | `#FFF8F0` | Arrière-plans |

## ✨ Fonctionnalités Interactives

### Boutons "Ajouter au Panier"
- Animation de succès avec changement de couleur
- Effet de particules (cœurs, roses, chocolats)
- Notification de confirmation
- Désactivation temporaire après ajout

### Formulaire de Contact
- Validation des champs requis
- Animation de soumission
- Message de confirmation personnalisé
- Réinitialisation automatique

### Galerie d'Images
- Clic pour agrandir en lightbox
- Fermeture au clic ou à l'extérieur
- Animations d'ouverture/fermeture
- Images haute résolution

### Navigation
- Smooth scroll vers les sections
- Effet sticky avec ombre au scroll
- Liens actifs avec underline animé
- Menu responsive (mobile)

## 📊 Sections Détaillées

### 1. Hero Section
- Titre accrocheur avec CTA
- Image produit premium
- Animation d'entrée (fade in left/right)
- Bouton scroll vers collection

### 2. Collection Signature
Trois produits avec:
- Image haute qualité
- Badge status (Bestseller, Premium, Exclusive)
- Description détaillée
- Détails techniques (type chocolat, nombre roses)
- Prix et bouton d'achat

### 3. Notre Histoire
- Image artisan chocolatier
- Texte histoire de la marque
- 3 statistiques animées:
  - 30+ années d'expertise
  - 50K+ clients satisfaits
  - 100% artisanal

### 4. Caractéristiques
- Création artisanale
- Ingrédients premium
- Livraison express
- Emballage raffiné

## 🌐 Sources & Crédits

### Images
Toutes les images proviennent d'[Unsplash](https://unsplash.com) (licence libre):
- [Chocolat Box Photos](https://unsplash.com/s/photos/chocolate-box)
- [Valentine Photos](https://unsplash.com/s/photos/valentines-day-chocolate)
- [Chocolate Heart](https://unsplash.com/s/photos/chocolate-heart)

### Typographies
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) - Google Fonts
- [Montserrat](https://fonts.google.com/specimen/Montserrat) - Google Fonts

### Inspirations
- [Planète Chocolat](https://www.planetechocolat.com) - Chocolatier belge de luxe
- [Fabrice Gillotte](https://fabricegillotte.com) - Chocolatier français
- Design moderne de sites e-commerce premium

## 🔧 Personnalisation

### Changer les Couleurs
Modifiez les variables CSS dans `style.css`:
```css
:root {
    --primary: #8B4513;      /* Votre couleur */
    --accent: #D4AF37;       /* Votre couleur */
    --rose: #E91E63;         /* Votre couleur */
}
```

### Modifier les Produits
Éditez les sections dans `index.html`:
```html
<div class="product-card">
    <div class="product-image">
        <img src="votre-image.jpg" alt="Produit">
    </div>
    <!-- Contenu du produit -->
</div>
```

### Ajouter des Images Locales
1. Placez vos images dans le dossier `images/`
2. Remplacez les URLs Unsplash par vos chemins locaux:
```html
<img src="images/votre-image.jpg" alt="Description">
```

## 📱 Responsive Design

### Breakpoints
- **Desktop**: > 1024px - Design complet
- **Tablet**: 768px - 1024px - Layout adapté
- **Mobile**: < 768px - Layout vertical

### Adaptations Mobile
- Navigation cachée (peut être étendue avec menu burger)
- Grids en colonnes simples
- Tailles de texte réduites
- Images adaptatives

## 🎯 Performance

- ✅ Pas de dépendances externes (sauf Google Fonts)
- ✅ Images optimisées via Unsplash CDN
- ✅ CSS minimaliste avec variables
- ✅ JavaScript vanilla performant
- ✅ Lazy loading natif des images
- ✅ Animations GPU-accelerated

## 📈 Améliorations Futures

- [ ] Menu burger responsive pour mobile
- [ ] Système de panier fonctionnel
- [ ] Intégration paiement (Stripe/PayPal)
- [ ] Backend pour formulaire de contact
- [ ] Système de gestion des commandes
- [ ] Blog intégré
- [ ] Multi-langues (FR/EN)
- [ ] Mode sombre

## 📞 Support

Pour toute question ou suggestion:
- Email: contact@coeurdevlelours.fr
- GitHub Issues: [Créer un issue](#)

## 📄 License

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer.

---

**Créé avec ❤️ par Cœur de Velours | Chocolatier d'Exception**

*"L'art chocolatier au service de vos émotions"*
