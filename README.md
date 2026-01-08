# 🎯 Jeu du Pendu - C++

Un jeu du pendu classique développé en **C++** pour console. Devinez le mot mystère lettre par lettre avant que le pendu ne soit complété !

## 🎮 Description

Le Pendu est un jeu de devinettes où le joueur doit trouver un mot caché en proposant des lettres. Chaque erreur rapproche le dessin du pendu de sa complétion. Le joueur doit deviner le mot avant d'épuiser toutes ses chances !

## 🎯 Objectif

- 🔤 Devinez le mot mystère lettre par lettre
- ⚠️ Vous avez un nombre limité d'erreurs
- 🏆 Trouvez le mot avant que le pendu soit complété
- 💯 Essayez de gagner avec le moins d'erreurs possible

## 🕹️ Comment Jouer

1. Le jeu choisit un mot aléatoire
2. Vous voyez le nombre de lettres du mot (représentées par des underscores `_`)
3. Proposez une lettre
4. Si la lettre est dans le mot, elle apparaît à sa position
5. Si la lettre n'est pas dans le mot, vous perdez une vie
6. Continuez jusqu'à deviner le mot ou perdre toutes vos vies

## ✨ Fonctionnalités

- 🎲 **Mots aléatoires** - Base de mots variée
- 💀 **Compteur de vies** - Nombre d'erreurs autorisées
- 🎨 **Affichage du pendu** - Visualisation graphique ASCII
- ✅ **Validation des entrées** - Vérification des lettres déjà proposées
- 📊 **Affichage du progrès** - Visualisation du mot en cours
- 🔄 **Rejouer** - Possibilité de relancer une partie
- 📝 **Historique des lettres** - Liste des lettres déjà proposées

## 🛠️ Technologies Utilisées

- **C++** - Langage de programmation
- **Standard Library** - iostream, string, vector, algorithm
- **Console Application** - Interface texte

## 🚀 Installation et Compilation

### Prérequis
- Compilateur C++ (g++, MinGW, MSVC, etc.)
- Système d'exploitation : Windows, Linux, ou macOS

### Compilation

#### Windows (MinGW)
```bash
# Clonez le repository
git clone https://github.com/AS0-69/jeu-du-pendu.git

# Accédez au dossier
cd jeu-du-pendu

# Compilez le programme
g++ -o pendu.exe pendu.cpp

# Exécutez le jeu
./pendu.exe
```

#### Linux / macOS
```bash
# Clonez le repository
git clone https://github.com/AS0-69/jeu-du-pendu.git

# Accédez au dossier
cd jeu-du-pendu

# Compilez le programme
g++ -o pendu pendu.cpp

# Exécutez le jeu
./pendu
```

#### Visual Studio (Windows)
```bash
# Ouvrez le fichier pendu.cpp dans Visual Studio
# Appuyez sur Ctrl+F5 pour compiler et exécuter
```

## 💻 Exemple de Partie

```
╔════════════════════════════════════╗
║      JEU DU PENDU - C++           ║
╚════════════════════════════════════╝

Mot à deviner : _ _ _ _ _ _ _
Vies restantes : 7

Proposez une lettre : e

Bravo ! La lettre 'e' est dans le mot.
Mot à deviner : _ _ _ _ e _ _
Vies restantes : 7
Lettres essayées : e

Proposez une lettre : a

Dommage ! La lettre 'a' n'est pas dans le mot.
   ___
   |  
   |  
   |  
   |  
   |__

Mot à deviner : _ _ _ _ e _ _
Vies restantes : 6
Lettres essayées : e, a
```

## 📝 Règles du Jeu

1. **Début du jeu** : Un mot est choisi au hasard
2. **Proposition** : Entrez UNE lettre à la fois
3. **Bonne réponse** : La lettre apparaît dans le mot
4. **Mauvaise réponse** : Le pendu se dessine progressivement
5. **Victoire** : Vous devinez le mot complet
6. **Défaite** : Le pendu est complété (toutes les vies perdues)

## 🎲 Catégories de Mots

Le jeu peut inclure différentes catégories :
- 🍎 Fruits et légumes
- 🦁 Animaux
- 🌍 Pays et villes
- 💻 Informatique et technologie
- ⚽ Sports
- 🎬 Cinéma et culture

## 🎯 Stratégies pour Gagner

1. 💡 **Commencez par les voyelles** (A, E, I, O, U)
2. 📊 **Lettres fréquentes** - E, A, I, S, N, R, T
3. 🧩 **Observez la longueur** du mot
4. 🔤 **Analysez les patterns** de lettres
5. 🎯 **Évitez les lettres rares** au début (K, W, X, Z)

## 🔧 Personnalisation

Vous pouvez modifier le code pour :
- 📝 Ajouter vos propres mots
- 🎨 Changer le dessin du pendu
- ⚡ Ajuster le nombre de vies
- 🎲 Ajouter des niveaux de difficulté
- 🏆 Implémenter un système de score

## 📊 Niveaux de Difficulté (selon implémentation)

- 🟢 **Facile** : Mots courts (4-6 lettres), 10 vies
- 🟡 **Moyen** : Mots moyens (6-8 lettres), 7 vies
- 🔴 **Difficile** : Mots longs (8+ lettres), 5 vies
- ⚫ **Expert** : Mots complexes, 3 vies

## 🚧 Améliorations Possibles

- [ ] Interface graphique (GUI)
- [ ] Multijoueur en ligne
- [ ] Base de données de mots étendue
- [ ] Système de hints (indices)
- [ ] Statistiques de jeu (victoires/défaites)
- [ ] Timer pour limiter le temps
- [ ] Mode thématique (choix de catégories)
- [ ] Sauvegarde du meilleur score

## 🎓 Concepts Informatiques Utilisés

- **Tableaux et strings** - Manipulation de chaînes
- **Boucles** - Logique de jeu répétitive
- **Conditions** - Vérifications et validations
- **Fonctions** - Organisation du code
- **Random** - Sélection aléatoire de mots
- **Input/Output** - Interaction utilisateur

## 👨‍💻 Auteur

**AS0** - [GitHub Profile](https://github.com/AS0-69)

## 📄 Licence

Ce projet est open source et disponible pour tous.

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :
1. Fork le projet
2. Créez votre branche (`git checkout -b feature/amelioration`)
3. Commit vos changements (`git commit -m 'Ajout fonctionnalité'`)
4. Push (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

---

⭐ **Si vous aimez ce jeu, n'oubliez pas de mettre une étoile !** ⭐

🎮 Bon jeu et amusez-vous bien !
