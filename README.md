# Teacher Toolkit for the Digital Proficiency Kit

### _STEAM: From Campus to Classroom, Crafting Tomorrow (STEAM-C3T)_

**Erasmus+ Cooperation Partnerships in School Education (KA220-SCH)**

Developed by **Tallinn University, Haapsalu College**

## Overview

The Teacher Toolkit complements the Digital Proficiency Kit with ready-to-use teaching materials. Each module provides lesson flow, differentiation, accessibility notes, and assessment rubrics to support effective delivery in STEAM contexts.

---

## Objectives

- Provide lesson-ready plans aligned to DPK modules and DigComp 2.2.
- Support inclusive, accessible teaching strategies for web-based STEAM learning.
- Offer assessment rubrics and reflection prompts for authentic evaluation.

---

## Toolkit Structure

| Module                                                                       | Focus                                 | Materials                      |
| ---------------------------------------------------------------------------- | ------------------------------------- | ------------------------------ |
| [1. Introduction to the Web](./modules/01-introduction-to-the-web/README.md) | How the web works, semantic HTML      | Overview, lesson plans, rubric |
| [2. HTML Foundations](./modules/02-html-foundations/README.md)               | Content hierarchy, accessibility      | Overview, lesson plans, rubric |
| [3. CSS Styling & Layout](./modules/03-css-styling-layout/README.md)         | Typography, colour, responsive design | Overview, lesson plans, rubric |
| [4. JavaScript Essentials](./modules/04-javascript-essentials/README.md)     | Variables, events, DOM manipulation   | Overview, lesson plans, rubric |
| [5. Data & Visualization](./modules/05-data-visualization/README.md)         | Visualising data (Canvas/SVG)         | Overview, lesson plan, rubric  |
| [6. Creative Web Projects](./modules/06-creative-web-projects/README.md)     | Art and computation                   | Overview, lesson plan, rubric  |
| [7. Green STEAM Challenge](./modules/07-green-steAM-challenge/README.md)     | Sustainable innovation with code      | Overview, lesson plan, rubric  |

Each module includes:

- Module overview (outcomes, sequence, resources)
- Unit lesson plan(s) (differentiation, accessibility, assessment)
- Assessment rubric mapped to DigComp 2.2

---

## Folder Structure

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
├── CHANGELOG.md
└── README.md
```

Example module folder layout:

```
modules/04-javascript-essentials/
├── module-overview.md      # Outcomes, sequence, resources (links to DPK)
├── unit-4.1-lesson-plan.md # Lesson flow, differentiation, accessibility, assessment
├── unit-4.2-lesson-plan.md # (If applicable) additional unit plan
└── assessment-rubric-04.md # Criteria mapped to DigComp 2.2
```

---

## Get Started

- Browse module overviews via the table above, then open the module’s README for links to unit plans and rubrics.
- Materials are plain Markdown – print or adapt as needed.
- Cross-links point to DPK units/examples/tasks for classroom handouts and code.

---

## Pedagogical Approach

The toolkit emphasizes inclusive, authentic learning:

1. Active making with purposeful artefacts and reflection.
2. Integration of code with content knowledge (STEAM).
3. Accessibility at design time (alt text, semantics, focus, contrast).

---

## Technical Requirements

- Any Markdown viewer (VS Code, GitHub, etc.).
- No build or external dependencies.

---

## Related Repositories

The Teacher Toolkit is part of a three-repository ecosystem:

### **1. [Digital Proficiency Kit](https://github.com/STEAM-C3T/digital-proficiency-kit)**

Runnable code examples, tasks, and student-facing module guides.

### **2. Teacher Toolkit** (this repository)

Lesson plans, assessment rubrics, module overviews, and professional development resources.

### **3. [Learning Materials](https://github.com/STEAM-C3T/dpk-learning-materials)**

Comprehensive instructional materials specifically designed for **novice teachers with little or no programming experience**, including:

- **Marp slide decks** for module overviews and unit lessons (ready to present in class)
- **Step-by-step tutorials** with code-along examples, common pitfalls, and debugging guidance
- **Student workbooks** with scaffolded practice, note-taking areas, and self-assessment
- **Teacher-annotated workbooks** with timing estimates, differentiation strategies, misconception alerts, and answer keys

**Why Learning Materials?**
While the Teacher Toolkit provides lesson plans and rubrics, the Learning Materials repository offers classroom-ready presentations, detailed tutorials, and workbooks that reduce preparation time for teachers new to web development. These materials complement the lesson plans by providing ready-to-use slides and scaffolded student handouts.

**Navigation:**

- From Teacher Toolkit lesson plans → links to Learning Materials decks and workbooks for immediate classroom use
- From Learning Materials → links back to Teacher Toolkit for assessment rubrics and module overviews

---

## Contribution and Collaboration

- Keep filenames lowercase and hyphen‑separated.
- Use inclusive language and provide accessibility notes.
- Update `CHANGELOG.md` when adding or updating modules/units.
