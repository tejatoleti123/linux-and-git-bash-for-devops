# GitHub Workflow & Best Practices

## Typical GitHub Workflow

1. Clone the repository
2. Create a feature branch
3. Make changes and commit
4. Push branch to GitHub
5. Create a Pull Request
6. Review and merge

---

## Branching Strategy

- `main` / `master`: production-ready code
- `feature/*`: new features
- `hotfix/*`: urgent fixes

Avoid committing directly to `main`.

---

## Pull Requests (PR)

A Pull Request:
- Proposes changes
- Enables code review
- Prevents direct production changes

Benefits:
- Better code quality
- Team collaboration
- Audit trail

---

## Fork vs Clone

| Fork | Clone |
|----|------|
| GitHub-level copy | Local copy |
| Used for open-source | Used for development |
| Separate repo | Same repo |

---

## Common Mistakes

- Large commits
- Vague commit messages
- Skipping `git pull`
- No `.gitignore`

---

## Best Practices

- One logical change per commit
- Write meaningful commit messages
- Pull before pushing
- Keep branches short-lived
- Use `.gitignore`
