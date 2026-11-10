# incremental-game

Petit jeu original jouable dans un navigateur, développé progressivement.

## Version actuelle — V0.3

- Une page entièrement blanche.
- Un bouton rond (112 px) centré, avec finition métal brossé simulée en CSS, relief, ombre et effet d'enfoncement à l'appui. Son libellé passe de « Cliquer » à « Cliqué ! » après un clic.
- Un compteur « Clics : 0 » en haut, au centre ; chaque clic l'incrémente de 1.
- Le compteur recommence à zéro au rechargement de la page (aucune sauvegarde demandée).
- Aucune autre mécanique, histoire, ressource ou progression n'a été décidée.

**Jouer :** https://kobalth13.github.io/incremental-game/

**Code :** `index.html` (HTML, CSS et JavaScript sans dépendance externe).

## Direction du projet

Références de départ : *Universal Paperclips*, *Crank* et *A Dark Room*, pour leur simplicité d'accès et leurs mécaniques évolutives. Il ne s'agit pas de les reproduire, et aucun univers ni système de jeu n'est arrêté.

**Répartition des rôles :**
- Pierre définit le concept, le contenu, les mécaniques et les changements souhaités.
- ChatGPT aide à les réaliser techniquement.
- Une idée peut être proposée, mais n'est pas ajoutée au jeu sans instruction ou accord de Pierre.
- Les changements se font pas à pas, sans fonctionnalités supplémentaires implicites.

## Méthode de travail

1. Pierre indique la modification à effectuer.
2. ChatGPT modifie uniquement les fichiers nécessaires sur GitHub.
3. Le code et les changements sont vérifiés.
4. GitHub Pages publie la branche `main` ; Pierre teste le résultat dans son navigateur.
5. Les ajustements suivent les retours de Pierre. L'historique Git permet de retrouver les versions antérieures.

**Attention :** les commits sur `main` peuvent être publiés automatiquement. La création éventuelle d'une branche de test reste un choix futur, non acté.

## Point de reprise

**État :** V0.3 : compteur de clics centré en haut ; bouton rond effet métal brossé au centre.

**Prochaine étape :** attendre la prochaine instruction de Pierre. Aucun développement supplémentaire du gameplay n'est planifié ou autorisé par déduction.
