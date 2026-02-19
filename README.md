# Marketing Landing Page - Nymia

Cette page HTML est optimisée pour le marketing et le référencement de l'application Nymia.

## 🔗 Configuration des liens stores

Pour activer les liens de téléchargement, remplacez les `href="#"` dans le fichier `index.html` :

### App Store (iOS)
Recherchez dans le fichier :
```html
<a href="#" class="store-btn" aria-label="Télécharger sur l'App Store">
```

Remplacez `#` par votre lien App Store, par exemple :
```html
<a href="https://apps.apple.com/fr/app/nymia/idXXXXXXXXX" class="store-btn" aria-label="Télécharger sur l'App Store">
```

### Google Play (Android)
Recherchez dans le fichier :
```html
<a href="#" class="store-btn" aria-label="Télécharger sur Google Play">
```

Remplacez `#` par votre lien Google Play, par exemple :
```html
<a href="https://play.google.com/store/apps/details?id=com.nymia.app" class="store-btn" aria-label="Télécharger sur Google Play">
```

Il y a 2 occurrences de chaque lien dans le fichier (hero section et CTA section).

## 📊 Optimisations SEO incluses

✅ **Meta tags complets** : title, description, keywords
✅ **Open Graph** pour partages sociaux (Facebook, LinkedIn)
✅ **Twitter Cards** pour partages Twitter
✅ **Schema.org markup** (MobileApplication) pour Google
✅ **Balises sémantiques** HTML5 (header, main, section, article, footer)
✅ **Alt texts** et aria-labels pour l'accessibilité
✅ **Hiérarchie de titres** optimisée (H1, H2, H3)
✅ **Canonical URL** pour éviter le contenu dupliqué
✅ **Responsive design** mobile-first
✅ **Performance** : CSS inline, pas de dépendances externes

## 🎨 Personnalisation

### Couleurs
Les couleurs sont définies en variables CSS dans le `<style>` :
```css
--primary: #E8AEBC;
--background: #FFFBFB;
--text: #4A4A4A;
```

### Contenu
Modifiez directement le texte dans le HTML. La structure est claire et commentée.

### Images
Pour ajouter des images (screenshots, logo, etc.) :
1. Placez-les dans le dossier `/marketing/`
2. Mettez à jour les références dans le HTML
3. N'oubliez pas de créer `og-image.png` (1024x500px) pour les partages sociaux

## 🚀 Déploiement

Cette page peut être hébergée sur :
- GitHub Pages
- Netlify
- Vercel
- Tout hébergeur web classique

Aucune compilation nécessaire, c'est du HTML pur.

## 📈 Points marketing mis en avant

1. **Sécurité & Santé** - Prévention du syndrome du choc toxique
2. **Charge mentale** - Tranquillité d'esprit
3. **Vie privée** - Données 100% locales, mode discret
4. **Simplicité** - Interface claire, pas de bullshit
5. **Inclusivité** - 6 types de protections, 12 langues

## 🌐 Langues

La page actuelle est en français. Pour créer des versions multilingues :
- Dupliquez `index.html` en `index-en.html`, `index-es.html`, etc.
- Modifiez l'attribut `lang` dans la balise `<html>`
- Traduisez le contenu
- Ajoutez des liens hreflang dans le `<head>`
