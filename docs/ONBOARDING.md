# Onboarding — ASTRAVA Portfolio

Welcome. This repository contains the public-facing ASTRAVA studio website.

## 1. Before you start

1. Make sure you have access to the astrava-studio/astrava-portfolio repository.
2. Install Git and the editor/runtime required by the stack once it is selected.
3. Clone the repository and open the repository root in your editor.
4. Read these files in order:
   - README.md
   - docs/PROJECT_CONTEXT.md
   - docs/PROJECT_BRIEF.md
   - docs/DEVELOPMENT_WORKFLOW.md
   - docs/ASTRAVA_STUDIO_STANDARD.md
   - AGENTS.md

## 2. First AI-agent session

Use the coding agent and skills already installed on your machine. Do not install or copy another skill pack into this repository.

Paste this as the first task:

~~~text
You are joining the ASTRAVA studio portfolio project.

First inspect the entire repository. Read README.md, AGENTS.md, and the relevant files in docs/, especially PROJECT_CONTEXT.md, PROJECT_BRIEF.md, DEVELOPMENT_WORKFLOW.md, ASTRAVA_STUDIO_STANDARD.md, and ONBOARDING.md.

Do not modify files, scaffold an app, install dependencies, or choose a framework yet.

Report:
1. What exists in the repository and what is missing.
2. The product goal, audience, and required website sections.
3. Existing technical decisions and unresolved decisions.
4. A proposed implementation plan in small milestones.
5. Any questions that need the project owner's decision.

Follow the ASTRAVA Studio Working Standard. Use skills already installed in this environment; do not duplicate skills or agent configuration in the repository.
~~~

## 3. Agree the implementation before coding

The project owner and team should confirm:
- Framework, language, package manager, and supported runtime.
- Hosting/deployment target and domain approach.
- Page structure, content, responsive behavior, and visual direction.
- Which projects are ready to showcase and what screenshots/links are approved.
- Contact method and how enquiries will be handled.
- Which animations or interactions add value and which are unnecessary.

The intended visual direction is premium, minimal, and modern: charcoal, warm white, electric blue accent, strong typography, clear hierarchy, and restrained motion. Keep the website honest: no invented clients, testimonials, awards, years of experience, or performance metrics.

## 4. First implementation milestones

1. Confirm scope, stack, and architecture; record important decisions.
2. Create the application foundation and verify local development/build commands.
3. Implement responsive page structure and shared visual tokens.
4. Add studio introduction, services, working process, and about content.
5. Add the inventory and restaurant demos only when their status and public links are verified.
6. Implement and test the contact path; do not use fake success states.
7. Test responsive layouts, accessibility, performance, metadata, and production build.
8. Review with another founder before merging and deploying.

## 5. Before opening a pull request

Follow the shared definition of done in docs/ASTRAVA_STUDIO_STANDARD.md. Include screenshots for visual changes, checks actually run, and any remaining limitations.

**Current status:** repository setup and planning. Confirm the actual stack and scope before scaffolding.
