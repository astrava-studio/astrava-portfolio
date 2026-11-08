# Development Workflow

## Branching

- Keep `main` as the stable branch.
- Create a focused branch for each task, for example:
  - `feat/hero-section`
  - `feat/project-showcase`
  - `fix/mobile-navigation`
  - `docs/deployment-guide`
- Do not commit unfinished work directly to `main`.

## Pull requests

Every pull request should include:

1. What changed and why
2. Screenshots or a short recording for UI changes
3. Tests and checks run, with their results
4. Known limitations or follow-up work

Request at least one founder review before merging. The repository owner remains responsible for coordinating changes and deployment.

## Commit messages

Prefer short, descriptive messages such as:

- `feat: add responsive hero section`
- `fix: correct mobile navigation behavior`
- `docs: add local setup instructions`
- `chore: configure linting`

## Definition of done

A task is complete only when:

- Implementation matches the agreed scope.
- No unrelated behavior is broken.
- Relevant lint, type-check, and build commands pass.
- Responsive behavior has been checked.
- Links and interactions have been tested.
- Documentation is updated where necessary.
- The pull request is reviewed and merged.

## Deployment

Choose the hosting provider after the application scaffold is established. Keep deployment settings and secrets out of source control. Document the production URL, environment variables, build command, and deployment procedure once confirmed.
