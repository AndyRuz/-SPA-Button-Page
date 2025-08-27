# Button Compliment Page

### Overview:
A single-page web app that is a page consisting of random interactive buttons built with HTML, CSS, and JavaScript. The goal of this application is to create a browser with multiple different buttons that the user can interact with (by: Andy Ruzicka)

### Features:
- Interactive Buttons: Clicking any of the nine buttons displays a unique message in the result area.
- Local Storage: The app remembers how many times you’ve clicked buttons, so if you leave and come back, it shows your past interactions.
- Dynamic Updates: The page never reloads when you click a button—the content changes with JavaScript.
- Animations and Styles: Buttons have hover effects, animations, and color highlights for a more engaging design.

### How It Works:
The app starts with a grid of nine buttons on the page. When you click on any button, JavaScript updates the result area to show a special message and changes the color highlight. This happens without reloading the page. Every time you click, the app saves your interaction in localStorage. That way, if you close the page and come back later, the app remembers how many times you’ve clicked and even shows a welcome back message.

The design uses HTML for the structure, CSS for styling and animations, and JavaScript for the interactivity. The layout also adjusts to fit different screen sizes, and you can use either your mouse or keyboard to interact with the buttons.

### Choices & Challenges:
- I decided to keep the project simple with plain HTML, CSS, and JavaScript. This made it easier to understand the basics of how SPAs work.

- For styling, I used CSS variables and gradients so the app would look modern without needing external CSS frameworks.

- A small challenge I faced was making the buttons accessible for keyboard users and screen readers, but I added focus outlines and keyboard event listeners to fix this.

### Getting Started/Deployment:
- https://andyruz.github.io/-SPA-Button-Page/
- https://github.com/AndyRuz/-SPA-Button-Page.git
