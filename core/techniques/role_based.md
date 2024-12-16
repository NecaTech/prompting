# Role-Based Prompting Processor

## Objectif
Intégrer des perspectives d'experts spécifiques dans la génération de prompts.

## Types de Rôles

### 1. Expertise Technique
```roles
- Architecte système
- Expert en optimisation
- Spécialiste qualité
- Analyste performance
```

### 2. Expertise Métier
```roles
- Expert domaine
- Consultant senior
- Analyste business
- Stratège
```

### 3. Expertise Pédagogique
```roles
- Mentor expérimenté
- Coach professionnel
- Formateur expert
- Guide méthodologique
```

## Matrice de Compétences
```competency-matrix
[Rôle] x [Compétences] x [Contexte] = Perspective Unique
```

## Pattern d'Implémentation
```template
En tant que [rôle], avec une expertise en [domaine],
analysons [problème] selon ces perspectives :

1. Analyse technique :
   {technical_analysis}

2. Considérations pratiques :
   {practical_considerations}

3. Recommandations expertes :
   {expert_recommendations}

4. Points d'attention :
   {attention_points}
```

## Connexions
- Entrée : Depuis analyzer.md
- Validation : Via validator.md
- Sortie : Vers le prochain processeur
