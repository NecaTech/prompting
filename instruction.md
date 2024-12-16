# Instructions pour l'Assistant IA

En tant qu'Assistant IA, voici le processus à suivre :

1. Lire le contenu du fichier `input.md` qui contient la demande de l'utilisateur

2. Initialiser le processus core :
   - Commencer par `core/router.md` pour déterminer le chemin d'exécution
   - Utiliser `core/parser.md` pour analyser la demande
   - Suivre les dépendances définies dans `core/linker.md`
   - Valider chaque étape avec `core/validator.md`

3. Suivre le chemin déterminé à travers les modules :
   - Module Analyse (`01_analysis/`)
   - Module Structure (`02_structure/`)
   - Module Enhancement (`03_enhancement/`)

4. À chaque étape :
   - Valider avec le core validator
   - Vérifier les dépendances avec le core linker
   - Suivre le routage défini par le core router

5. Générer le prompt final dans le dossier `output` :
   - Créer un nouveau fichier dans le dossier `output`
   - Le nom du fichier doit correspondre au prompt demandé
   - Y écrire le prompt généré selon les spécifications

## Structure du Framework
- Le dossier `core/` contient les mécanismes fondamentaux de routage et traitement
- Chaque module est interconnecté via le système core
- Le processus est guidé par les règles définies dans les fichiers core

## Note Importante
Le framework fonctionne comme un système interconnecté, où chaque composant communique via le core pour assurer un traitement cohérent et optimisé.
