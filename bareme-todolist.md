# Barême



Respect du cahier des charges : 10pts

- [ ] Correspondre aux maquettes
- [ ] Afficher une liste de tâches
- [ ] Ajouter une tâche
- [ ] Filtrer les tâches : "tâches faites" / "toutes les tâches"
- [ ] Cocher une tâche
- [ ] Compter les tâches restantes
- [ ] Fonctionne sur un téléphone ou un émulateur (android ou iOS)



Qualité du code : 5pts

- [ ] Concision, WET (Write Everything Twice)
- [ ] Facilité de compréhension et nommage
- [ ] Mise en page et indentation (prettier)
- [ ] Équilibre signal / bruit (code inutilisé, commentaires redondants, opportunités d'abstraction manquées…)



Ergonomie et accessibilité : 3pts

- [ ] Esthétique
- [ ] Sémantique, navigable au clavier, respect des normes
- [ ] Compréhension et lisibilité de l'interface
- [ ] Textes explicites, orthographe



Qualité des commits : 2pts

- [ ] Des commits atomiques
- [ ] Des commits bien nommés



Pertes de points :

- code smell (code trop compliqué ou pouvant introduire des bugs potentiels)

- bugs
  - mineurs (comportement inattendu mais marche quand même)
  - moyens (empêche l'accomplissement d'une tâche mais on peut y arriver par un moyen détourné)
  - majeurs (empêche l'accomplissement d'une tâche)



Bonus de +1pts par fonctionnalité en plus :

- [ ] persistence des données
- [ ] permettre l'édition d'une tâche
- [ ] permettre la suppression définitive d'une tâche
- [ ] ajout d'une colonne "fait"
- [ ] écrit avec typescript en mode strict