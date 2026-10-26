# Chef Claude 🍳

An AI-powered recipe generator built with React. Add the ingredients you currently have on hand, and Chef Claude will suggest a delicious recipe using Hugging Face / Anthropic AI models.

Built as part of the Scrimba Fullstack Developer Path (React.js Fundamentals).

---

## Features

- **Ingredient Tracker:** Add ingredients dynamically to build your current pantry list.
- **Conditional Rendering:** Context-aware UI that prompts for recipe generation once sufficient ingredients are added.
- **AI-Powered Recipes:** Fetches tailored recipe recommendations using modern LLM APIs (`@anthropic-ai/sdk` / `@huggingface/inference`).
- **Markdown Rendering:** Formats generated recipes cleanly using `react-markdown`.
- **Modern Form Handling:** Uses React 19 form actions and state management best practices.

---

## Tech Stack

- **React 19**
- **Vite / Scrimba Scaffolding**
- **CSS3** (Custom Responsive Layout)
- **Anthropic AI SDK / Hugging Face Inference**
- **React Markdown**

---

## Project Structure

```text
├── components/
│   ├── ClaudeRecipe.jsx     # Renders the markdown recipe response
│   ├── Header.jsx           # App navbar and branding
│   ├── IngredientsList.jsx  # Pantry list and "Get Recipe" CTA
│   └── Main.jsx             # Core state, form handling, and layout
├── images/
│   └── chef-claude-icon.png
├── ai.js                    # LLM API integration logic
├── App.jsx                  # Root wrapper
├── index.css                # Global styles
├── index.jsx                # Entry point
└── recipeCode.md            # Reference prompt / markdown templates
