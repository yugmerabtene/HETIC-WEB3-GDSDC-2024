# Test Driven Development (TDD)

## Définition

Le Test Driven Development (TDD) est une méthode de développement où les tests sont écrits avant le code lui-même. Contrairement au Behaviour Driven Development (BDD) où le développement est guidé par des spécifications fonctionnelles, le TDD se concentre sur la validation des tests pour construire le logiciel. Cette approche favorise une meilleure qualité du produit final en garantissant que toutes les fonctionnalités sont validées par des tests unitaires.

## Fonctionnement du TDD


Le TDD suit un cycle défini :

1. **Écriture du test :** Commencez par écrire un test pour la fonctionnalité à implémenter.

2. **Exécution et validation :** Exécutez le test nouvellement écrit et vérifiez qu'il échoue, indiquant ainsi que la fonctionnalité n'est pas encore implémentée correctement.

3. **Développement :** Implémentez la fonctionnalité jusqu'à ce que le test réussisse.

4. **Refactorisation :** Réorganisez et nettoyez le code pour maintenir sa qualité et sa lisibilité.

5. **Réexécution des tests :** Assurez-vous que tous les tests, y compris les anciens, réussissent après la refactorisation.

6. **Écriture d'un nouveau test :** Ajoutez un nouveau test pour une nouvelle fonctionnalité ou un nouveau comportement.

![TDD_Global_Lifecycle](https://github.com/yugmerabtene/HETIC-WEB3-GDSDC-2023/assets/3670077/43ed0ca2-48db-4df0-9e8e-6308da16ced0)

Ce cycle itératif s'appuie sur l'écriture de tests pour guider le développement. Il est souvent résumé par l'acronyme RGR (Red Green Refactor) : Rouge (test en échec), Vert (test réussi), Refactor (refactorisation du code).

![tdd](https://github.com/yugmerabtene/HETIC-WEB3-GDSDC-2023/assets/3670077/ebb9627a-c3af-4a2b-9cf7-6d4d9a3be0de)

## TDD et tests unitaires

Le TDD est couramment associé aux tests unitaires. Contrairement au processus traditionnel où les développeurs écrivent d'abord du code puis des tests, le TDD inverse cet ordre, ce qui oblige les développeurs à écrire des tests pour chaque fonctionnalité avant même d'écrire le code correspondant.

## ATDD (Acceptance TDD)

L'Acceptance Test Driven Development (ATDD) étend la méthode TDD aux tests d'acceptance ou tests métiers. Dans ce cas, à l'instar du TDD, les tests d'acceptance sont écrits avant que le code de la fonctionnalité ne soit développé. Cela encourage une collaboration étroite entre les équipes fonctionnelles et techniques pour assurer que les exigences métier sont correctement intégrées dans les tests.

## Avantages du TDD

Le TDD offre plusieurs avantages :

- **Qualité du produit :** En garantissant que chaque fonctionnalité est testée dès sa conception, le TDD favorise une meilleure qualité du produit final.

- **Intégration à d'autres méthodes :** Le TDD se combine efficacement avec d'autres méthodes de développement incrémentiel telles que SCRUM.

- **Motivation des développeurs :** Les développeurs voient la validation des tests comme une validation de leur travail, ce qui peut renforcer leur motivation.

- **Communication améliorée :** L'ATDD encourage la communication entre les équipes fonctionnelles et techniques, réduisant ainsi les risques de mauvaises interprétations.

- **Détection précoce des bugs :** En effectuant régulièrement des tests, les bugs sont détectés plus tôt dans le processus de développement, ce qui réduit les coûts de correction.

Le TDD, bien qu'exigeant une adaptation initiale, est largement adopté pour ses nombreux avantages en matière de qualité, de collaboration et de productivité dans le développement logiciel.

**Aller plus loin :**  
Voici des explications de chaque acronyme avec des exemples :

1. **BDD (Behaviour-Driven Development)** :
   - **Définition :** Le développement axé sur le comportement consiste à écrire des spécifications comportementales sous forme de scénarios compréhensibles par tous les intervenants, puis à les traduire en tests automatisés.
   - **Exemple :** Dans un projet de développement d'une application de commerce électronique, au lieu d'écrire des tests comme "Vérifiez si l'utilisateur peut ajouter un article au panier", un scénario de BDD serait : "En tant qu'utilisateur connecté, je veux pouvoir ajouter un article à mon panier afin de procéder à l'achat".

2. **DDD (Domain-Driven Design)** :
   - **Définition :** Il s'agit d'une approche de conception logicielle basée sur un modèle métier profondément compris et reflété dans le code.
   - **Exemple :** Dans un système de gestion de bibliothèque, les concepts du domaine comme "Livres", "Auteurs", "Emprunteurs" sont représentés en tant qu'entités dans le code avec des relations et des comportements spécifiques à leur domaine.

3. **FDD (Feature-Driven Design)** :
   - **Définition :** Cette méthode de développement se concentre sur la conception par fonctionnalité, en découpant le travail en fonctionnalités gérables et en les développant de manière itérative.
   - **Exemple :** Dans le développement d'un système de gestion de projet, chaque fonctionnalité comme "Créer une tâche", "Assigner une tâche à un membre de l'équipe", etc., serait traitée comme une entité distincte avec sa propre itération de développement.

4. **HDD (Hype-Driven Development)** :
   - **Définition :** Ce type de développement se caractérise par l'adoption de technologies populaires ou à la mode sans évaluation approfondie de leur pertinence ou de leur valeur ajoutée.
   - **Exemple :** Une entreprise décide d'adopter une nouvelle technologie de blockchain simplement parce qu'elle est largement médiatisée, sans avoir identifié de cas d'utilisation concrets pour son application dans leurs produits ou services.

5. **PDD (Pain-Driven Development)** :
   - **Définition :** Cette approche de développement se concentre sur la résolution de problèmes douloureux ou sur la réponse directe à des besoins critiques identifiés par les parties prenantes.
   - **Exemple :** Une entreprise qui a subi plusieurs violations de la sécurité décide de mettre en œuvre une approche de développement orientée vers la sécurité, où chaque décision de conception est motivée par la nécessité de renforcer la sécurité des applications.
