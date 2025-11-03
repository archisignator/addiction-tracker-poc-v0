# Tracking Sobriété - Prototype React

Application de suivi pour le parcours vers la sobriété avec approche bienveillante et réduction des risques.

## 🚀 Import dans CodeSandbox

### Méthode 1 : ZIP Upload
1. Téléchargez le fichier `addiction-tracker-project.zip`
2. Allez sur [codesandbox.io](https://codesandbox.io)
3. Cliquez sur "Create Sandbox" ou "Import Project"
4. Choisissez "Import from ZIP"
5. Uploadez le fichier ZIP
6. L'application se lance automatiquement !

### Méthode 2 : Créer manuellement
1. Allez sur [codesandbox.io](https://codesandbox.io)
2. Créez un nouveau sandbox "React + Vite"
3. Remplacez le contenu de `src/App.jsx` par notre fichier
4. Copiez le `package.json` pour installer les dépendances
5. Copiez `src/index.css` pour les styles

## 💻 Installation locale (Mac)

### Prérequis
- Node.js installé ([télécharger ici](https://nodejs.org/))

### Installation
```bash
# 1. Extraire le ZIP et aller dans le dossier
cd addiction-tracker-project

# 2. Installer les dépendances
npm install

# 3. Lancer le serveur de développement
npm run dev

# 4. Ouvrir dans le navigateur
# L'URL s'affiche dans le terminal (généralement http://localhost:5173)
```

## ✨ Fonctionnalités

### Sauvegarde automatique
- ✅ **localStorage activé** : Vos données persistent automatiquement
- ✅ **Export JSON** : Sauvegarde complète téléchargeable
- ✅ **Import JSON** : Restauration depuis un fichier
- ✅ **Export CSV** : Compatible Excel, pour partage avec soignants

### Interface
- **6 vues** : Accueil, Saisie Rapide, Journal, Dashboard, Analyses, Configuration
- **Saisie multi-niveaux** : Rapide (5 sec) → Contexte → Détaillé
- **Visualisations** : Graphiques interactifs (Recharts)
- **Analyses automatiques** : Fréquence, tendances, patterns

### Configuration flexible
- Ajout illimité de substances/comportements
- Catégorisation personnalisable
- Unités personnalisées
- Quantifiable ou non

## 📱 Utilisation

1. **Configuration** : Ajoutez vos types (substances/comportements)
2. **Saisie** : Enregistrez vos épisodes (niveau 1, 2 ou 3)
3. **Visualisation** : Consultez Dashboard et Analyses
4. **Export** : Téléchargez CSV pour soignants ou JSON pour backup

## 🔒 Confidentialité

- Données stockées **localement** dans le navigateur
- Aucun serveur, aucune transmission
- Vous contrôlez vos exports
- Possibilité de tout effacer (bouton "Zone de danger")

## 🛠️ Technologies

- React 18
- Recharts (graphiques)
- Papaparse (CSV)
- Tailwind CSS (via CDN dans index.css)
- Lucide React (icônes)
- Vite (build tool)

## 📝 Notes

- **Sauvegarde auto** : Les données persistent dans le navigateur
- **Export régulier recommandé** : Faites des sauvegardes JSON externes
- **Compatible mobile** : Interface responsive
- **Print-friendly** : Classes CSS pour impression PDF

## 🐛 Problèmes connus

Aucun pour l'instant ! Si vous rencontrez un bug, notez-le.

## 📦 Structure du projet

```
addiction-tracker-project/
├── package.json          # Dépendances
├── vite.config.js        # Configuration Vite
├── index.html            # Point d'entrée HTML
└── src/
    ├── main.jsx          # Bootstrap React
    ├── App.jsx           # Application principale
    └── index.css         # Styles globaux
```

## 🎯 Prochaines étapes

Après les tests :
- Ajustements UI/UX selon vos retours
- Fonctionnalités supplémentaires si besoin
- Hébergement permanent (Netlify/Vercel) si validé
