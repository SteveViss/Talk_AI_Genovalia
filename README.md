# Introduction à l'IA générative — présentation

Diapositives Quarto/revealjs (thème Genovalia) présentant les notions clés de l'IA générative
moderne à des collègues : tokens (taille de contexte, coût), skills, artifacts et programmation
en mode agentic.

Auteur : Steve Vissault.

## Modifier la présentation

1. Éditer [index.qmd](index.qmd)
2. Prévisualiser localement :

```bash
quarto preview index.qmd
```

## Publier sur GitHub Pages

```bash
quarto publish gh-pages
```

Génère la présentation, crée/met à jour la branche `gh-pages` et la pousse vers GitHub.

## Plan de la présentation

- Tokens & contexte : c'est quoi un token, la fenêtre de contexte, taille par modèle, coût
- Skills : partager des prompts/procédures réutilisables en équipe
- Artifacts : contenu généré persistant et partageable
- Programmation agentic : LLM augmenté, boucle agent, exemple d'agent de code, workflows vs agents

Les schémas proviennent de la documentation officielle Anthropic (liens directs, non copiés) :
platform.claude.com/docs et anthropic.com/engineering/building-effective-agents.
