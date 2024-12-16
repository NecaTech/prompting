# Circuit Validator

## Objectif
Valider l'intégrité et le bon fonctionnement du circuit de génération de prompts.

## Points de Test
```circuit-test
[Entrée] -> Validation Format
   |
[Transitions] -> Validation Flux
   |
[Connexions] -> Validation Liens
   |
[Données] -> Validation Contenu
   |
[Sortie] -> Validation Finale
```

## Tests de Circuit

### 1. Test d'Intégrité
```validation
- Connexions complètes
- Pas de circuits ouverts
- Pas de courts-circuits
- Flux unidirectionnel respecté
```

### 2. Test de Flux
```validation
- Données correctement formatées
- Transitions valides
- États cohérents
- Pas de blocages
```

### 3. Test de Données
```validation
- Format correct
- Contenu cohérent
- Transformations valides
- Pas de perte d'information
```

## États de Validation
- PASS : Test réussi
- FAIL : Test échoué
- WARN : Attention requise
- SKIP : Test ignoré

## Actions Correctives
1. Identification du point d'échec
2. Diagnostic du problème
3. Proposition de correction
4. Revalidation après correction

## Rapport de Validation
```report
{
    "circuit_id": "string",
    "timestamp": "datetime",
    "status": "PASS|FAIL|WARN|SKIP",
    "tests": [{
        "name": "string",
        "status": "PASS|FAIL|WARN|SKIP",
        "message": "string"
    }],
    "corrections_needed": ["string"]
}
```

## Prochain Nœud
Déterminé par le résultat de la validation :
- Si PASS -> Prochain module
- Si FAIL -> Retour au point d'échec
- Si WARN -> Vérification manuelle requise
