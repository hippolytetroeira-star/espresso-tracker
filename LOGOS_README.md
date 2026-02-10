# 🎨 Espresso Tracker - Version avec Logos

## ✨ Nouveautés visuelles

### 1️⃣ **Icône de l'app** 
✅ Nouveau logo : **Soleil doré de L'Arbre à Café**
- Remplace l'ancienne tasse de café
- S'affiche sur ton écran d'accueil (iOS et Android)

### 2️⃣ **Logos dans les cartes de shots**
✅ Chaque shot affiche le **petit logo du café** (32px) à côté du nom
- Timanà → Logo bleu/rose/orange 🔵🟡🔴
- Gédéo → Logo jaune/vert/bleu 🟡🟢🔵
- Autres cafés → Logo générique marron

### 3️⃣ **Logos dans les cartes de paquets**
✅ Logo plus gros (48px) à gauche du nom du paquet
- Même détection automatique selon le nom

### 4️⃣ **Sélecteur visuel dans les formulaires** 
✅ **Nouveau Shot** et **Nouveau Paquet** : clique sur un logo au lieu de taper
- Boutons cliquables avec logos Gédéo, Timanà, et "Autre"
- Le champ texte reste disponible pour personnaliser ou taper un autre nom

## 🔍 Détection automatique des logos

L'app détecte automatiquement quel logo afficher selon le nom du café :
- Nom contient "gédéo" ou "gedeo" → Logo Gédéo
- Nom contient "timanà", "timana" ou "timana" → Logo Timanà
- Autres noms → Logo générique

**Insensible à la casse et aux accents** ✓

## 📁 Fichiers mis à jour

1. **index.html** → Code de l'app avec les logos intégrés en base64
2. **icon-192.png** → Nouvelle icône 192x192 (logo L'Arbre à Café)
3. **icon-512.png** → Nouvelle icône 512x512 (logo L'Arbre à Café)
4. **manifest.json** → Inchangé (référence les icônes)

## 🚀 Installation

Même procédure que d'habitude :
1. Upload tous les fichiers sur GitHub
2. Attends 2-3 minutes
3. Ouvre l'app
4. ✅ Les logos apparaissent partout !

## 💡 Ajouter d'autres cafés

Si tu veux ajouter les logos d'autres cafés (Finca La Folie, Brésil 366, etc.) :
1. Envoie-moi les images/PDFs des logos
2. Je les intègre dans le code
3. Tu upload la nouvelle version

## 🎨 Prévisualisation

**Cartes de shots :**
```
┌─────────────────────────────────┐
│ 🟡🟢🔵 Gédéo                      │
│       10/02/2026 22:48          │
│                                  │
│ 18g → 38g (1:2.1)   Mouture: 7.6│
│ Temps: 33s          PI: 8s      │
│ ...                              │
└─────────────────────────────────┘
```

**Sélecteur de café :**
```
┌─────────────────────────────────┐
│ Café *                           │
│ [🟡 Gédéo] [🔵 Timanà] [● Autre]│
│ ───────────────────────────────  │
│ Gédéo                    ←tapé  │
└─────────────────────────────────┘
```

Bon café ! ☕🎨
