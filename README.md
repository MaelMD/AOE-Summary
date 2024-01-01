# Advanced Objet Engineering - Ingénierie avancé objet

# Advanced Objet Engineering - Ingénierie avancée objet

## Sommaire
1. [Résumé du Chapitre 1 - "Ingénierie Avancée Objet"](#chapitre-1)
2. [Résumé du Chapitre 2 - "Clean Code et Principes SOLID"](#chapitre-2)
3. [Résumé du Chapitre 3 - "Design Patterns"](#chapitre-3)
4. [Résumé du Chapitre 4 - "Métriques Orientées Objets"](#chapitre-4)

## Résumé du Chapitre 1 - "Ingénierie Avancée Objet" <a name="chapitre-1"></a>
### Introduction
- **Définition du Logiciel :** Un logiciel est un ensemble d'entités nécessaires au traitement automatique de l'information, incluant des programmes, des documentations d'utilisation, et des informations de configuration.
- **Interaction et Spécification :** Un logiciel est un sous-système qui interagit avec divers clients, y compris des opérateurs humains, d'autres logiciels, et des contrôleurs matériels. Il doit respecter un ensemble de critères spécifiés.

### Développement de Logiciel
- **Processus :** Transformation d'une idée ou d'un besoin en un logiciel fonctionnel.
- **Rôles :** L'idée est produite par un client et développée par un fournisseur, pouvant être la même entité.
- **Perspectives Client et Fournisseur :** Un bon logiciel est peu coûteux, respecte les critères de qualité, est livré dans les délais, et réalise les fonctions demandées.

### Génie Logiciel
- **Définition :** Ensemble de méthodes, techniques et outils pour la production d'un logiciel.
- **Objectifs :** Satisfaire client et fournisseur, qualité supérieure, délais raisonnables, coûts acceptables.
- **Domaines Associés :** Exigences, conception, construction, tests, maintenance, gestion de configuration, ingénierie de gestion logicielle, ingénierie des processus logiciels, outils et méthodes logiciels, assurance qualité.

### Qualité et Maintenance du Logiciel
- **Critères de Qualité :** Utilité, utilisabilité, fiabilité, interopérabilité, performance, portabilité, réutilisabilité, facilité de maintenance.
- **Types de Maintenance :** Corrective (corriger les erreurs), adaptative (ajuster aux évolutions), évolutive (accroître les possibilités), avec des stratégies pour minimiser la maintenance corrective et rendre les autres maintenances moins coûteuses.

### Cycle de Vie du Logiciel
- **Étapes :** Étude de faisabilité, spécification, organisation du projet, conception, implémentation, tests, livraison.
- **Importance :** Contrôler la succession des différentes étapes pour garantir la qualité du logiciel.

### Conception Orientée Objet
- **Analyse et Conception :** Passage de l'approche Métier (analyse) à l'approche informatique (conception).
- **Principes :** Encapsulation, héritage, polymorphisme.
- **Décomposition en Objets :** Tâche essentielle et difficile, nécessitant la prise en compte de plusieurs facteurs comme l'encapsulation, la granularité, la dépendance, la performance, et la réutilisabilité.
- **Interfaces et Polymorphisme :** Importance de l'interface d'un objet, permettant la réalisation du polymorphisme.

### Réutilisation et Paradigme Objet
- **Techniques de Réutilisation :** Héritage (boîte blanche) et composition (boîte noire).
- **Promesses du Paradigme Objet :** Développabilité, extensibilité, maintenabilité, réutilisabilité, mais attention aux périls liés à une mauvaise utilisation du paradigme.
- **Conclusion :** Nécessité de s'appuyer sur le savoir-faire et les principes de conception pour développer des logiciels extensibles, maintenables et réutilisables.

## Résumé du Chapitre 2 - "Clean Code et Principes SOLID" <a name="chapitre-2"></a>
### Introduction au Clean Code
- **Concept :** Art d'écrire un code source lisible, compréhensible et maintenable.
- **Importance :** Améliore

 la maintenabilité, facilite la collaboration, réduit les bugs, et contribue à la qualité du logiciel.
- **Citation :** "Clean code is simple and direct. Clean code reads like well-written prose." - Robert C. Martin

### Principes du Clean Code
- **Lisibilité :** Compréhension facile par d'autres développeurs.
- **Simplicité :** Éviter la complexité inutile.
- **Modularité :** Créer de petites unités de code autonomes.
- **Cohérence :** Suivre des conventions de codage uniformes.

### Techniques de Codage Propre
- **Noms de Variables et Fonctions :** Utiliser des noms significatifs et descriptifs.
- **Indentation :** Respecter une indentation propre et cohérente.
- **Fonctions :** Diviser les fonctions longues en fonctions plus petites.
- **Conventions de Nommage :** Utiliser camelCase, snake_case, PascalCase, etc., de manière appropriée.

### Gestion des Exceptions et Tests
- **Exceptions :** Préférer les exceptions pour gérer les erreurs.
- **Tests :** Les tests unitaires pour assurer la fonctionnalité du code.

### Outils pour le Clean Code
- **Outils :** ESLint, Prettier, Black, SonarQube.
- **Utilisation :** Aider à maintenir la propreté et la qualité du code.

### Défis du Clean Code
- **Défis :** Délais serrés, compromis sur la qualité.
- **Solutions :** Planification, sensibilisation, éducation.

### Principes SOLID
- **S :** Single Responsibility Principle (Principe de responsabilité unique).
- **O :** Open-Closed Principle (Principe d'ouverture / fermeture).
- **L :** Liskov Substitution Principle (Principe de substitution de Liskov).
- **I :** Interface Segregation Principle (Principe de ségrégation des interfaces).
- **D :** Dependency Inversion Principle (Principe d'inversion des dépendances).

### Conclusion
- **Application :** Ces principes et règles ne sont pas absolus mais doivent être considérés lors du développement pour une conception efficace et de haute qualité.

### Résumé du Chapitre 3 - "Design Patterns"

#### Objectifs des Design Patterns
- **Modularité, Facilité de Gestion :** Utilisation de la technologie objet pour améliorer la modularité et la gestion.
- **Cohésion et Couplage :** Viser une forte cohésion et un couplage lâche pour une meilleure qualité logicielle.
- **Réutilisabilité :** Utiliser des bibliothèques et des frameworks pour faciliter la réutilisabilité.

#### Définition et Utilité
- **Pattern :** Solution réutilisable à un problème fréquent dans un contexte donné, sans être adaptée deux fois de la même manière.
- **Documentation de Conception Expérimentée :** Fournit un vocabulaire commun et facilite la compréhension des principes de conception.

#### Catégories de Design Patterns
- **Architectural Patterns :** Schémas d'organisation structurelle de logiciels.
- **Design Patterns :** Structures de conception communes à plusieurs applications.
- **Idioms ou Coding Patterns :** Solutions liées à un langage spécifique.
- **Anti-Patterns :** Mauvaises solutions ou comment s'en échapper.
- **Organizational Patterns :** Schémas d'organisation du développement logiciel.

#### Catégories de Design Pattern
- **Création :** Gestion de la création, l'initialisation, et la configuration d'objets.
- **Structure :** Connexion d'objets pour indépendance face aux évolutions.
- **Comportement :** Interaction et dynamiques entre classes et objets.

#### Présentation d'un Design Pattern
- **Nom :** Identification concise du pattern.
- **Problème :** Contexte et conditions d'application.
- **Solution :** Description des éléments de conception de la solution, incluant des diagrammes.
- **Conséquences :** Effets positifs et négatifs de l'application du pattern.

#### Exemples de Design Patterns
- **Singleton :** Assurer une seule instance d'une classe avec accès global.
- **Factory Method :** Standardiser la création d'objets tout en permettant des personnalisations.
- **Abstract Factory :** Travailler avec des familles de produits tout en étant indépendant de leurs types.
- **Builder :** Séparer la création d'un objet complexe de sa représentation.
- **Prototype :** Utiliser la copie d'une instance existante plutôt que de créer une nouvelle.

#### Résumé
- Les Design Patterns offrent des solutions structurées pour des problèmes de conception courants, facilitant le développement de logiciels plus robustes, maintenables et évolutifs.


### Résumé du Chapitre 4 - "Métriques Orientées Objets"

#### Problématique des Métriques
- **Importance :** Les métriques sont essentielles pour évaluer la qualité des logiciels, particulièrement dans les projets de grande envergure.
- **Défi :** Trouver un équilibre entre coût, efficacité et satisfaction des besoins clients.

#### Métriques de Chidamber et Kemerer (CK)
- **Suite de Métriques pour la Conception Orientée Objet :** Évaluation des classes d'un système.
- **Principales Métriques :**
  - **M1 : Méthodes Pondérées par Classe (WMC) :** Mesure la complexité d'une classe.
  - **M2 : Profondeur de l'Arbre d'Héritage (DIT) :** Distance entre une classe et la racine de l'arbre d'héritage.
  - **M3 : Nombre d'Enfants (NOC) :** Nombre de sous-classes directes.
  - **M4 : Couplage Entre les Classes (CBO) :** Mesure le degré d'interdépendance entre les classes.
  - **M5 : Réponse pour une Classe (RFC) :** Nombre de méthodes pouvant être exécutées en réponse à un message.
  - **M6 : Manque de Cohésion des Méthodes (LCOM) :** Mesure la cohésion au sein d'une classe.

#### Métriques MOOD
- **Objectif :** Évaluer les attributs de la programmation orientée objet comme l'encapsulation, l'héritage, le couplage, et le polymorphisme.
- **Métriques Clés :**
  - **Encapsulation :** Facteurs de Cachette de Méthodes (MHF) et d'Attributs (AHF).
  - **Héritage :** Facteurs d'Héritage de Méthodes (MIF) et d'Attributs (AIF).
  - **Couplage :** Facteur de Couplage (CF).
  - **Polymorphisme :** Facteur de Polymorphisme (PF).

#### État Actuel des Métriques
- **Usage Minoritaire :** L'utilisation des métriques reste peu répandue dans l'industrie.
- **Défis :** Ambiguïté des concepts et manque de base théorique solide.
- **Conclusion :** Nécessité d'améliorer la compréhension et l'application des métriques pour une meilleure gestion de la qualité logicielle.
