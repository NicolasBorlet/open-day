# Guide de Style

## Structure des Composants React

- Un composant par fichier
- Utiliser la syntaxe des composants fonctionnels avec TypeScript
- Nommer les fichiers en PascalCase (ex: `UserProfile.tsx`)

## Conventions CSS

- Utiliser CSS Modules ou Styled Components
- Nommer les classes en kebab-case
- Éviter les styles globaux
- Utiliser des variables CSS pour les couleurs et les dimensions récurrentes

## TypeScript

- Toujours définir les types explicitement
- Éviter `any`
- Utiliser des interfaces pour les props des composants
- Nommer les interfaces avec un préfixe 'I' (ex: `IUserProps`)

## Imports

- Grouper les imports par catégorie :
  1. Imports React/externes
  2. Imports composants
  3. Imports utils/helpers
  4. Imports styles
