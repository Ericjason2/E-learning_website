# SkillPath

Un site web d'e-learning moderne et responsive construit avec **React** et **Vite**, offrant une expérience utilisateur fluide pour découvrir et suivre des cours en ligne.

## Table des contenus

- [À propos](#à-propos)
- [Fonctionnalités](#fonctionnalités)
- [Pile technologique](#pile-technologique)
- [Installation](#installation)
- [Scripts disponibles](#scripts-disponibles)
- [Structure du projet](#structure-du-projet)
- [Composants](#composants)
- [Styling](#styling)
- [Contribution](#contribution)
- [Licence](#licence)

## À propos

**SkillPath** est une plateforme d'apprentissage en ligne qui permet aux utilisateurs de :

- Consulter une variété de cours disponibles
- Découvrir les avantages de l'apprentissage en ligne
- Lire les témoignages d'autres apprenants
- Accéder à une section FAQ complète
- Naviguer facilement sur le site

## Fonctionnalités

- **Design responsive** - Adaptation fluide sur tous les appareils (mobile, tablette, desktop)
- **Animations fluides** - Utilisation de la librairie Motion pour des animations performantes
- **Carrousel de cours** - Présentation interactive des cours avec Swiper
- **Marquee dynamique** - Défilement continu des contenus avec React Fast Marquee
- **Optimisation Vite** - Build rapide et serveur de développement performant
- **Icons modernes** - Intégration de React Icons et Remix Icons
- **Linting** - Configuration ESLint pour maintenir la qualité du code

## Pile technologique

### Frontend

- **React** 19.2.4 - Bibliothèque JavaScript pour la construction d'interfaces
- **Vite** 8.0.1 - Bundler et serveur de développement ultra-rapide
- **Tailwind CSS** 4.2.2 - Cadre CSS utilitaire pour le styling moderne

### Animations et Interactions

- **Motion** 12.38.0 - Librairie d'animations performantes
- **Swiper** 12.1.4 - Carrousels responsifs
- **React Fast Marquee** 1.6.5 - Défilement continu

### Icons

- **React Icons** 5.6.0 - Bibliothèque d'icônes populaires
- **Remix Icon** 4.9.0 - Icônes open-source de haute qualité

### Outils de développement

- **ESLint** 9.39.4 - Linting et analyse de code
- **TypeScript Support** - Types pour React et React DOM

## Installation

### Prérequis

- Node.js (version 16 ou supérieure)
- npm ou yarn

### Étapes d'installation

1. **Cloner le repository**

   ```bash
   git clone https://github.com/Ericjason2/E-learning_website.git
   cd e-learning_website
   ```

2. **Installer les dépendances**

   ```bash
   npm install
   ```

3. **Démarrer le serveur de développement**

   ```bash
   npm run dev
   ```

4. **Ouvrir dans le navigateur**
   - Le site sera accessible à `http://localhost:5173`

## Scripts disponibles

```bash
# Démarrer le serveur de développement
npm run dev

# Créer une build de production
npm run build

# Lint le code et vérifier les erreurs
npm run lint

# Prévisualiser la build de production
npm run preview
```

## Structure du projet

```
e-learning_website/
├── src/
│   ├── components/           # Composants React réutilisables
│   │   ├── Header.jsx       # En-tête et navigation
│   │   ├── Hero.jsx         # Section héro
│   │   ├── Benefits.jsx     # Section avantages
│   │   ├── Courses.jsx      # Galerie de cours
│   │   ├── Testimonials.jsx # Témoignages des utilisateurs
│   │   ├── FaqSec.jsx       # Questions fréquemment posées
│   │   ├── Footer.jsx       # Pied de page
│   │   └── Title.jsx        # Composant titre réutilisable
│   ├── constant/
│   │   └── data.js          # Données statiques (navigation, cours, etc.)
│   ├── motion/
│   │   └── animation.js     # Configurations d'animations
│   ├── App.jsx              # Composant principal
│   ├── index.css            # Styles globaux
│   └── main.jsx             # Point d'entrée React
├── public/
│   └── images/              # Ressources statiques
├── index.html               # Fichier HTML principal
├── vite.config.js           # Configuration Vite
├── tailwind.config.js       # Configuration Tailwind CSS
├── eslint.config.js         # Configuration ESLint
└── package.json             # Dépendances et scripts
```

## Composants

### Header

Navigation principale du site avec liens vers les différentes sections (Home, Courses, About, Pricing).

### Hero

Section d'introduction avec appel à l'action pour attirer les utilisateurs.

### Benefits

Présentation des avantages et bénéfices de la plateforme.

### Courses

Galerie interactive des cours disponibles avec carrousel Swiper.

### Testimonials

Section des témoignages d'utilisateurs satisfaits.

### FaqSec

Section FAQ pour répondre aux questions courantes.

### Footer

Pied de page avec liens importants, informations de contact et réseaux sociaux.

## Styling

Le projet utilise **Tailwind CSS** pour le styling :

- Approche utilitaire pour un code CSS minimaliste
- Design responsive avec classes Tailwind
- Thème personnalisable via `tailwind.config.js`
- Google Fonts intégrées (DM Sans, Inter, Poppins)

## Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le repository
2. Créer une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Commiter vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Pousser vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## Support

Pour toute question ou problème, n'hésitez pas à ouvrir une issue sur GitHub.

**Bon apprentissage avec SkillPath!**
