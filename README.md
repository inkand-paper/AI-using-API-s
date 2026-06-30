# AI-using-API-s

A minimal, single-file LLM chat web application designed to run on legacy browsers (specifically tested for Android 5 WebViews/browsers). It interacts directly with Gemini and Groq APIs using vanilla JavaScript and `XMLHttpRequest`.

## Features
- **Legacy Compatibility**: Uses webkit-prefixed Flexbox layout, standard HTML/CSS, and standard JavaScript (no ES6 features like `fetch`, arrow functions, `const/let`, etc., where unsupported, ensuring high compatibility).
- **Direct API Calls**: Connects straight to Gemini and Groq endpoints.
- **Client-Side Key Management**: Your API keys are stored secure locally in your browser's `localStorage` and never sent to any third-party server.
- **Dynamic Model Selection**: Swap between Gemini and Groq models instantly.
