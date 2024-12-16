# Instructions pour l'Assistant IA

## RÈGLES FONDAMENTALES

### 1. Règles Absolues
- **TOUJOURS** commencer par lire `input.md`
- **TOUJOURS** générer les prompts en français
- **TOUJOURS** suivre le workflow complet
- **TOUJOURS** valider chaque étape

### 2. Structure du Framework
```yaml
framework:
  répertoires:
    - core/: "Composants fondamentaux du système"
    - output/: "Prompts générés"
    - docs/: "Documentation"
```

## PROCESSUS DE GÉNÉRATION

### 1. Lecture de la Demande
```yaml
étape_initiale:
  fichier: "input.md"
  actions:
    - Lire intégralement la demande
    - Identifier les objectifs principaux
    - Noter les contraintes spécifiques
  validation:
    - Vérifier la complétude
    - Confirmer la compréhension
```

### 2. Workflow Obligatoire
```yaml
séquence_workflow:
  1. input.md:
     - localisation: "./"
     - action: "Lecture demande utilisateur"
     - validation: "Compréhension complète"
     
  2. core/circuit_manager.md:
     - localisation: "./core/"
     - action: "Initialisation du circuit"
     - validation: "Configuration correcte"
     
  3. core/context_management.md:
     - localisation: "./core/"
     - action: "Analyse du contexte"
     - validation: "Contexte établi"
     
  4. core/adaptation_patterns.md:
     - localisation: "./core/"
     - action: "Sélection patterns"
     - validation: "Patterns appropriés"
     
  5. core/unified_processor.md:
     - localisation: "./core/"
     - action: "Traitement demande"
     - validation: "Traitement complet"
     
  6. core/unified_metrics.md:
     - localisation: "./core/"
     - action: "Validation qualité"
     - validation: "Métriques conformes"
```

### 3. Validation du Processus
```yaml
validation_processus:
  utilisation:
    - core/process_validator.md: "Validation de chaque étape"
    
  points_contrôle:
    - Avant chaque étape: "Pré-conditions"
    - Pendant l'étape: "Exécution"
    - Après l'étape: "Post-conditions"
    
  documentation:
    - Logs complets
    - Rapport d'exécution
    - Traçabilité
```

## GÉNÉRATION DU PROMPT

### 1. Structure du Prompt
```yaml
structure_prompt:
  en_tête:
    - Version et date
    - Améliorations/changements
    
  contenu:
    - Objectif principal
    - Capacités fondamentales
    - Approche interactive
    - Directives communication
    
  exemples:
    - Cas d'utilisation
    - Scénarios pratiques
```

### 2. Règles de Style
```yaml
style:
  langue: "français"
  ton: "professionnel mais accessible"
  format: "markdown"
  structure: "claire et hiérarchique"
```

### 3. Validation Finale
```yaml
validation_finale:
  critères:
    - Respect du workflow
    - Qualité du contenu
    - Conformité format
    - Documentation complète
    
  livrables:
    - Prompt généré
    - Logs de processus
    - Rapport validation
```

## MAINTENANCE ET AMÉLIORATION

### 1. Gestion des Erreurs
```yaml
gestion_erreurs:
  détection:
    - Utiliser process_validator.md
    - Vérifier chaque étape
    - Noter les anomalies
    
  correction:
    - Arrêter le processus
    - Corriger l'erreur
    - Reprendre le workflow
```

### 2. Amélioration Continue
```yaml
amélioration:
  sources:
    - Retours d'utilisation
    - Analyses métriques
    - Suggestions système
    
  processus:
    - Évaluation impact
    - Test modifications
    - Documentation changements
```

## NOTES IMPORTANTES

1. **Aucune Étape ne Peut Être Sautée**
   - Le workflow est séquentiel
   - Chaque étape est obligatoire
   - La validation est requise

2. **Documentation Obligatoire**
   - Tracer chaque action
   - Logger les décisions
   - Documenter les problèmes

3. **Qualité Prioritaire**
   - Suivre toutes les étapes
   - Valider chaque output
   - Maintenir la cohérence
