# Composants de Prompt

## Objectif
Fournir des blocs de construction réutilisables pour construire des prompts.

## Types de Composants

### 1. Composants de Contexte
```component
[Contexte Technique]
{technical_context}

[Contexte Business]
{business_context}
```

### 2. Composants d'Instruction
```component
[Instruction Principale]
{main_instruction}

[Sous-Instructions]
{sub_instructions}
```

### 3. Composants de Contrainte
```component
[Contraintes Techniques]
{technical_constraints}

[Contraintes de Format]
{format_constraints}
```

### 4. Composants de Validation
```component
[Critères de Succès]
{success_criteria}

[Points de Vérification]
{checkpoints}
```

## Connexions
- Entrée : Depuis `templates/main.md`
- Sortie : Vers `format/main.md`
- Validation : Via `core/validator.md`

## Règles d'Assemblage
1. Commencer par le contexte
2. Ajouter les instructions
3. Spécifier les contraintes
4. Inclure les validations
