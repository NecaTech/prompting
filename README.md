# Prompting Framework

Un framework sophistiqué pour la génération de prompts optimisés pour n'importe quel LLM (Language Learning Model).

## ⚠️ Important

Avant toute utilisation, il est **IMPÉRATIF** de lire le fichier `instruction.md`. Ce fichier contient les instructions précises que l'IA doit suivre pour générer des prompts optimaux. Le respect scrupuleux de ces instructions est la clé du bon fonctionnement du framework.

```markdown
1. Lire instruction.md
2. Suivre TOUTES les étapes indiquées
3. Ne pas sauter d'étapes
4. Respecter l'ordre du processus
```

## Structure du Framework

```
prompting/
├── core/                   # Mécanismes fondamentaux
│   ├── analyzer.md        # Analyse du flux de données
│   ├── router.md          # Gestion du routage
│   ├── parser.md          # Analyse des entrées
│   ├── validator.md       # Validation des processus
│   ├── linker.md          # Gestion des dépendances
│   ├── xml_processor.md   # Traitement des balises XML
│   └── 4c_processor.md    # Application des règles 4C
│
├── 01_analysis/           # Analyse de la demande
│   ├── context/          # Analyse du contexte
│   ├── requirements/     # Identification des besoins
│   └── constraints/      # Contraintes à respecter
│
├── 02_structure/          # Structure du prompt
│   ├── templates/        # Modèles de base
│   ├── components/       # Composants réutilisables
│   └── format/          # Règles de formatage
│
├── 03_enhancement/        # Amélioration du prompt
│   ├── rules/           # Règles universelles
│   ├── clarity/         # Amélioration de la clarté
│   ├── optimization/    # Optimisations
│   └── validation/      # Validation finale
│
├── input.md              # Fichier d'entrée utilisateur
├── instruction.md        # ⚠️ Instructions ESSENTIELLES pour l'IA
└── output/              # Prompts générés
```

## Fonctionnement

1. **CRUCIAL** : L'IA lit et assimile `instruction.md`
2. L'utilisateur écrit sa demande dans `input.md`
3. Le système traite la demande via le circuit core :
   - Analyse XML et structurelle
   - Application des règles 4C
   - Routage et validation
4. Le prompt optimisé est généré dans le dossier `output/`

## Les 4C du Framework

- **Clarté** : Instructions précises et compréhensibles
- **Cohérence** : Continuité logique entre les sections
- **Contexte** : Informations pertinentes intégrées
- **Complétude** : Couverture exhaustive des besoins

## Utilisation

1. Clonez le repository :
```bash
git clone https://github.com/NecaTech/prompting.git
```

2. **IMPORTANT** : Assurez-vous que l'IA lit `instruction.md`

3. Écrivez votre demande dans `input.md`

4. Le système générera automatiquement un prompt optimisé dans le dossier `output/`

## Caractéristiques

- Architecture en circuit pour un traitement systématique
- Validation à chaque étape du processus
- Génération de prompts universels (compatibles avec tous les LLMs)
- Structure modulaire et extensible
- Système de feedback intégré

## Contribution

Les contributions sont les bienvenues ! Voici comment contribuer :

1. Fork le projet
2. Créez une branche pour votre fonctionnalité
3. Committez vos changements
4. Push vers la branche
5. Ouvrez une Pull Request

**Note** : Tout contributeur doit impérativement comprendre et respecter le processus décrit dans `instruction.md`

## Licence

MIT License

## Auteurs

- NecaTech
