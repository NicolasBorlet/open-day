# Guide de Développement

## Configuration de l'Environnement

1. Node.js version spécifiée dans `.nvmrc`
2. Installation des dépendances : `npm install`
3. Lancer en développement : `npm run dev`

## Scripts Disponibles

- `npm run dev` : Lance le serveur de développement
- `npm run build` : Build pour la production
- `npm run test` : Lance les tests
- `npm run lint` : Vérifie le code avec ESLint
- `npm run format` : Formate le code avec Prettier

## Bonnes Pratiques

1. **Tests**

   - Écrire des tests pour chaque nouvelle fonctionnalité
   - Maintenir une couverture de tests > 80%

2. **Performance**

   - Optimiser les images
   - Minimiser les re-renders
   - Utiliser la compression gzip

3. **Sécurité**
   - Valider toutes les entrées utilisateur
   - Échapper le contenu dynamique
   - Maintenir les dépendances à jour
