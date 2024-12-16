# Zero-Shot Learning Processor

## Objectif
Générer des prompts efficaces sans exemples préalables.

## Principes Fondamentaux

### 1. Clarté des Instructions
```instruction-pattern
[Contexte précis] -> [Objectif clair] -> [Contraintes explicites]
```

### 2. Décomposition Structurée
```decomposition
1. Définition du problème
2. Critères de succès
3. Contraintes spécifiques
4. Format attendu
```

### 3. Guidage Implicite
```guidance
- Questions directrices
- Points de contrôle
- Critères de validation
- Formats de sortie
```

## Structure de Prompt
```template
Contexte :
{detailed_context}

Objectif :
{clear_objective}

Instructions spécifiques :
1. {instruction_1}
2. {instruction_2}
3. {instruction_3}

Format de sortie attendu :
{output_format}

Critères de validation :
{validation_criteria}
```

## Connexions
- Entrée : Depuis analyzer.md
- Validation : Via validator.md
- Sortie : Vers le prochain processeur
