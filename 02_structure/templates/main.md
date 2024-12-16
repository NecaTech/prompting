# Templates de Prompts

## Objectif
Fournir des structures de base adaptables pour différents types de prompts.

## Types de Templates
1. Instruction simple
2. Analyse complexe
3. Génération créative
4. Question-réponse
5. Conversation multi-tours

## Structure de Base
```template
[Contexte]
{context_placeholder}

[Objectif]
{objective_placeholder}

[Contraintes]
{constraints_placeholder}

[Format de Sortie Attendu]
{output_format_placeholder}

[Instructions Spécifiques]
{specific_instructions_placeholder}
```

## Connexions
- Entrée : Depuis `core/router.md`
- Sortie : Vers `components/main.md`
- Validation : Via `core/validator.md`

## Sélection de Template
Utiliser les données d'analyse pour choisir le template le plus approprié :
- Complexité de la demande
- Type de sortie attendue
- Niveau de détail requis
