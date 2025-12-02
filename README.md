# BMAD Client Template

Template pour les sessions client du Remote Coding Agent. Ce repo est clone automatiquement quand un nouveau client est cree via `/new-client`.

## Structure

```
.agents/commands/
├── discovery.md    # Premier contact - collecte les besoins
├── brief.md        # Creation du Project Brief
└── prd.md          # Creation du PRD detaille

docs/
├── brief.md        # Project Brief (genere)
└── prd.md          # PRD (genere)
```

## Workflow client

1. **Discovery** - Sophie accueille le client et collecte les informations de base
2. **Brief** - Marie structure les informations en Project Brief
3. **PRD** - Jean transforme le brief en specifications detaillees

## Personnalisation

Les prompts dans `.agents/commands/` peuvent etre modifies pour:
- Changer le ton (plus formel, plus decontracte)
- Ajouter des questions specifiques a ton domaine
- Modifier les templates de documents

## Utilisation

Ce template est utilise par le Remote Coding Agent. Ne pas modifier directement - les changements seront ecrases lors du prochain clone.
