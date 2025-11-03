 🧩 Jeopardy Game API

> A browser-based Jeopardy game built with HTML, CSS, JavaScript, and Axios — powered by the [Rithm Jeopardy API](https://rithm-jeopardy.herokuapp.com/api).
> Features randomized categories, dynamic board generation, interactive question-answer flow, and restart logic.


🎯 Jeopardy! — Browser Edition

A web-based Jeopardy game that dynamically fetches categories and clues using the [Rithm Jeopardy API](https://rithm-jeopardy.herokuapp.com/api).  
Built in **Vanilla JavaScript** with Axios for API calls and jQuery for simple DOM manipulation.


🚀 Features

- 🎲 Randomized categories on each play
- 💡 Interactive clue reveal system (Value → Question → Answer)
- ⚡ Live API integration
- 🔁 Restartable game sessions
- 🧠 Automatic “Game Over” message when all clues are played
- 📱 Responsive layout for modern browsers



🧩 Tech Stack

| Technology | Purpose |
|-------------|----------|
| HTML5 / CSS3 | Layout and styling |
| JavaScript (ES6) | Game logic and event handling |
| Axios | HTTP requests to the API |
| jQuery | DOM manipulation |
| Rithm API | Trivia data source |



⚙️ How It Works

1. On “Play Game,” the app fetches **100 categories**.
2. It randomly selects **6 categories** that each have **≥5 clues**.
3. Each category fetches full data via `/category?id=<id>`.
4. The board is built dynamically with 5 clues per category.
5. Click a clue cell to reveal:

   * First click: show question
   * Second click: show answer
   * Third click: clear clue (locked)
6. Game ends automatically once all clues are answered.



🧠 API Endpoints

| Endpoint                | Description                            |
| ----------------------- | -------------------------------------- |
| `/categories?count=100` | Fetches available categories           |
| `/category?id=<id>`     | Fetches a specific category with clues |


💻 Developer Notes

 This project follows a simple modular pattern:

  * `index.html` → structure
  * `style.css` → styling
  * `jeopardy.js` → game logic
* Each clue is clickable only once.
* Code uses async/await for clarity and error handling.



🧑‍💻 Author

**Jonathan Ndakola**
Creative Designer • UX/AI Developer • Software Developer
📍 Jacksonville, FL
🔗 [LinkedIn](https://www.linkedin.com/in/jonathan-ndakola)
https://ndakola-portfolio--ndakola-portfolio.us-central1.hosted.app/#home


🪄 License

MIT License © 2025 Jonathan Ndakola



⭐️ Show Your Support

If you like this project, please **star** the repo and share it with others who love learning JavaScript through games!

```

---

Would you like me to generate the **exact GitHub commit message and repository setup commands** (e.g., `git init`, `git add`, `git commit -m "Initial Jeopardy game"`, `git push`)?
```
