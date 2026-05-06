# 💻 Login Form - Dev em Dobro

A simple and modern login form built during the Dev em Dobro online course.

##  Technologies Used
* Vite
* React
* TypeScript
* Tailwind CSS

##  Features
* **Responsive Interface:** The layout adapts well to different screen sizes.
* **Componentization:** Organized structure utilizing React functional components (`LoginForm.tsx`).
* **Custom Styling:** Advanced use of Tailwind CSS to create inputs with specific colors and borders.
* **Custom Checkbox:** Hiding the native checkbox input in favor of a styled and interactive visual element using Tailwind's `peer` class.
* **Default Behavior Prevention:** Handling the form's `submit` event with React (`e.preventDefault()`) to avoid unnecessary page reloads.

##  What I Learned
* Further learn how to structure a basic project using **Vite** and **React**.
* How to correctly type form events using **TypeScript** (`FormEvent<HTMLFormElement>`).
* Interesting **Tailwind CSS** techniques, such as using pseudo-classes (`peer-checked`) to alter the style of sibling elements, making it incredibly easy to create custom checkboxes without relying on heavy JavaScript.