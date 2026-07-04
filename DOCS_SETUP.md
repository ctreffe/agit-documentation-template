# Documentation Setup

Use this checklist to define the documentation project before substantive drafting begins.

## Documentation identity

- Documentation title: TBD
- Documentation type: TBD
- Product, system, process, or topic covered: TBD
- Intended publication context: TBD
- Maintainer-approved status model: draft, review, stable, archived, or other.

## Documentation type

Select one or more and record the selected profile in `PROJECT_CONTEXT.md`. Use `DOCUMENTATION_TYPE_PROFILES.md` for profile-specific structure and QA guidance. If the project is a tutorial, define the reader task, starting state, expected result, and verification standard before drafting.

Select one or more:

- User guide.
- Admin guide.
- Developer documentation.
- API reference.
- Technical concept.
- Architecture documentation.
- Migration guide.
- Troubleshooting guide.
- Operating procedure.
- Release documentation.
- Training or onboarding material.
- Mixed documentation set.

## Audience

Audience definition is a first-order documentation decision, especially for tutorials and guides for less experienced users. Define the audience before deciding detail level, screenshots, terminology, or procedure depth.

Define:

- Primary audience.
- Secondary audience.
- Required prior knowledge.
- Tasks the documentation must support.
- Decisions the documentation must enable.
- Misunderstandings the documentation must prevent.

## Source material

Identify:

- Existing documentation.
- Source repositories.
- Tickets or issue threads.
- Screenshots or recordings.
- Logs, exports, or configuration examples.
- External references.

Before the assistant reads raw material, check whether it may contain sensitive information.

## Visual material

Decide:

- When screenshots are necessary.
- Which screen states must be captured.
- Whether screenshots need redaction.
- Whether diagrams are needed.
- Where visual assets should live.
- How visual QA will be performed.

## Link model

Decide:

- Internal navigation conventions.
- External reference conventions.
- Link text standards.
- Link check cadence.
- Handling of private or unstable URLs.

## Language model

Define:

- Primary working language.
- Publication languages.
- Whether German and English are maintained in parallel.
- Whether one language is authoritative.
- How terminology and screenshots are checked across languages.

## Initial output

Before the first substantive documentation milestone, the repository should contain:

- Completed `PROJECT_CONTEXT.md`.
- Selected documentation type profile and language model.
- Adapted audience, style, screenshot, link, and visual QA rules.
- Initial documentation structure.
- Any required DDRs.
- Updated changelog and version information if a milestone is reached.
