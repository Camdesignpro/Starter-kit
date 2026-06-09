# 🎨 Design System Starter Kit

Un starter kit prêt à l'emploi pour créer, maintenir et faire évoluer un Design System scalable et cohérent.

## 🚀 Objectif

Ce projet fournit les fondations nécessaires pour construire un Design System moderne :

- Composants UI réutilisables
- Design Tokens centralisés
- Documentation interactive
- Bonnes pratiques d'accessibilité
- Architecture scalable
- Intégration CI/CD

---

## 📦 Contenu

### Design Tokens

Les tokens constituent la source unique de vérité pour :

- Couleurs
- Typographie
- Espacements
- Ombres
- Bordures
- Breakpoints
- Animations

```text
tokens/
├── colors.json
├── typography.json
├── spacing.json
├── shadows.json
└── breakpoints.json
```

### Composants

```text
src/
├── components/
│   ├── Button/
│   ├── Input/
│   ├── Card/
│   ├── Modal/
│   └── ...
```

Chaque composant contient :

```text
Button/
├── Button.tsx
├── Button.types.ts
├── Button.test.tsx
├── Button.stories.tsx
└── index.ts
```

### Documentation

Documentation générée avec Storybook.

Fonctionnalités :

- Catalogue des composants
- Playground interactif
- Documentation des props
- Tests visuels

---

## 🛠️ Stack technique

- React
- TypeScript
- Storybook
- Sass / CSS Modules
- Vitest
- ESLint
- Prettier

---

## 📥 Installation

```bash
git clone <repository-url>
cd design-system-starter-kit

npm install
```

---

## ▶️ Démarrage

Lancer Storybook :

```bash
npm run storybook
```

Lancer l'application :

```bash
npm run dev
```

Exécuter les tests :

```bash
npm run test
```

---

## 🏗️ Architecture

```text
design-system/
├── src/
│   ├── components/
│   ├── foundations/
│   ├── hooks/
│   ├── utils/
│   └── index.ts
│
├── tokens/
│
├── docs/
│
├── .storybook/
│
└── tests/
```

---

## ♿ Accessibilité

Tous les composants doivent respecter :

- WCAG 2.1 AA
- Navigation clavier
- Compatibilité lecteurs d'écran
- Gestion des contrastes

---

## 🎯 Conventions

### Nommage des composants

```tsx
<Button />
<TextField />
<IconButton />
```

### Export

```tsx
export { Button } from "./Button";
export type { ButtonProps } from "./Button.types";
```

---

## 🧪 Tests

Chaque composant doit inclure :

- Tests unitaires
- Tests d'accessibilité
- Stories Storybook

Objectif minimal :

```text
Coverage > 80%
```

---

## 📚 Documentation

Avant toute contribution :

1. Créer ou mettre à jour les stories.
2. Documenter les props.
3. Ajouter les cas d'usage.
4. Vérifier l'accessibilité.

---

## 🤝 Contribution

1. Créer une branche :

```bash
git checkout -b feature/new-component
```

2. Développer le composant.
3. Ajouter les tests.
4. Ajouter la documentation.
5. Soumettre une Pull Request.

---

## 🗺️ Roadmap

- [ ] Dark Mode
- [ ] Design Tokens multi-thèmes
- [ ] Génération Figma ↔ Tokens
- [ ] Tests visuels automatisés
- [ ] Publication NPM

---

## 📄 Licence

MIT

---

## 👥 Maintainers

Équipe Design System

Pour toute question ou suggestion, ouvrir une Issue ou contacter l'équipe de maintenance.
