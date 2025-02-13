# Conventions de Code

## Général

- Indentation : 2 espaces
- Fin de ligne : LF
- Encodage : UTF-8
- Pas de trailing whitespace
- Une ligne vide en fin de fichier

## JavaScript/TypeScript

- Utiliser `const` par défaut, `let` si nécessaire
- Pas de `var`
- Toujours terminer les instructions par des point-virgules
- Utiliser les template literals plutôt que la concaténation
- Préférer les fonctions fléchées
- Destructuring pour les props React

## React

- Un composant par fichier
- Composants fonctionnels avec hooks
- Props typées avec TypeScript
- Extraction des handlers dans des fonctions nommées
- Éviter les inline styles

## Tests

- Un fichier de test par composant/module
- Nommage : `[nom].test.tsx`
- Utiliser des descriptions claires
- Grouper les tests logiquement
