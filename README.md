# 🧭 Exploration de carrière — App interactive

Application web **mono-fichier** qui guide le processus complet d'exploration de carrière en 4 étapes, basé sur un pack de ressources pédagogiques en 4 devoirs (Self-Assessments, Evaluating Career Options, Career Plan, Job Seeker Checklist).

## Lien direct

L'application est accessible en ligne (GitHub Pages) :

**`https://<votre-utilisateur>.github.io/career-explorer/`**

## Le parcours en 4 étapes

| Étape | Module | Contenu |
| --- | --- | --- |
| 1 | Auto-évaluations | Valeurs (max 10), compétences (5-10, appréciation 1-10), intérêts |
| 2 | Évaluation des options | Fiche par option de carrière : rôle, lieu, disponibilité, adéquation, forces, plan de développement |
| 3 | Plan de carrière | Vision (court/moyen/long terme), valeurs, 5-8 objectifs SMART avec mesure + échéance, obstacles et mitigations |
| 4 | Checklist emploi | 7 actions de préparation à la recherche d'emploi |

## Fonctionnalités

- **Sauvegarde automatique** — les réponses sont conservées dans le navigateur (localStorage) à chaque saisie.
- **Progression visuelle** — barre globale + pourcentage par étape.
- **Navigation** — clic, boutons Précédent/Suivant ou flèches ←/→ du clavier.
- **Export Markdown** — copie ou téléchargement d'une note structurée (frontmatter, tableaux, checklists), prête pour Obsidian.
- **Réinitialisation** — avec confirmation.
- **100 % hors-ligne** — zéro dépendance, zéro build, un seul fichier `index.html`.

## Utilisation locale

Ouvrez simplement `index.html` dans n'importe quel navigateur. Aucune installation requise.

## Technologies

HTML + CSS + JavaScript vanilla, aucun framework, aucune dépendance externe.

## Structure

```text
career-explorer/
├── index.html   # l'application complète (un seul fichier)
└── README.md
```