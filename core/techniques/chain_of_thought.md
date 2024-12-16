# Chain of Thought (CoT) Processor

## Objectif
Implémenter le raisonnement pas à pas dans la génération de prompts.

## Méthodes d'Implémentation

### 1. Zero-shot CoT
```circuit
[Problème] -> [Réflexion étape par étape] -> [Conclusion]
```

### 2. Few-shot CoT
```circuit
[Exemples similaires] -> [Pattern de raisonnement] -> [Application au cas présent]
```

### 3. Self-consistency CoT
```circuit
[Multiple raisonnements] -> [Agrégation] -> [Solution optimale]
```

## Patterns de Raisonnement
```thought-pattern
1. Décomposition du problème
2. Analyse de chaque composant
3. Identification des relations
4. Synthèse progressive
5. Validation logique
```

## Intégration dans le Prompt
```template
Raisonnons étape par étape :

1. Compréhension initiale :
   - Contexte : {context}
   - Objectif : {objective}

2. Analyse des composants :
   {component_analysis}

3. Développement logique :
   {logical_steps}

4. Synthèse et validation :
   {synthesis}

5. Conclusion :
   {conclusion}
```

## Connexions
- Entrée : Depuis analyzer.md
- Validation : Via validator.md
- Sortie : Vers le prochain processeur
