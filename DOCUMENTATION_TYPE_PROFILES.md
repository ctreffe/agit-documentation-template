# Documentation Type Profiles

Documentation type profiles define how a documentation project adapts its structure, depth, tone, examples, screenshots, and QA criteria to a specific kind of technical documentation.

A profile is not a rigid form. It is a maintainer-controlled orientation layer. The assistant may propose profile-specific structure, checks, and examples, but the maintainer decides which profile applies and how it should be adapted.

## Profile selection

During initialization, the assistant must ask which documentation type or combination of types the project uses.

Common documentation types include:

- Tutorial.
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

If multiple profiles apply, define the dominant profile and any secondary profiles in `PROJECT_CONTEXT.md`.

## Bilingual documentation

Documentation projects may be maintained bilingually. For AGIT documentation projects, German and English should be treated as first-class documentation languages when the maintainer requires bilingual output.

A bilingual project should define:

- Primary working language.
- Publication languages.
- Whether German and English files are maintained in parallel.
- Whether one language is authoritative and the other is a translation.
- How terminology consistency is checked across languages.
- How screenshots are handled when UI language differs from documentation language.

Bilingual documentation should not become two diverging documentation systems. Equivalent documents should have explicit relationships, for example `README.md` and `README.de.md`.

## Profile: Tutorial

A tutorial teaches a reader how to complete a concrete task or workflow. It is especially important when the target audience includes less experienced users.

### Purpose

A tutorial should help readers reach a meaningful result with enough guidance that they can follow the path without already understanding the whole system.

A tutorial should not merely describe features. It should guide a reader through a sequence of actions and explain the necessary context at the point where it becomes relevant.

### Audience focus

Tutorials require explicit audience decisions. Before drafting a tutorial, define:

- What readers already know.
- What readers should not be expected to know.
- Which terms need explanation.
- Which actions are obvious to expert users but not to this audience.
- Which mistakes or misunderstandings are likely.
- What successful completion looks like for the reader.

For less experienced users, the documentation should reduce hidden assumptions. It should name prerequisites, navigation paths, visible UI labels, expected screen states, and verification steps.

### Recommended structure

A tutorial usually benefits from this structure:

1. Goal.
2. Audience and prerequisites.
3. Starting state.
4. Required materials, permissions, or setup.
5. Step-by-step procedure.
6. Expected result.
7. Verification.
8. Common problems or next steps.

The structure may be adapted when the topic requires a different flow.

### Writing guidance

Tutorials should use direct, task-oriented language. Prefer active voice and concrete UI labels. Avoid unexplained jargon.

Each step should state one meaningful action where possible. If a step has a risk, dependency, or important consequence, explain it near the step rather than in a distant background section.

Conceptual explanations should be short and placed where they support the action. Longer background material should be linked separately.

### Screenshots and visuals

Tutorial screenshots should show critical screen states, transitions, and expected results. They are most valuable when readers need to recognize where they are or confirm that their screen matches the documentation.

Avoid screenshots that are visually impressive but do not help the reader act.

### QA checklist

Before a tutorial milestone, check:

- The target audience is explicit.
- Prerequisites are complete.
- Steps can be followed in order.
- UI labels and navigation paths match the actual interface.
- Screenshots show relevant states and contain no sensitive information.
- Expected results and verification points are clear.
- The tutorial avoids hidden expert assumptions.
- German and English versions are aligned when bilingual output is required.
