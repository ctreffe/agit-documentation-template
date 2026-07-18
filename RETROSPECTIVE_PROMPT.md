# Retrospective Prompt

Use this prompt when the maintainer requests a review of documentation
collaboration over a selected milestone, project phase or other defined period.
It evaluates Maintainer-Agent collaboration rather than project content.

Invoke it with `Read and execute RETROSPECTIVE_PROMPT.md.`

## Prompt

```text
Perform a structured retrospective of Maintainer-Agent collaboration in this
documentation project.

Do not harmonize documentation content, coverage or roadmap here. Hand those
implications to a later harmonization.

1. Read CODEX.md, ChatGPT.md and PROJECT_CONTEXT.md.
2. Read the relevant milestone, current CHANGELOG.md sections and
   collaboration-related Decision Records.
3. Read CONTINUATION_PROMPT.md and HARMONIZATION_PROMPT.md.
4. Inspect relevant commit history, numbered handoffs, feedback artifacts and
   documented QA decisions with read-only commands and subject to documented
   access boundaries. Preserve uncommitted work.
5. Use current-session evidence and maintainer reports without claiming access
   to unavailable earlier chats.

Label material findings as repository evidence, current-session observation,
maintainer report or inference. Avoid conclusions from isolated events alone.
Do not open sensitive screenshots, source documents or feedback merely to
evaluate collaboration.

Evaluate:

- clarity of documentation purpose, audience and maintainer ownership
- usefulness of numbered questions, decisions and checkpoint handoffs
- structure, drafting, review and correction collaboration
- handling of maintainer and external feedback
- link, screenshot, visual QA and Quarto-render validation partnership
- source sensitivity, redaction and publication boundaries
- work-step and commit rhythm below documentation milestones
- accuracy of summaries, descriptions, limitations and completion claims
- prompt-based continuation across context windows
- practices to retain and recurring friction or rework

Classify outcomes as retain, adjust in project, hand to harmonization, template
candidate or no action. Documentation-content and roadmap implications go to
harmonization. Template candidates must be transferable, sanitized,
evidence-based and checked against overfitting.

Do not change the source-template repository unless I authorize the specific
template change with `explicit`, `explicitly` or the German word family
`explizit`. Retrospective invocation and concrete-project edit permission are
not template-change permission. If this repository is itself a template, apply
the same control-word rule to its reusable collaboration guidance.

Template-edit permission does not authorize Git history. Every stage, commit,
tag, push, pull, merge, rebase, reset or branch action requires its own specific
maintainer instruction containing a recognized control word.

Before edits, report:

1. scope and evidence
2. practices to retain
3. friction points, likely causes and confidence
4. proposed project collaboration changes
5. content or roadmap implications for harmonization
6. abstracted template candidates and overfitting risks
7. no-action observations
8. maintainer decisions

Apply only agreed project collaboration changes when clearly authorized. Do
not apply documentation-content changes or template candidates. After approved
edits, update affected collaboration documents consistently, validate links and
record durable decisions where useful. Update the last collaboration
retrospective in PROJECT_CONTEXT.md only when its scope and outcome are
accurately recorded.
```
