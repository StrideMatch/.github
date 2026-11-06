# StrideMatch — configuration GitHub de l'organisation

Ce repo spécial `.github` fournit des fichiers par défaut à **tous les repos de l'organisation**
qui n'ont pas les leurs.

## Templates d'issue (`.github/ISSUE_TEMPLATE/`)

| Template | Type | Label | Usage |
|---|---|---|---|
| 🐛 Bug | Bug | `bug` | Quelque chose ne marche pas |
| ✨ Feature | Feature | `enhancement` | Nouvelle fonctionnalité / amélioration produit |
| 🔧 Tâche technique | Task | — | Nettoyage, refacto, infra, dette technique |

Chaque issue créée avec un template est **ajoutée automatiquement au projet « Backlog »**
(`projects: ["StrideMatch/2"]`). Si le projet change de numéro, mettre à jour les 3 fichiers.

Les issues vierges sont désactivées (`config.yml`) pour que tout passe par un template.

⚠️ Ce repo est **public** (exigence GitHub pour les fichiers par défaut). N'y mettre que des
templates et de la config générique, jamais d'information interne.

Un repo qui a son propre dossier `.github/ISSUE_TEMPLATE/` n'utilise plus ces templates.
