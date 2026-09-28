# Teacher Feedback on the Digital Proficiency Kit Materials

## A classroom-focused review of the student and teacher resources

**Prepared:** 28 September 2026  
**Materials reviewed:** Digital Proficiency Kit, Teacher Toolkit, and DPK Learning Materials  
**Audience:** Teachers and curriculum partners

The seven-module sequence gives students a useful route from web foundations to independent STEAM projects. The resources already include lesson plans, examples, presentations, tutorials, and workbooks. From a teacher’s perspective, the next improvement should be a consistency and classroom-readiness pass: each unit should teach the same outcomes across repositories, fit a realistic lesson schedule, and demonstrate the accessibility and privacy practices it asks students to use.

> **Overall recommendation:** Keep the project-based structure. Before wider classroom use, align the cross-repository materials, correct a small number of technical and framework inaccuracies, and provide teachers with a concise, reliable lesson route for each unit.

## Priority feedback

### 1. Align the learning sequence across repositories

Module 4 currently describes different Unit 4.1 lessons in different places. The Digital Proficiency Kit teaches DOM events with an interactive profile card; the Teacher Toolkit follows that activity; the Learning Materials tutorial instead covers a much wider JavaScript fundamentals sequence, including variables, data types, functions, conditionals, loops, a calculator, and a quiz. Teachers need one agreed sequence so that the lesson plan, deck, tutorial, workbook, task, and runnable example all support the same learning outcomes.

**Suggested change:** Agree on the scope and order of Units 4.1 and 4.2, then align the objectives, examples, and assessment evidence in all three repositories. Consider moving any additional topics into clearly marked extension material.

**Evidence:** [Kit Unit 4.1](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.1-js-basics-dom.md) (`digital-proficiency-kit/modules/04-javascript-essentials/units/unit-4.1-js-basics-dom.md`), [Teacher Toolkit Unit 4.1 plan](https://github.com/STEAM-C3T/teacher-toolkit/blob/main/modules/04-javascript-essentials/unit-4.1-lesson-plan.md) (`teacher-toolkit/modules/04-javascript-essentials/unit-4.1-lesson-plan.md`), and [Learning Materials Unit 4.1 tutorial](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/04-javascript-essentials/units/4.1-javascript-basics/tutorial/unit-4.1-tutorial.md) (`dpk-learning-materials/modules/04-javascript-essentials/units/4.1-javascript-basics/tutorial/unit-4.1-tutorial.md`).

### 2. Make lesson duration and workload consistent

Some short lesson plans sit beside longer tutorials and workbooks. A teacher may reasonably plan for one class period and discover that the independent task requires another session. Unit 1.2, for example, estimates 90–120 minutes in its unit overview, while several Teacher Toolkit lesson plans are structured around roughly 50–55 minutes. The unit README also still says its materials are placeholders even though the deck, tutorial, and workbooks are present.

**Suggested change:** Give each unit a common timing model: a core lesson with named minute ranges, the expected stopping point, and optional follow-up or extension activities. Update stale completion notes and make the time estimates agree across the lesson plan, unit page, tutorial, and teacher workbook.

### 3. Correct the DigComp mapping in Module 7

The Module 7 assessment rubric labels competence 4.2 as “Engaging in citizenship through digital technologies.” In DigComp 2.2, competence 4.2 is “Protecting personal data and privacy”; engaging in citizenship is competence 2.3. Because privacy is also a real concern in the mini-app activity, this mapping should be corrected and the other rubric mappings checked for consistency.

**Suggested change:** Correct the rubric and review all DigComp labels against the cited edition of the framework. Keep the framework version visible in the teacher-facing materials.

**Evidence:** [Module 7 assessment rubric](https://github.com/STEAM-C3T/teacher-toolkit/blob/main/modules/07-green-steam-challenge/assessment-rubric-07.md) (`teacher-toolkit/modules/07-green-steam-challenge/assessment-rubric-07.md`). Reference: [European Commission DigComp framework](https://joint-research-centre.ec.europa.eu/oldpage-digcomp/digcomp-framework_en).

### 4. Teach heading hierarchy without turning a convention into a rule

Several HTML workbooks and tutorials tell students to use only one `<h1>` and describe that as necessary for screen-reader accessibility. A single main heading is often a helpful convention for a simple student page, but the materials should focus on meaningful, logically nested headings rather than present an “exactly one” rule as a technical requirement.

**Suggested change:** Teach students to choose headings for document structure and keep the hierarchy understandable. If one `<h1>` is used as a beginner-friendly pattern, label it as a practical convention for this task.

**Evidence:** [Unit 1.2 student workbook](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/01-introduction-to-the-web/units/1.2-basic-structure/workbook/unit-1.2-student-workbook.md) (`dpk-learning-materials/modules/01-introduction-to-the-web/units/1.2-basic-structure/workbook/unit-1.2-student-workbook.md`) and [teacher-annotated workbook](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/01-introduction-to-the-web/units/1.2-basic-structure/workbook/unit-1.2-teacher-annotated.md).

### 5. Make accessibility examples match the stated expectations

Some examples do not yet demonstrate the practices taught elsewhere. The Module 6 unit objectives require pause/play controls for animation accessibility, but the runnable example animates continuously with no pause control. The Module 3 responsive tutorial includes a contact form whose inputs rely on placeholder text without visible or programmatic labels.

**Suggested change:** Add pause/play and reduced-motion handling to the generative-art example. Add explicit labels to the contact form and ensure the tutorial explains why placeholders are supplementary guidance rather than labels. Use examples as the reference solution students will inspect.

**Evidence:** [Module 6 runnable example](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/06-creative-web-projects/examples/generative-art.html) (`digital-proficiency-kit/modules/06-creative-web-projects/examples/generative-art.html`), [Module 6 objectives](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/06-creative-web-projects/units/6.1-generative-art/README.md), and [Module 3 responsive tutorial](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/03-css-styling-layout/units/3.2-responsive-layouts/tutorial/unit-3.2-tutorial.md).

### 6. Clarify classroom tools and preparation

The kit is described as browser-only, while some learning activities assume students can edit files and use browser DevTools. This is a reasonable setup, but teachers need to know which activities only require a browser and which require an editor, DevTools access, downloaded files, or an internet connection. School-managed devices may restrict some of those tools.

**Suggested change:** Add a short pre-class checklist for each unit, including the required tools, file setup, browser features, and an alternative if a school device blocks DevTools or software installation. Separate “open and explore the example” from “create and edit a file.”

### 7. Reduce student-facing duplication and improve teacher scanning

The Unit 2.1 student workbook repeats its title, student details, and learning objectives at the beginning. Some teacher-annotated workbooks are detailed enough to function as references, but that detail can make it difficult to find the immediate teaching sequence during class.

**Suggested change:** Remove duplicated workbook sections. Put a one-page lesson guide near the beginning of each teacher resource with preparation, sequence, checks for understanding, likely sticking points, differentiation, and assessment evidence. Keep answer keys and longer background notes after it.

**Evidence:** [Unit 2.1 student workbook](https://github.com/STEAM-C3T/dpk-learning-materials/blob/main/modules/02-html-foundations/units/2.1-building-content/workbook/unit-2.1-student-workbook.md) (`dpk-learning-materials/modules/02-html-foundations/units/2.1-building-content/workbook/unit-2.1-student-workbook.md`).

### 8. Make the sustainability app’s data and impact claims safer

The Green Actions example stores choices in `localStorage`, but writing to browser storage can fail in restricted settings. Its score is simply a count of selected actions and should not be mistaken for a measured environmental benefit. The student materials already ask learners to discuss privacy and honest impact claims; the example should model those expectations.

**Suggested change:** Make persistence optional, handle storage failures gracefully, explain how to reset local data, and call the score an activity count rather than an environmental impact measurement. Avoid asking students to enter personal or sensitive information.

**Evidence:** [Green Actions Tracker example](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/07-green-steam-challenge/examples/green-mini-app.html) (`digital-proficiency-kit/modules/07-green-steam-challenge/examples/green-mini-app.html`).

## Assessment and teacher use

The rubrics would be easier to use consistently if they shared a common set of performance levels and clear evidence descriptions. At present, criteria and labels vary between modules, and some descriptors leave room for teachers to interpret “proficient” differently. I would also connect each rubric criterion to a specific artifact or observation: for example, the submitted page, a keyboard check, a peer test, or a short student explanation.

For classroom use, I would include a brief formative check and an exit prompt in every lesson plan. These let a teacher see whether students are ready to move on before assigning the next larger project. Extension work should be optional and should deepen the objective rather than introduce several new concepts at once.

## Access to teacher guidance

> **Publishing consideration:** Teacher-annotated workbooks and answer keys are available in public repositories and public Pages sites. “Instructor Use Only” is a label, not an access restriction. If the materials are intended to remain openly available, label and group them clearly in the teacher area. If answers must be restricted to teachers, store them in an access-controlled system rather than public Pages.

## Recommended revision order

1. Align Module 4 outcomes and sequence across all repositories.
2. Correct the Module 7 DigComp mapping and audit related labels.
3. Correct the heading guidance and align the accessibility examples with the learning objectives.
4. Reconcile lesson durations and remove stale or duplicate content.
5. Add practical setup notes and improve the sustainability example’s storage and impact messaging.
6. Standardize assessment evidence and teacher-facing lesson summaries.

This report is intended to guide the next improvement pass. It recommends changes to the existing materials; it does not replace the curriculum or prescribe a single teaching style.
