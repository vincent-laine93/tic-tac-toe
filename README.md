# 🎮 Tic-Tac-Toe – Projet React

Ce projet est une version interactive du jeu **Morpion (Tic-Tac-Toe)** développé en **React**, basé sur le [tutoriel officiel React](https://react.dev/learn/tutorial-tic-tac-toe).
Je réalise ce projet dans le cadre de mon stage afin de me préparer a ma premiere mission qui est de développer le site internet de l'entreprise de facon dynamique et avec React
---

## 🚀 Fonctionnalités

- Grille de jeu 3x3.
- Deux joueurs s’alternent automatiquement (X et O).
- Les cases ne sont cliquables qu’une fois.
- Le jeu détecte un gagnant.
- Utilisation de `useState` pour gérer l’état du jeu.

---

## 🧠 Concepts React abordés

- **JSX** : syntaxe proche du HTML utilisée dans le rendu.
- **Composants** fonctionnels (`Square`, `Board`).
- **Props** : transmission de données de parent à enfant.
- **State immuable** : utilisation de `useState` avec `.slice()` pour ne pas modifier l’état directement.
- **Levée d’état (lift state up)** : la logique de clic est centralisée dans `Board`.
- **Hook `useState`** pour le suivi des cases et du tour du joueur.
- **Fonction `calculateWinner()`** pour déterminer le gagnant.

---

## 🏁 Lancer le projet en local

### Installation

```bash
npm install
