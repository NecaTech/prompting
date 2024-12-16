# Few-Shot Learning Processor

## Objectif
Utiliser des exemples pertinents pour guider la génération de prompts.

## Types d'Exemples

### 1. Exemples Directs
```examples
[Situation similaire] -> [Solution appliquée] -> [Résultat obtenu]
```

### 2. Exemples Contrastés
```examples
[Bon exemple] vs [Mauvais exemple] -> [Différences clés]
```

### 3. Exemples Progressifs
```examples
[Simple] -> [Intermédiaire] -> [Complexe]
```

## Structure d'Apprentissage
```learning-pattern
1. Présentation des exemples
2. Identification des patterns
3. Extraction des principes
4. Application au cas présent
```

## Format d'Implémentation
```template
Considérons ces exemples pertinents :

1. Premier exemple :
   Situation : {situation_1}
   Solution : {solution_1}
   Résultat : {result_1}

2. Deuxième exemple :
   Situation : {situation_2}
   Solution : {solution_2}
   Résultat : {result_2}

Principes extraits :
{extracted_principles}

Application à notre cas :
{current_case_application}
```

## Connexions
- Entrée : Depuis analyzer.md
- Validation : Via validator.md
- Sortie : Vers le prochain processeur
