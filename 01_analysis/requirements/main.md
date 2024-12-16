# Analyse des Besoins

## Objectif
Identifier et structurer tous les besoins explicites et implicites.

## Processus d'analyse
1. Extraire les besoins explicites
2. Déduire les besoins implicites
3. Prioriser les besoins
4. Identifier les dépendances

## Points d'analyse
- Objectifs principaux
- Contraintes fonctionnelles
- Contraintes non-fonctionnelles
- Critères de succès
- Dépendances

## Connexions
- Entrée : Depuis `context/main.md`
- Sortie : Vers `constraints/main.md`
- Validation : Via `core/validator.md`

## Format de sortie
```json
{
    "explicit_requirements": ["string"],
    "implicit_requirements": ["string"],
    "priorities": {
        "high": ["string"],
        "medium": ["string"],
        "low": ["string"]
    },
    "dependencies": ["string"],
    "success_criteria": ["string"]
}
```
