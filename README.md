**Introduction du Projet :**
- Le projet consiste en la création d'une version numérique du jeu traditionnel de "Gomoku", également connu sous le nom de **"Five in a Row"**. Ce jeu se joue sur un plateau de 15x15 cases où deux joueurs s'affrontent en plaçant des pierres de leur couleur (noir ou blanc) pour tenter d'aligner cinq de leurs pierres consécutivement à l'horizontale, à la verticale ou en diagonale.

- Pour rendre ce projet interactif et intelligent, nous avons intégré une intelligence artificielle (IA) basée sur l'algorithme Monte Carlo Tree Search (MCTS). Cet algorithme est largement utilisé dans les jeux de stratégie, car il permet de prendre des décisions optimales en simulant un grand nombre de parties aléatoires à partir d'un état de jeu donné. MCTS est capable de déterminer le meilleur coup en évaluant les résultats possibles de chaque mouvement sur plusieurs itérations.

- En plus de l'IA MCTS, un joueur aléatoire (RandomAI) a été implémenté pour offrir un adversaire simple contre lequel tester l'IA. La combinaison de ces éléments permet non seulement de jouer contre l'ordinateur, mais aussi d'observer la manière dont l'IA choisit ses coups en temps réel.
