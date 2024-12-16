# Analyse des Contraintes

## Objectif
Identifier et cataloguer toutes les contraintes applicables.

## Types de contraintes
1. Contraintes techniques
2. Contraintes de format
3. Contraintes de longueur
4. Contraintes de style
5. Contraintes de sécurité

## Processus d'analyse
1. Extraire les contraintes explicites
2. Identifier les contraintes implicites
3. Valider la compatibilité
4. Définir les limites

## Connexions
- Entrée : Depuis `requirements/main.md`
- Sortie : Vers `core/router.md` pour la phase suivante
- Validation : Via `core/validator.md`

## Format de sortie
```json
{
    "technical_constraints": {
        "must_have": ["string"],
        "must_not_have": ["string"]
    },
    "format_constraints": ["string"],
    "length_constraints": {
        "min": "number",
        "max": "number",
        "optimal": "number"
    },
    "style_constraints": ["string"],
    "security_constraints": ["string"]
}
```

## Prochain module
Retour au `core/router.md` pour transition vers `02_structure`
