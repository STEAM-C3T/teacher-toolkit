# Module 4: JavaScript Essentials

## Unit 4.2 – DOM Events & Dynamic UI — Forms, Lists, State

## Outcomes

- Structure small UI logic into functions.
- Manage a small array of items and render the current list; filtering is optional.

## Lesson flow

- Recap (5’): state vs DOM, event flow.
- Demo (10’): submit one item; trace event → array update → rendered list.
- Guided (15’): select the form, input, and list; build the empty state and `renderItems()`, then render one hard-coded array item.
- Practice (20’): add non-empty items through a form and test blank input. Completion, deletion, and filters are optional extensions.
- Share (5’): discuss state shape and trade‑offs.

## Materials

- DPK Unit: [Unit 4.2 — DOM Events & Dynamic UI](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.2-dom-events.md)
- Example: [Todo List](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/todo-list.html)
- Task: [DOM Events](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-2-dom-events.md)

## Differentiation

- Provide starter functions; extension: persist to localStorage.

## Accessibility

- Maintain focus order; use labels and roles where appropriate.

Students do not need DevTools for the core task. Check success from the visible list, blank-input behavior, and a short trace of event → array → render.

## Assessment

- Rubric: event handling, state correctness, accessibility practices.

## Formative check and exit prompt

- **Formative check:** Have students submit one non-empty item, reject blank input, and trace the array change and rendered list.
  **Evidence:** State trace matched to the rendered list.
- **Exit prompt:** Describe one interaction as a sequence from user action to state change to updated display.
  **Evidence:** Three-step exit note.
