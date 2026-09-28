# Module 4: JavaScript Essentials

## Unit 4.1 — JavaScript Basics and a First Interaction

### Learning outcomes

Students will be able to:

- Declare and update simple values using `const` and `let`.
- Use arithmetic and basic comparisons.
- Write and call a function that returns a value.
- Use `if`/`else` to handle a missing value or invalid calculation.
- Connect form submission to a function with `addEventListener` and display feedback with `textContent`.

### Materials

- DPK unit: [JavaScript Basics and a First Interaction](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/units/unit-4.1-js-basics-dom.md)
- Example: [JavaScript Basics Calculator](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/examples/javascript-basics.html)
- Task: [First JavaScript Calculator](https://github.com/STEAM-C3T/digital-proficiency-kit/blob/main/modules/04-javascript-essentials/tasks/task-1-interactive-elements.md)
- Learning materials: [Unit 4.1 decks, tutorial, and workbooks](https://github.com/STEAM-C3T/dpk-learning-materials/tree/main/modules/04-javascript-essentials/units/4.1-javascript-basics)

### Lesson flow

1. **Warm-up:** Ask students to predict the result of a short arithmetic expression and explain their reasoning.
2. **Model:** Use the browser console to declare two values, calculate with an operator, and call a function.
3. **Guided practice:** Write a function that calculates one operation; use `if`/`else` to handle a special case.
4. **First interaction:** Connect the calculator form’s `submit` event to the function and show the result as text.
5. **Practice and check:** Students complete the calculator task. Ask them to explain the inputs, function, and one validation rule.

### Differentiation

- **Scaffold:** Provide the HTML form and function signature; students complete the calculation and event handler.
- **Extension:** Add a second validation rule or one additional operation. Arrays, objects, and loops are optional extensions rather than prerequisites for this lesson.

### Accessibility and safe coding

- Give every input a visible, associated label.
- Use a semantic form and submit button so keyboard activation works naturally.
- Put results and error messages in a text element with a polite live announcement.
- Use `textContent` for output and avoid inline event attributes.

### Assessment evidence

- A working calculator with labeled controls.
- A named calculation function and an event listener.
- Clear behavior for missing inputs and division by zero.
- A short explanation of how an input becomes a result.

### Formative check and exit prompt

- **Formative check:** Before running the calculator, ask students to trace one input through the event handler, calculation function, and validation condition, including a missing value or division by zero.
  **Evidence:** Predicted result or error message, checked against the running calculator.
- **Exit prompt:** Explain what event starts the calculation and name one special case the program handles.
  **Evidence:** Brief written or oral response.

### Transition to Unit 4.2

Review functions, conditions, and event listeners. Unit 4.2 applies those ideas to a list whose items are stored in an array and displayed from state.
