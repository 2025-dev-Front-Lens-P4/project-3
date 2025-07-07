# 📦 Test, qualité & bonnes pratiques

<img src="./img/testing.svg" alt="testing">

## 🎯 Objectif pédagogique
L'objectif est de **mettre en place des outils de tests**, de **s'assurer de la qualité du code**, et de **préparer le projet à la mise en production** selon les standards attendus en entreprise.

---

## 🧭 Contexte du projet
Vous avez désormais un MVP (Minimum Viable Product) de votre application codée avec React. Il est temps d’adopter une posture plus professionnelle et de renforcer la fiabilité de votre code.

Ce brief s'inscrit dans une logique de production : 
- **tests unitaires** pour vérifier le bon fonctionnement de vos composants,
- **linting** et **formatage automatique** du code,
- **analyse des performances**,
- **préparation à l’intégration continue**.

---

## 👩‍💻 Compétences visées
- **C3** : Contrôler l'exécution du code source à l’aide de tests et d’analyses statiques — niveau 3
- **C4** : Automatiser les tests unitaires et les analyses statiques avec des outils d’intégration continue — niveau 3
- **C5** : Concevoir un processus de livraison continue via des outils d’automatisation — niveau 3

---

## 📚 Modalités pédagogiques

### Étapes à suivre :
1. **Installer un outil de test (ex. : Jest, Testing Library, Vitest)**  
   - Tester au moins un composant ou une fonction
2. **Mettre en place un outil de linting (ex. : Eslint) et de formatage (ex. : Prettier)**
   - Corriger les éventuelles erreurs et configurer les règles
3. **Utiliser un outil d’analyse de performance (ex. : Lighthouse dans Chrome DevTools)**
   - Identifier un axe d'amélioration
4. **Préparer un pipeline de CI simple avec GitHub Actions**
   - Lancer les tests automatiquement à chaque push

## ⏳ Deadline
4 jours ouvrés

---

## 📦 Livrables attendus
- Un dépôt GitHub public avec :
  - une branche `main` stable
  - des tests présents et fonctionnels
  - un fichier `.github/workflows/ci.yml` pour GitHub Actions
- Un README mis à jour expliquant :
  - Comment lancer les tests
  - Quelle librairie de tests a été choisie
  - Les résultats/perfs de Lighthouse

---

## ✅ Critères de performance

| Critère           | Description                                                                 |
| ----------------- | --------------------------------------------------------------------------- |
| 🧪 Tests          | Un ou plusieurs tests unitaires sont présents et fonctionnels               |
| 🧹 Lint & Format  | Le projet passe sans erreur les outils de linting et formatage              |
| ⚙️ CI             | Une intégration continue est mise en place (ex. GitHub Actions)             |
| 📄 README         | Un README documente les outils de qualité utilisés et les résultats obtenus |
| 🚀 Performance    | Un audit Lighthouse a été réalisé et une amélioration a été apportée        |

---

## 🔗 Ressources utiles
- [Vitest](https://vitest.dev/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [GitHub Actions](https://docs.github.com/en/actions)
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)

---

## ✍️ Auteurs / contributeurs

[Rémy Cottrez](https://github.com/Azur-tsx)
