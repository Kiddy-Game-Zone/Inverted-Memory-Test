# 🔄 Inverted Memory Test Game 🧠

Test your focus and adaptability! ✨ Watch a sequence of colorful shapes appear on the canvas, then try to repeat the sequence by clicking the shapes. But watch out – the rules might suddenly flip, requiring you to recall the sequence in **reverse**! 🤯 Can you keep up?

---

## 🔥 Features

* **🧠 Memory Challenge:** Tests your ability to recall increasingly long sequences of shapes and colors.
* **↔️ Rule Inversion:** At higher levels, the game might suddenly require you to recall the sequence in *reverse* order, adding a tricky twist!
* **🎨 Visual Sequences:** Uses p5.js to display colorful shapes (circles, squares, triangles, stars) dynamically on a canvas.
* **👆 Clickable Input:** Repeat the sequence by clicking on the displayed shape buttons.
* **📊 Performance Tracking:** Tracks your level, successes, attempts, and failure rate.
* **🎨 7 Vibrant Themes:** Customize the game's appearance! Themes are saved using `localStorage`.
    * 🎨 Default (Purple/Lime)
    * 🌊 Ocean Blue
    * 🌲 Forest Green
    * ✨ Cosmic Purple
    * ☀️ Sunny Yellow
    * 🍬 Candy Pink
    * 🌙 Night Mode
* **📱 Fully Responsive:** Plays smoothly on desktops, tablets, and mobile devices.
* **🤩 Animated & Playful:** Modern design with smooth transitions and clear feedback.
* **🔁 Game Reset:** Start over anytime with the reset button.

---

## 🎮 How to Play

1.  **Start Round:** Click the "🚀 Start Round" button.
2.  **Watch Carefully:** Observe the sequence of colorful shapes displayed one by one on the canvas. 👀
3.  **Recall:** Once the sequence finishes, clickable buttons representing the shapes in that sequence will appear below the canvas (in a shuffled order).
4.  **Click the Sequence:** Click the shape buttons in the **exact order** they were shown.
5.  **Watch for the Twist!** At higher levels, the game might tell you the rule is **REVERSED** 🔄. If so, you must click the shapes in the **reverse order** they were shown!
6.  **Feedback:** The game will tell you if you were correct or not.
7.  **Next Round:** If correct, the sequence gets longer! Click "🚀 Next Round" to continue. If incorrect, you can try again by clicking "🚀 Next Round".
8.  **Reset:** Click "Reset Game 🔁" at any time to start back at level 1 with the normal rule.

---

## 🎨 Available Themes

Change the game's look anytime using the theme selector dropdown in the top-right corner. Your preference is saved!

* 🎨 **Default:** A playful purple and lime theme.
* 🌊 **Ocean Blue:** Cool blues and cyans.
* 🌲 **Forest Green:** Earthy greens and yellows.
* ✨ **Cosmic Purple:** Deep space indigos and violets.
* ☀️ **Sunny Yellow:** Bright yellows and oranges.
* 🍬 **Candy Pink:** Sweet pinks and purples.
* 🌙 **Night Mode:** A comfortable dark theme.

---

## 💻 Technologies Used

* **HTML5:** For the core structure.
* **CSS3:** For styling, themes, and animations.
    * **Tailwind CSS:** For utility classes and rapid development.
    * **CSS Variables:** For managing the 7 themes.
* **JavaScript (ES6+):** For game logic (sequence generation, state management, rule inversion, scoring), DOM manipulation, theme switching, and `localStorage`.
* **p5.js:** For drawing the shape sequences dynamically on the HTML canvas.

---

## 🏃 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the directory:**
    ```bash
    cd <repository-folder-name>
    ```
3.  **Open the file:** Simply open the `index.html` file (or your main HTML file) in your web browser.

No build steps or installations are required! Test your memory! 💪

---

## ❤️ Built By

This game was built with ❤️ by Anas.
