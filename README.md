# Chef Claude 🍳

**Chef Claude** is an interactive React application. It empowers users to manage a dynamic pantry list of ingredients and leverage AI to instantly generate customized, mouth-watering recipes based on what they have on hand.

---

## ✨ Features

* **Dynamic Pantry Management:** Add new ingredients to your list on the fly using React form actions.
* **AI Recipe Generation:** Connects with AI SDK endpoints (`@anthropic-ai/sdk` and `@huggingface/inference`) to turn your available ingredients into structured cooking instructions.
* **Smooth Scrolling Effects:** Utilizes `useEffect` and `useRef` hooks along with custom coordinate calculations to smoothly scroll down to the generated recipe section.
* **Markdown Rendering:** Formats AI-generated text cleanly using `react-markdown`.

---

## 🛠️ Tech Stack

* **Library:** React (v19)
* **Build Tool:** Vite
* **Styling:** CSS3
* **Libraries & SDKs:** 
  * `react-dom`
  * `react-markdown`
  * `@anthropic-ai/sdk`
  * `@huggingface/inference`

---

## 📁 Project Structure

```text
├── components/
│   ├── ClaudeRecipe.jsx    # Displays the generated recipe output
│   ├── Header.jsx          # Application header banner
│   ├── IngredientsList.jsx # Lists ingredients currently on hand
│   └── Main.jsx            # Core state management, side effects, and layout logic
├── images/                 # App assets and icons
├── ai.js                   # AI API integration helpers
├── App.jsx                 # Root application component
├── index.css               # Global application styles
└── index.jsx               # React DOM entry point
