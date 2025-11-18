# Module 4: JavaScript Essentials

Metadata

- Module: 04 • Version: 2025-11-18 • Audience: Lower/upper secondary

## Module Overview

Students add interactivity by listening to events and updating the DOM. They manage simple UI state and render deterministically from that state, with progressive enhancement so content remains usable without JS.

## Learning Outcomes (DigComp 2.2)

- Registers event listeners and updates the DOM based on user actions.
- Manages small UI state and renders from state via a simple render function.
- Ensures keyboard operability and perceivable updates for dynamic content.
- Applies progressive enhancement principles.

### Alignment (DigComp areas)

- Digital content creation (3.1, 3.2)
- Problem solving (5.3)
- Safety & inclusion (4.1 accessible interaction)

## Sequence & Timing (60–120 min)

1. JS basics (15–25): variables, `querySelector`, `addEventListener`.
2. DOM + state (20–30): render from state; add/remove elements; focus.
3. Guided practice (15–25): counter + accessibility (visible updates).
4. Independent task (10–25): small list-based UI (e.g., todo) with filter.
5. Share & reflect (5–10): explain event flow and render triggers.

## Materials & Setup

- Browser DevTools console; editor; starter HTML for enhancement.

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

- Unit 4.1: [JS Basics + DOM](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.1-js-basics-dom.md)
- Unit 4.2: [DOM Events & Dynamic UI](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.2-dom-events.md)
- Examples: [DOM Interactions](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/dom-interactions.html) • [Todo List](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/todo-list.html)
- Tasks: [Interactive Elements](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-1-interactive-elements.md) • [DOM Events](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-2-dom-events.md)

## Teacher Notes

- Separate state from view; avoid inline event attributes.
- Use aria-live or visible text updates where appropriate; maintain focus order.
