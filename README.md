# To-do-List
📝 Interactive Animated Todo List
A sleek, responsive, and persistent To-Do List application designed to help users manage daily tasks with ease. This project features a modern UI with an animated gradient background and utilizes browser local storage to ensure your data stays safe even after refreshing the page.

🚀 Features
Dynamic Task Management: Add and delete tasks instantly without page reloads.

Persistent Storage: Uses localStorage to save your tasks locally in the browser.

Interactive UI:

Smooth entrance animations for new tasks.

Animated "breathing" gradient background.

Strikethrough effect for completed tasks.

Responsive Design: Built with Bootstrap 4 to ensure it looks great on mobile, tablet, and desktop.

Modern Iconography: Integrated with FontAwesome 6 for clean, recognizable action icons.

🛠️ Technologies Used
HTML5: Semantic structure of the application.

CSS3: Custom styling, Flexbox layout, and Keyframe animations.

JavaScript (ES6): DOM manipulation, event handling, and JSON data management.

Bootstrap 4: Grid system and responsive utility classes.

FontAwesome 6: Scalable vector icons for the user interface.

📂 File Structure
Plaintext
├── index.html   # Main layout and external library links
├── index.css    # Animations and custom UI styling
└── script.js    # Logic for CRUD operations and local storage
⚙️ How to Run
Clone or Download this repository to your local machine.

Ensure you have an active internet connection (to load Bootstrap and FontAwesome via CDN).

Open index.html in any modern web browser (Chrome, Firefox, Edge, etc.).

Start typing a task in the input box and click "Add".

Important: Click the "Save" button to store your changes to the browser's memory.

📖 Lessons Learned
While building this project, I focused on:

Managing complex state by syncing an array of objects with the DOM.

Using findIndex() and splice() to precisely manipulate data.

Enhancing user experience through CSS transitions and animations.

🔮 Future Roadmap
[ ] Add "Clear All" functionality.

[ ] Implement task categories (Work, Personal, etc.).

[ ] Add due dates and priority levels.

[ ] Dark Mode toggle.
