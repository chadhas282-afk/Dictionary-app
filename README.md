# English Dictionary App

A clean, responsive, and interactive **English Dictionary Application** built using HTML, CSS, and Vanilla JavaScript. This app fetches real-time data from a public Dictionary API to provide definitions, examples, pronunciations, and synonyms.

---

## 🚀 Features

* **Real-time Search**: Get instant results by typing a word and pressing Enter.
* **Comprehensive Data**: Displays word definitions, parts of speech, and phonetic transcriptions.
* **Usage Examples**: Provides contextual examples to help understand how words are used.
* **Synonym Support**: Lists up to five clickable synonyms that allow users to jump to new word definitions instantly.
* **Responsive Design**: A centered, mobile-friendly interface with smooth transitions.
* **Interactive UI**: Includes a clear button to reset the search and dynamic status text to guide the user.

---

## 🛠️ Technologies Used

* **HTML5**: For the application structure.
* **CSS3**: Custom styling including Google Fonts (Poppins), Font Awesome icons, and Material Icons.
* **JavaScript (ES6)**: Handles API fetching, DOM manipulation, and event listening.
* **Dictionary API**: Powered by [Free Dictionary API](https://dictionaryapi.dev/).

---

## 📂 File Structure

* `index.html`: The core layout and structure of the app.
* `style.css`: Contains all visual styles, including the "active" states and scrollbar customizations.
* `script.js`: Contains the logic for fetching data and updating the UI dynamically.

---

## 📖 How to Use

1. **Open** the `index.html` file in any modern web browser.
2. **Type** a word into the search input field.
3. **Press Enter** to fetch the meaning.
4. **Explore**:
* Read the **Meaning** and **Example** sections.
* Click on any **Synonym** to automatically search for that word.


5. **Clear**: Click the "close" icon in the search bar to reset the app.

---

## ⚙️ Development Highlights

The application uses the `fetch` API to retrieve JSON data from:
`https://api.dictionaryapi.dev/api/v2/entries/en/{word}`

It includes error handling to notify users if a word cannot be found or if there is a network issue.

---
