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




### Personal Reflection:
When I started this project, I was honestly way too confident about what I could pull off. My original plan was to build this memory card matching game because I figured, How hard could it be? Just flip some cards, match pairs, boom - done. I mean, I've played those games a million times, so coding one seemed like it'd be pretty straightforward for my first real single-page application.
Yeah, that was naive. Once I actually sat down and started thinking through all the moving pieces, I realized I was in way over my head. Like, keeping track of which cards were flipped, making the animations work smoothly, preventing people from spam-clicking cards while they're still flipping, handling the win conditions, it was getting overwhelming fast. I probably spent two whole days just staring at my code, trying to figure out the game state logic, before I admitted defeat.

So I had to swallow my pride and scale way back. Instead of going too intense with a game, I decided to just make a simple app with nine buttons that would show different positive messages when you clicked them. Not exactly groundbreaking stuff, but hey, at least I knew I could actually finish it without pulling multiple all-nighters. Plus, it still hit all the SPA requirements like dynamic content updates, no page reloads, and interactive elements. Sometimes you gotta know when to pivot. Honestly, this whole experience taught me a lot about scoping projects realistically. Now I get why my professor keeps emphasizing the importance of breaking things down and starting small. It's better to have a working, simple app than a half-broken, complicated one that crashes every time someone looks at it wrong.

The development process had its moments, though. One thing that really stumped me was figuring out how to save user interactions between sessions. I was genuinely considering trying to set up some kind of database until I discovered localStorage. That was definitely one of those "wait, it's THAT easy?" moments. Being able to greet returning users and remember their previous clicks made the whole thing feel way more polished than it actually was.

Accessibility was another reality check for me. I usually just focus on making things look decent and work properly, but this project forced me to actually think about users who might navigate differently. Adding proper focus indicators and keyboard navigation wasn't as intuitive as I expected. I'm pretty sure my implementation isn't perfect, but at least now I understand why accessibility can't just be an afterthought. It's definitely something I need to get better at.

Looking back, I'm actually glad I had to simplify my original idea. It helped me learn way more from completing something than I would have from abandoning a half-finished mess. I feel way more comfortable with vanilla JavaScript and HTML now, and I have a better sense of what goes into planning a project from start to finish. For next time, I want to try something a bit more challenging, maybe even circle back to that memory game idea, but with way better planning upfront. I think I understand my capabilities better now, which hopefully means I can set more realistic goals while still pushing myself to grow. This whole experience was humbling but honestly pretty rewarding in the end.
