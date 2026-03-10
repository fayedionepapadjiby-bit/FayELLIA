# 📱 GUIDE COMPLET FAYELLIA
## Site E-commerce pour Accessoires & Vêtements Féminins

---

## 🚀 DÉMARRAGE RAPIDE

### Vous avez 2 fichiers:
1. **fayellia.html** - Le site visible par vos clients
2. **fayellia-admin.html** - Votre panneau de gestion privé

---

## 📊 PANNEAU D'ADMINISTRATION

### 🔓 Accès au Panneau Admin

**URL:** Ouvrez le fichier `fayellia-admin.html` dans votre navigateur

**Identifiants par défaut:**
- **Identifiant:** `admin`
- **Mot de passe:** `fayellia2024`

> ⚠️ **IMPORTANT:** Changez le mot de passe dès que possible pour sécuriser votre compte!

---

## 💻 UTILISATION DU PANNEAU ADMIN

### 1️⃣ TABLEAU DE BORD (Accueil)
- **Vue d'ensemble** de votre boutique
- **Statistiques en temps réel:**
  - Nombre total de produits
  - Nombre de commandes reçues
  - Nombre de clients uniques
  - Revenus totaux
- **Dernières commandes** (5 dernières)

### 2️⃣ GESTION DES PRODUITS

#### ➕ Ajouter un produit:
1. Cliquez sur **"+ Ajouter un produit"**
2. Remplissez les informations:
   - **Emoji** (🛍️, 👗, 👜, etc.) - Représente visuellement le produit
   - **Nom du produit** (ex: Robe Traditionnelle Chic)
   - **Catégorie** (Vêtements, Accessoires, Bijoux, Sacs)
   - **Prix en CFA** (ex: 45000)
   - **Stock** (nombre d'articles disponibles)
   - **Badge** (optionnel: Nouveau, Populaire, Soldes, Exclusif, Tendance)
3. Cliquez sur **"Ajouter le produit"**

#### ✏️ Éditer un produit:
- Dans le tableau, cliquez sur **"Éditer"** à côté du produit
- Modifiez les informations
- Sauvegardez

#### 🗑️ Supprimer un produit:
- Cliquez sur **"Supprimer"**
- Confirmez la suppression

### 3️⃣ GESTION DES COMMANDES

- **Voir toutes les commandes** reçues de vos clients
- Informations pour chaque commande:
  - Numéro de commande (#ID)
  - Nom du client
  - Numéro de téléphone
  - Montant de la commande
  - Méthode de paiement (Wave ou Orange Money)
  - Date de la commande
  - Statut (Confirmée)

### 4️⃣ GESTION DES CLIENTS

- **Liste de tous vos clients** qui ont acheté
- Pour chaque client:
  - Nom complet
  - Numéro de téléphone
  - Méthode de paiement utilisée
  - Nombre de commandes passées
  - Montant total dépensé

### 5️⃣ ACCÈS & CONFIGURATION

#### 🔐 Identifiants d'accès:
- Affiche vos identifiants admin
- Permet de changer votre mot de passe

#### 📱 Informations de boutique:
Mettez à jour:
- Nom de la boutique
- Localisation
- Email
- Numéro de téléphone

#### 💳 Comptes de paiement:
Enregistrez:
- Votre numéro Wave
- Votre numéro Orange Money

---

## 🛍️ SITE CLIENT (fayellia.html)

### 📋 Vue générale pour vos clients:

#### Navigation (En haut)
- **FAYELLIA** - Logo de la boutique
- **Accueil** - Retour à l'accueil
- **Produits** - Voir tous les produits
- **Contact** - Informations de contact
- **Panier** 🛍️ - Voir le panier (affiche le nombre d'articles)

#### Section Héro
- Présentation attrayante de votre boutique
- Bouton pour découvrir les produits

#### Filtres de catégories
Vos clients peuvent filtrer par:
- **Tous** - Tous les produits
- **Vêtements** - Robes, Boubous, Cardigans, etc.
- **Accessoires** - Ceintures, Foulards, Sandales, etc.
- **Bijoux** - Bracelets, Colliers, Boucles d'oreilles
- **Sacs** - Sacs à main, Sacs bandoulière

#### Grille de produits
Chaque produit affiche:
- Emoji du produit
- Nom
- Prix en CFA
- Badge (si applicable)
- Bouton "Ajouter au panier"

#### Panier
Vos clients peuvent:
- Ajouter des produits
- Modifier les quantités (+/-)
- Supprimer des articles
- Voir le total
- Passer la commande

#### Paiement
Après clic sur "Passer la commande", vos clients choisissent:
- **Wave** - Entrent leur numéro + nom
- **Orange Money** - Entrent leur numéro + nom

Les informations de la commande sont enregistrées dans votre admin!

#### Footer (Pied de page)
- Informations de la boutique
- Liens utiles
- Coordonnées de contact
- Réseaux sociaux
- Moyens de paiement acceptés

---

## 💳 INTÉGRATION DES PAIEMENTS

### Wave
- Clients entrent leur numéro Wave (+221 7X XXX XXXX)
- Montant est envoyé à votre compte Wave
- Les commandes sont enregistrées automatiquement

### Orange Money
- Clients entrent leur numéro Orange Money
- Montant est envoyé à votre compte Orange Money
- Les commandes sont enregistrées automatiquement

---

## 🔧 PERSONNALISATION

### Modifier les informations de la boutique:
1. Allez à **Accès & Configuration** dans l'admin
2. Cliquez sur **"Modifier les informations"**
3. Changez:
   - Email: `contact@fayellia.sn`
   - Téléphone: `+221 77 XXX XXXX`
   - Localisation: `Dakar`

### Modifier vos comptes de paiement:
1. Allez à **Accès & Configuration**
2. Cliquez sur **"Mettre à jour les comptes"**
3. Entrez:
   - Votre numéro Wave
   - Votre numéro Orange Money

### Ajouter/Modifier les couleurs du site:
**Note:** Pour personnaliser les couleurs, vous devez modifier le code HTML
(Cherchez `:root` au début du fichier CSS)

---

## 📈 FONCTIONNEMENT COMPLET

### Client achète:
1. Visite votre site (fayellia.html)
2. Parcourt les produits
3. Ajoute des articles au panier
4. Clique "Passer la commande"
5. Choisit Wave ou Orange Money
6. Rentre ses informations
7. Paiement effectué

### Vous recevez:
- ✅ Notification de paiement (sur Wave/Orange)
- ✅ Détails de commande dans le Panneau Admin
- ✅ Informations du client
- ✅ Montant total de la commande

### Vous livrez:
- 📦 Livrez à l'adresse du client
- 📝 Marquez la commande comme livrée (optionnel)

---

## ⚙️ CONSEILS D'UTILISATION

### 📱 Sur mobile:
- Le site s'adapte automatiquement
- Facile à consulter pour les clients
- Paiement simple et rapide

### 💾 Sauvegarde des données:
- Les produits et commandes sont sauvegardés automatiquement
- Les données sont stockées localement sur votre navigateur
- Utilisez toujours le **même navigateur** pour voir vos données

### 🔐 Sécurité:
- Changez votre mot de passe régulièrement
- Ne partagez jamais vos identifiants
- Vérifiez les commandes avant de livrer

### 📊 Analyser vos ventes:
- Consultez le **Tableau de bord** régulièrement
- Voyez quels produits se vendent le plus
- Ajustez votre stock en fonction
- Analysez les tendances de vos clients

---

## 🌐 PARTAGER VOTRE SITE

### Partager le lien:
1. Hébergez le fichier `fayellia.html` sur un serveur web
2. Obtenez l'URL (ex: `https://www.fayellia.sn`)
3. Partagez sur:
   - WhatsApp
   - Facebook
   - Instagram
   - Email
   - SMS

### Garder l'admin sécurisé:
- Ne partagez PAS le lien `fayellia-admin.html`
- Gardez-le pour vous uniquement
- Utilisez un mot de passe fort

---

## ❓ QUESTIONS FRÉQUENTES

### Q: Où mes données sont-elles stockées?
**R:** Les données sont stockées dans le navigateur (localStorage). Utilisez toujours le même navigateur.

### Q: Comment exporter mes commandes?
**R:** Ouvrez la console du navigateur (F12) et copiez les données de localStorage.

### Q: Puis-je avoir plusieurs administrateurs?
**R:** Pour le moment, il y a un seul compte admin. Une version multi-utilisateurs peut être développée.

### Q: Comment augmenter la capacité de stock?
**R:** Dans le panneau admin, modifiez simplement la valeur du stock pour chaque produit.

### Q: Les paiements sont-ils automatiques?
**R:** Les informations sont enregistrées. Vous recevez les paiements directement sur votre compte Wave/Orange.

### Q: Comment ajouter d'autres méthodes de paiement?
**R:** Contactez un développeur pour intégrer d'autres services (Stripe, PayPal, etc).

---

## 🎨 PERSONNALISATION AVANCÉE

### Ajouter votre logo:
1. Ouvrez le fichier HTML dans un éditeur de texte
2. Cherchez `.logo`
3. Remplacez le texte ou ajoutez une image

### Changer les couleurs:
Cherchez dans le CSS:
```css
--primary: #D4A574;      /* Couleur principale (or)*/
--accent: #8B4789;       /* Couleur secondaire (violet) */
--dark: #2D2D2D;         /* Texte sombre */
--light: #F9F7F4;        /* Couleur de fond */
```

---

## 📞 SUPPORT & AIDE

### Si quelque chose ne fonctionne pas:

1. **Rafraîchissez la page** (Ctrl+F5 ou Cmd+Shift+R)
2. **Videz le cache** du navigateur
3. **Utilisez un autre navigateur** (Chrome, Firefox, Safari)
4. **Vérifiez votre connexion internet**

### Pour les problèmes techniques:
- Ouvrez la **Console Développeur** (F12)
- Cherchez les messages d'erreur
- Signalez-les pour que nous puissions aider

---

## 📝 RÉSUMÉ RAPIDE

| Action | Où? | Comment? |
|--------|-----|---------|
| **Ajouter produit** | Produits | + Ajouter un produit |
| **Voir commandes** | Commandes | Tableau des commandes |
| **Voir clients** | Clients | Tableau des clients |
| **Modifier infos** | Accès & Config | Cliquer sur modifier |
| **Vendre** | fayellia.html | Partager le lien |
| **Gérer** | fayellia-admin.html | Se connecter avec admin |

---

## 🎯 OBJECTIFS POUR DÉMARRER

- [ ] Télécharger les 2 fichiers HTML
- [ ] Ouvrir `fayellia-admin.html`
- [ ] Se connecter avec `admin` / `fayellia2024`
- [ ] Changer le mot de passe
- [ ] Ajouter/modifier vos produits
- [ ] Mettre à jour vos coordonnées
- [ ] Ajouter vos numéros Wave et Orange
- [ ] Partager le lien `fayellia.html` avec vos clients
- [ ] Vérifier régulièrement le Tableau de bord
- [ ] Livrer les commandes promptement

---

## 🚀 PROCHAINES ÉTAPES

### Pour améliorer votre site:
1. **Héberger le site** - Utilisez un service comme Netlify, GitHub Pages, ou un serveur web
2. **Domaine personnalisé** - Achetez un domaine (fayellia.sn par exemple)
3. **Emails automatiques** - Configurez des notifications de commandes
4. **Mode sombre** - Ajouter un mode nuit pour plus de confort
5. **Multiple langues** - Proposer le wolof ou d'autres langues
6. **Système de livraison** - Intégrer des partenaires de livraison

---

**Merci d'utiliser FAYELLIA! 💚**

*Bonne chance pour votre boutique en ligne!*
