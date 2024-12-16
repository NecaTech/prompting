# XML Circuit Processor

## Objectif
Traiter et router les différentes balises XML du système de prompting.

## Structure des Balises
```xml-circuit
<input> ──────┐
              │
<objectif> ───┼──> [PROCESSOR] ──> [VALIDATOR] ──> <output>
              │
<instructions>┘
```

## Circuits de Traitement

### 1. Circuit Input
```processor
[<input>] -> parser.md:extract_user_input
         -> analyzer.md:analyze_context
         -> validator.md:validate_input
```

### 2. Circuit Objectif
```processor
[<objectif>] -> parser.md:extract_goals
            -> analyzer.md:analyze_objectives
            -> validator.md:validate_objectives
```

### 3. Circuit Instructions
```processor
[<instructions>] -> parser.md:extract_instructions
                -> analyzer.md:analyze_rules
                -> validator.md:validate_rules
```

### 4. Circuit 4C
```processor
[Clarté] -> analyzer.md:check_clarity
[Cohérence] -> analyzer.md:check_coherence
[Contexte] -> analyzer.md:check_context
[Complétude] -> analyzer.md:check_completeness
```

## Règles de Transformation
1. Extraction des balises
   ```transform
   <balise>contenu</balise> -> {
     "type": "balise",
     "content": "contenu",
     "metadata": {}
   }
   ```

2. Validation des Relations
   ```validate
   input -> objectif : cohérence
   objectif -> instructions : alignement
   instructions -> output : complétude
   ```

## États du Processeur
- READING : Lecture des balises
- PROCESSING : Traitement du contenu
- VALIDATING : Validation des transformations
- GENERATING : Génération de l'output
- ERROR : Erreur de traitement

## Connexions avec le Core
- Router : Gestion du flux entre balises
- Analyzer : Analyse du contenu
- Validator : Validation des transformations
- Linker : Gestion des dépendances

## Format de Sortie
```output-format
{
    "input": {
        "content": string,
        "analysis": object
    },
    "objective": {
        "main": string,
        "sub_objectives": array
    },
    "instructions": {
        "4c_rules": array,
        "tasks": array,
        "validations": array
    },
    "output": {
        "structure": object,
        "content": string
    }
}
```
