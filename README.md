Assignment 4: Forms and Validation
Alina Ibadulla, SE-2540

This assignment focuses on building user-friendly web forms, applying HTML5 built-in validation attributes, styling forms using Bootstrap 5 layout and components, and implementing client-side validation feedback (`is-valid` / `is-invalid`).

Part 1: Basic HTML Forms
Task 0 (Simple Contact Form) & Task 1 (HTML5 Validation):
   Built a basic contact form containing Name, Email, and Message fields using semantically correct `<label>` and `<input>` elements.
   Applied HTML5 attributes (`required`, `type="email"`, `minlength`, `maxlength`) to enforce browser-native validation rules for input formats and mandatory fields.

<img width="1409" height="791" alt="Screenshot 2026-10-14 at 19 19 39" src="https://github.com/user-attachments/assets/519dc52c-6723-4afc-a330-1188a0fef9df" />


Part 2: Bootstrap Forms & Validation Styles
Task 2 (Bootstrap Form Styling) & Task 3 (Bootstrap Validation Styles):
   Recreated and enhanced the contact form using Bootstrap form controls (`form-control`, `form-label`) and grid layout classes (`row`, `col-md-6`).
   Integrated custom JavaScript logic to override standard form submission (`event.preventDefault()`) and dynamically apply Bootstrap feedback classes (`is-valid` / `is-invalid`) alongside feedback messages (`valid-feedback` / `invalid-feedback`).

<img width="1402" height="790" alt="Screenshot 2026-10-14 at 19 19 50" src="https://github.com/user-attachments/assets/9d714239-b577-4da0-9d68-1c29d27a7602" />


Part 3: Advanced Registration Form Project
Task 4 (Comprehensive Registration Form):
   Designed a complete, responsive registration interface using Bootstrap Grid.
   Form components included:
     First Name and Last Name inputs (`col-md-6`).
     Email and Password fields with minimum length rules.
     Password Confirmation matching check implemented via custom JavaScript (`setCustomValidity`).
     Gender selection using custom styled Bootstrap radio buttons.
     Hobbies selection via Bootstrap checkboxes.
     Country selection dropdown using `<select>`.
     Form submission and reset buttons.

<img width="1396" height="820" alt="Screenshot 2026-10-14 at 19 20 03" src="https://github.com/user-attachments/assets/79cefaed-175c-4415-86e5-34bf7b9b50f1" />


Summary of Work Process:

1. **Structuring & Markup:**
   Developed semantic HTML5 form layouts for each requirement part, establishing correct connections between `<label for="...">` and `<input id="...">` elements.

2. **Styling & Design System:**
   Integrated Bootstrap 5 via CDN and applied custom CSS variables to create a cohesive dark UI theme (`--bg-dark: #121318`, pink/purple accents) paired with modern typography (`Plus Jakarta Sans`). Styled form controls, selects, radios, and checkboxes to align with the visual system.

3. **Interactive Validation:**
   Implemented lightweight JavaScript event listeners to perform real-time checking for password matching (`reg-password` vs `reg-confirm-password`) and handle form submit events to toggle `is-valid` and `is-invalid` states dynamically without triggering page reloads.

4. **Testing & Deployment:**
   Tested form responsiveness across different viewport sizes, verified HTML5 validation constraints, validated custom feedback states, and deployed the repository to GitHub Pages.
