# Teacher Toolkit for the Digital Proficiency Kit

This repository hosts teacher-facing materials aligned with the Digital Proficiency Kit (DPK). It includes module overviews, unit lesson plans, and assessment rubrics that map to DigComp 2.2.

- Audience: Teachers and facilitators
- Format: Markdown (printable, easy to adapt)
- Tech: No build – open and read in any Markdown viewer

## Structure

```
teacher-toolkit/
├── modules/
│   ├── 01-introduction-to-the-web/
│   ├── 02-html-foundations/
│   ├── 03-css-styling-layout/
│   ├── 04-javascript-essentials/
│   ├── 05-data-visualization/
│   ├── 06-creative-web-projects/
│   └── 07-green-steam-challenge/
├── assessment/
└── docs/
```

Each module folder contains:
- module-overview.md – outcomes, flow, resources
- unit-X.Y-lesson-plan.md – lesson plan with differentiation, accessibility, assessment
- assessment-rubric-0X.md – criteria mapped to DigComp 2.2

## Cross‑links to DPK

Lesson plans link to matching code/examples in the DPK repository. If both repos are cloned side‑by‑side, links like:

```
../../digital-proficiency-kit/modules/02-html-foundations/examples/student-survey.html
```

will work in VS Code. On GitHub, browse to the DPK repository and follow the same path.

## Contributing

- Keep filenames lowercase hyphen‑separated
- Include metadata (module, unit, author, date)
- Use inclusive language and provide accessibility notes
- Update CHANGELOG in this repo when adding modules/units
