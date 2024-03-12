# Test Driven Development (TDD)

## Définition

Le Test Driven Development (TDD) est une méthode de développement où les tests sont écrits avant le code lui-même. Contrairement au Behaviour Driven Development (BDD) où le développement est guidé par des spécifications fonctionnelles, le TDD se concentre sur la validation des tests pour construire le logiciel. Cette approche favorise une meilleure qualité du produit final en garantissant que toutes les fonctionnalités sont validées par des tests unitaires.

## Fonctionnement du TDD
![TDD_Global_Lifecycle](https://github.com/yugmerabtene/HETIC-WEB3-GDSDC-2023/assets/3670077/43ed0ca2-48db-4df0-9e8e-6308da16ced0)

Le TDD suit un cycle défini :

1. **Écriture du test :** Commencez par écrire un test pour la fonctionnalité à implémenter.

2. **Exécution et validation :** Exécutez le test nouvellement écrit et vérifiez qu'il échoue, indiquant ainsi que la fonctionnalité n'est pas encore implémentée correctement.

3. **Développement :** Implémentez la fonctionnalité jusqu'à ce que le test réussisse.

4. **Refactorisation :** Réorganisez et nettoyez le code pour maintenir sa qualité et sa lisibilité.

5. **Réexécution des tests :** Assurez-vous que tous les tests, y compris les anciens, réussissent après la refactorisation.

6. **Écriture d'un nouveau test :** Ajoutez un nouveau test pour une nouvelle fonctionnalité ou un nouveau comportement.

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
