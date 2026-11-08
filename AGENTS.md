# ASTRAVA Portfolio — Agent Instructions

These instructions apply to all work in this repository.

## Before making changes

1. Read this file and relevant project documentation.
2. Inspect the existing codebase, scripts, and conventions before editing.
3. Summarize the task, affected areas, assumptions, and verification plan.
4. Ask before changing the agreed architecture, adding major dependencies, or removing existing functionality.

## Engineering principles

- Use TypeScript for application code.
- Prefer focused, reusable components and clear module boundaries.
- Keep content and project showcase data separate from presentation components.
- Use descriptive names and avoid unnecessary abstractions.
- Build responsive behavior and accessibility in from the beginning.
- Respect reduced-motion preferences.
- Avoid dependencies that duplicate simple existing functionality.

## Design principles

- Follow the approved ASTRAVA direction: premium, minimal, modern creative-tech.
- Palette direction: charcoal, warm white, electric blue accent.
- Maintain consistent spacing, typography, contrast, and interaction states.
- Avoid generic template layouts and excessive decorative effects.
- Ensure the experience works on mobile as well as desktop.

## Content integrity

- Never invent clients, logos, testimonials, awards, years of experience, or performance metrics.
- Clearly distinguish concepts, demos, work in progress, and completed work.
- Only link to live projects when the destination has been deployed and verified.
- Do not claim a service is available until the team can deliver and support it.
- Use approved contact details only.

## Security and privacy

- Never commit API keys, passwords, tokens, private customer data, or production secrets.
- Keep secrets in environment variables and provide an accurate `.env.example` when needed.
- Do not expose private admin routes or configuration interfaces on the public website.
- Validate and sanitize untrusted input where applicable.

## Verification

Before declaring work complete:

1. Run relevant lint and type-check commands if configured.
2. Run the production build.
3. Test changed behavior at mobile and desktop widths.
4. Check navigation, links, forms, and interactive controls.
5. Report commands run, results, and checks that could not be performed.

Never claim a test passed if it was not run.

## Git workflow

- Use a descriptive feature branch; do not work directly on `main`.
- Make focused commits with clear messages.
- Open a pull request with a summary, screenshots for visual changes, and verification notes.
- Request review before merging.
- Do not force-push or rewrite shared history without explicit approval.
