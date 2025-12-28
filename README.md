**Capital Quiz** is a fully-featured, browser-based quiz game designed to test your knowledge of world capitals, Indian state capitals, and Canadian province capitals. It runs entirely in your browser (desktop or mobile), requires no login, and supports multiple players sharing the same link.

---

## **Demo / Hosting**

You can host the game using **GitHub Pages** or any static web hosting. Once hosted, players can access it on any device via a URL.

Example:

```
https://yourusername.github.io/capital-quiz-pro/
```

---

## **Features**

### 1. **Extensive Question Database**

* **World Capitals** – full 195+ countries plus partially recognized states and territories.
* **Continents** – additional categories:

  * African countries
  * Asian countries
  * European countries
  * North American countries
  * South American countries
  * Oceania
  * Middle East
* **India** – all state capitals.
* **Canada** – all provincial and territorial capitals.
* **Multiple capitals supported** – e.g., South Africa: Pretoria, Cape Town, Bloemfontein.

---

### 2. **Gameplay**

* Players can select:

  * **Category** (World, continents, India, Canada)
  * **Difficulty** (Easy / Medium / Hard)
  * **Multiple Choice Mode** (optional)
* **Session Limit:** 30 questions per session. After 30 questions, the final score is displayed with a 🎉 emoji.

---

### 3. **Answer Features**

* **Text input or multiple choice**, depending on settings.

* **Case-insensitive** answers.

* **Spelling tolerance**:

  * Easy → allows ~25% minor misspellings
  * Medium → allows ~15% minor misspellings
  * Hard → exact match only

* Feedback after submitting:

  * ✅ Correct
  * 🟡 Accepted (minor spelling error)
  * ❌ Wrong (shows correct answer)

* **Reveal Answer button** – shows the correct answer for the current question without affecting the score.

---

### 4. **Score Tracking**

* Tracks correct/total answers.
* Reset button to restart the session at any time.

---

### 5. **Sound Effects**

* Correct answer → cartoon “clang” sound
* Wrong answer → cartoon “wood plank flick” sound

---

### 6. **Dark Mode**

* Fully dark-themed interface for easy reading and mobile-friendliness.

---

## **How to Play**

1. Open the game in a browser (mobile or desktop).
2. Select:

   * **Category** (World / Continent / India / Canada)
   * **Difficulty** (Easy / Medium / Hard)
   * **Enable Multiple Choice Mode** (optional)
3. Click **Start Quiz**.
4. Read the question and either:

   * Type the answer in the input field
   * Click a multiple choice button (if enabled)
5. Click **Submit** to check your answer.
6. Use **Next** to go to the next question.
7. Click **Reveal Answer** if you want to see the correct answer without affecting your score.
8. After 30 questions, your **final score** is displayed along with 🎉.
9. Use **Reset Score** to start a new session.

---

## **Installation / Hosting on GitHub Pages**

1. **Create a GitHub repository**:

   * Repository name: `capital-quiz-pro`
   * Public repository.

2. **Upload the HTML file** (rename to `index.html`).

3. **Enable GitHub Pages**:

   * Go to repository → Settings → Pages
   * Branch: `main` (or `master`)
   * Folder: `/root`
   * Save → GitHub provides a URL for your game.

4. Access the URL on any device and share it with friends.

---

## **Customization**

* **Add more countries or capitals**: Extend the `worldCapitals`, `indiaCapitals`, or `canadaCapitals` objects in the script.
* **Adjust session length**: Change `const sessionLimit = 30;` in the script.
* **Sound effects**: Replace the audio URLs with your preferred sounds.
* **Difficulty tuning**: Modify the similarity threshold in the `submitAnswer()` function.

---

## **Technical Notes**

* Built entirely with **HTML, CSS, and JavaScript**. No server-side code required.
* All game logic runs **client-side** in the browser.
* Supports **modern browsers** on mobile and desktop.
* Works **offline** once the HTML file is loaded in the browser.

---

## **Credits**

* Sound effects: [Google Actions Sounds](https://developers.google.com/assistant/actions/sounds)
* Game design & coding: Self-contained JS logic

---

## **License**

* Free to use, share, and modify for personal and educational purposes.

---
