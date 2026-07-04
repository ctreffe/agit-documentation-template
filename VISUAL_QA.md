# Visual QA

Use this checklist before publishing or closing a documentation milestone that includes screenshots, diagrams, rendered pages, PDFs, or other visual artifacts.

## Screenshots

- Screenshot is current.
- Screenshot shows the intended state.
- Important text is readable.
- Cropping does not remove necessary context.
- Sensitive information has been removed or approved.
- Filename is stable and descriptive.
- Screenshot is referenced from the relevant text.

## Diagrams

- Diagram reflects the current technical model.
- Labels are readable.
- Terminology matches the documentation.
- Diagram is not more detailed than the reader needs.
- Source or generation method is documented when relevant.

## Quarto rendered outputs

When Quarto is used, run `quarto render` before milestone closure if the local toolchain is available. HTML is the default baseline render. PDF render checks require a TeX toolchain such as TinyTeX. Check the generated outputs required by the project.

## Rendered outputs

- Headings, lists, tables, code blocks, and images render correctly.
- Navigation works.
- Internal links resolve.
- External links are checked.
- Images have appropriate alt text or surrounding explanation.
- Layout works in the expected output format.

## Publication readiness

- No unintended draft notes remain.
- No sensitive visual information remains.
- Visuals support real reader tasks.
- Open visual issues are documented if they cannot be resolved before the milestone.
