# Analyse du Contexte

## Objectif
Extraire et comprendre le contexte complet de la demande.

## Processus d'analyse
1. Identifier le domaine principal
2. Détecter le niveau de complexité
3. Repérer les références implicites
4. Établir le cadre temporel

## Éléments à extraire
- Domaine d'application
- Contexte technique
- Contexte business
- Contraintes temporelles
- Références externes

## Connexions
- Entrée : Données du `core/parser.md`
- Sortie : Vers `requirements/main.md`
- Validation : Via `core/validator.md`

## Format de sortie
```json
{
    "domain": "string",
    "complexity": "low|medium|high",
    "technical_context": ["string"],
    "business_context": ["string"],
    "temporal_constraints": ["string"],
    "external_references": ["string"]
}
```
