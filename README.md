# University Student Clubs Portal

A small informational website introducing university student clubs, built collaboratively as part of the DevOps Assignment 01 (Summer 2026).

## Project Structure

```
student-portfolio/
├── .gitignore
├── README.md
├── src/
│   ├── index.html
│   ├── clubs.html
│   ├── events.html
│   ├── join.html
│   └── highlights.html
└── styles/
    └── style.css
```

## Pages

| Page | Description | Owner |
|------|-------------|-------|
| index.html | Home / landing page | Team Lead |
| clubs.html | Club categories | Member 1 |
| events.html | Upcoming events | Member 2 |
| join.html | How to join | Member 3 |
| highlights.html | Club achievements | Member 4 |

## Branching Strategy

- `production` — production-ready code
- `develop` — active development, all feature branches merge here first
- `feature/<page-name>` — one per member, branched from `develop`
- `release/v1.0` — cut from `develop` for QA before merging to `production`

## Workflow

1. Branch from `develop`: `feature/<page-name>`
2. Commit + push your work
3. Open a PR into `develop`, assign the Team Lead, request 2 reviewers
4. Rebase onto latest `develop` before merge
5. After QA on `release/v1.0`, PR into `production` (3 approvals required)

## Team

See submission document for full team roster and roles.
