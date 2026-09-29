# Module 4: JavaScript Essentials

Metadata

- Module: 04 • Last updated: 2026-09-29 • Audience: Lower/upper secondary

## Module Overview

Students first learn JavaScript fundamentals, then use events and DOM updates to build a small stateful interface. The sequence moves from values, operators, functions, and conditions to a calculator interaction, then to list state and rendering.

## Student Route

Use the [Module 4 student route](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/README.md) to guide students from the calculator interaction to the dynamic UI project. Arrays and loops are marked as optional for Unit 4.1.

## Learning Outcomes (DigComp 2.2)

- Uses variables, simple values, operators, functions, and conditions to solve a small problem.
- Connects a form event to a calculation function and reports the result accessibly.
- Manages small UI state and renders from state via a simple render function.
- Ensures keyboard operability and perceivable updates for dynamic content.
- Applies progressive enhancement principles.

### Alignment (DigComp areas)

- Digital content creation (3.1, 3.2)
- Problem solving (5.3)
- Problem solving (identifying needs and technological responses, 5.2; accessible interaction)

## Sequence & Timing (60–120 min)

1. JavaScript basics (20–30): values, variables, arithmetic, functions, and simple conditions.
2. First interaction (15–20): connect a calculator form to a function with `addEventListener`.
3. DOM state (20–30): render a small list from an array, then add items from a form.
4. Independent task (10–25): build the core add-and-render list; completion, deletion, filters, and persistence are optional extensions.
5. Share & reflect (5–10): explain event flow and render triggers.

## Materials & Setup

**Required:** Modern browser and a text editor or approved browser-based editor; starter HTML for enhancement.

**Optional:** Browser DevTools console for inspecting errors and values.

**Before class:** Open the calculator example and starter files; prepare a visible-output walkthrough. DevTools may support teacher debugging but are not required for students.

**If restricted:** Students can follow the calculator’s visible output and trace values on paper while the teacher demonstrates the console. If they cannot install an editor, use an approved browser-based editor; if file editing is unavailable, pair on a teacher-prepared device and complete the coding task later.

## Accessibility & Inclusion

- Use semantic buttons/controls; ensure Enter/Space activation.
- Manage focus when adding/removing elements; visible feedback for changes.

## Differentiation

- Scaffold: Provide starter HTML and a basic render function stub.
- Extension: Add simple persistence (localStorage) or filtering.

## Assessment & Evidence

- Evidence: HTML/JS files + short video/notes demonstrating interaction.
- Use rubric: See [assessment-rubric-04.md](./assessment-rubric-04.md).

## Resources (DPK)

- Unit 4.1: [JavaScript Basics and a First Interaction](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.1-js-basics-dom.md)
- Unit 4.2: [DOM Events & Dynamic UI](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.2-dom-events.md)
- Examples: [JavaScript Basics Calculator](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/javascript-basics.html) • [Todo List](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/todo-list.html)
- Tasks: [First JavaScript Calculator](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-1-interactive-elements.md) • [DOM Events](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-2-dom-events.md)

## Teacher Notes

- Separate state from view; avoid inline event attributes.
- Use aria-live or visible text updates where appropriate; maintain focus order.
