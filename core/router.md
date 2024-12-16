# Circuit Router

Ce router détermine le chemin d'exécution à suivre en fonction de la demande.

## Analyse de la demande
1. Lire le contenu de `input.md`
2. Identifier le type de prompt requis
3. Déterminer la séquence de modules à exécuter

## Objectif
Contrôler et diriger le flux de données à travers le circuit du framework.

## Circuit Principal
```circuit
[ENTRÉE] -> parser -> analyzer -> [MODULES] -> validator -> [SORTIE]
```

## Table de Routage
```routing
1. Entrée -> core/parser.md
2. Parser -> core/analyzer.md
3. Analyzer -> Modules selon analyse
4. Modules -> core/validator.md
5. Validator -> Module suivant ou sortie
```

## Routes disponibles
- Route Analyse → `01_analysis/context`
- Route Structure → `02_structure/templates`
- Route Enhancement → `03_enhancement/rules`

## Points de Décision
1. Analyse initiale
   ```decision
   Si demande_complexe -> circuit_analyse_complet
   Si demande_simple -> circuit_analyse_rapide
   ```

2. Structure
   ```decision
   Si template_standard -> circuit_template_direct
   Si template_personnalisé -> circuit_components
   ```

3. Enhancement
   ```decision
   Si optimisation_requise -> circuit_enhancement_complet
   Si déjà_optimisé -> circuit_validation
   ```

## Règles de routage
1. Toujours commencer par l'analyse du contexte
2. Suivre les dépendances définies dans `linker.md`
3. Valider chaque transition avec `validator.md`

## Gestion du Flux
1. Contrôle de la direction
2. Gestion des bifurcations
3. Synchronisation des circuits parallèles
4. Détection des boucles infinies

## États du Circuit
- INIT : Circuit initialisé
- FLOW : Flux en cours
- WAIT : Attente de validation
- DONE : Circuit complété
- ERROR : Erreur détectée

## Prochain Nœud
Déterminé par :
1. État actuel du circuit
2. Résultats de l'analyse
3. Validations précédentes

## Prochain module
Diriger vers `core/parser.md` pour l'analyse initiale
