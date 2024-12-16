# Meta-Prompting Templates

## 1. Analyse de Prompt
```template
PROMPT À ANALYSER :
{prompt_original}

DÉCOMPOSITION STRUCTURELLE :

1. Éléments de Base :
   - Contexte : {analyse_contexte}
   - Objectif : {analyse_objectif}
   - Contraintes : {analyse_contraintes}

2. Structure :
   - Format : {analyse_format}
   - Organisation : {analyse_organisation}
   - Cohérence : {analyse_coherence}

3. Clarté :
   - Instructions : {analyse_instructions}
   - Spécifications : {analyse_specifications}
   - Ambiguïtés : {analyse_ambiguites}

ÉVALUATION QUALITATIVE :
Score global : {score_global}/10

Forces :
1. {force_1}
2. {force_2}
3. {force_3}

Faiblesses :
1. {faiblesse_1}
2. {faiblesse_2}
3. {faiblesse_3}

VERSION OPTIMISÉE :
{prompt_optimise}

JUSTIFICATION DES MODIFICATIONS :
{justification_changements}
```

## 2. Génération de Prompt
```template
SPÉCIFICATIONS :

1. Objectif :
   - Principal : {objectif_principal}
   - Secondaires : {objectifs_secondaires}

2. Contexte d'Utilisation :
   - Modèle cible : {modele_llm}
   - Cas d'usage : {cas_usage}
   - Contraintes : {contraintes}

3. Caractéristiques Requises :
   - Style : {style_requis}
   - Ton : {ton_requis}
   - Format : {format_requis}

STRUCTURE DU PROMPT :

1. Introduction :
   {structure_intro}

2. Corps :
   {structure_corps}

3. Conclusion :
   {structure_conclusion}

ÉLÉMENTS DE CONTRÔLE :
- Validations : {validations}
- Contraintes : {contraintes_specifiques}
- Formats de sortie : {formats_sortie}

PROMPT GÉNÉRÉ :
{prompt_final}

INSTRUCTIONS D'UTILISATION :
{guide_utilisation}
```

## 3. Optimisation de Prompt
```template
PROMPT INITIAL :
{prompt_initial}

OBJECTIFS D'OPTIMISATION :
1. {objectif_opt_1}
2. {objectif_opt_2}
3. {objectif_opt_3}

ANALYSE DE PERFORMANCE :

1. Efficacité :
   Score actuel : {score_efficacite}/10
   Améliorations :
   - {amelioration_eff_1}
   - {amelioration_eff_2}

2. Clarté :
   Score actuel : {score_clarte}/10
   Améliorations :
   - {amelioration_cla_1}
   - {amelioration_cla_2}

3. Précision :
   Score actuel : {score_precision}/10
   Améliorations :
   - {amelioration_pre_1}
   - {amelioration_pre_2}

VERSIONS OPTIMISÉES :

Version 1 (Accent sur la clarté) :
{version_1}

Version 2 (Accent sur la précision) :
{version_2}

Version 3 (Accent sur l'efficacité) :
{version_3}

RECOMMANDATION FINALE :
{version_recommandee}

JUSTIFICATION :
{justification_choix}
```
