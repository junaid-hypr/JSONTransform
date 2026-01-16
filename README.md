# JSON Transform Playground

A powerful, interactive playground for **ST.js** (SelectTransform), allowing you to transform JSON data using JSON templates in real-time.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🚀 Live Demo
**[Try it online here!](https://junaid-hypr.github.io/JSONTransform/)**

## ✨ Features

- **Real-time Transformation**: See your results instantly as you type.
- **Three-Pane Layout**:
  - **Data Input**: Your source JSON.
  - **Template Input**: The ST.js template to apply.
  - **Result Output**: The transformed JSON output.
- **Advanced Search & Replace**:
  - VS Code-style search widget (Ctrl+F).
  - Visual highlighting of matches without focus stealing.
  - Search & Replace functionality.
  - Regular expression support (case-insensitive).
  - Scoped to each pane (Data, Template, Result).
- **Productivity Tools**:
  - **Prettify**: Auto-format your JSON with a single click.
  - **Shareable URLs**: Encodes your current state into the URL to share specific transformations with others.
  - **File Operations**: Upload JSON files and save your templates.
  - **Theme Support**: Toggle between Dark and Light modes.
  - **State Persistence**: AUtomatically saves your work to `localStorage` so you never lose context.

## 🛠️ Usage

1. **Enter Data**: Paste your source JSON into the **Data** pane.
2. **Create Template**: Define your transformation rules in the **Template** pane using ST.js syntax.
3. **View Result**: The **Result** pane automatically updates with the transformed output.

### Shortcuts
- `Ctrl + F`: Open Search
- `Ctrl + H`: Open Replace (in Data/Template panes)
- `Ctrl + A`: Select All (Scoped to the active pane)
- `Esc`: Close Search

## 💻 Local Development

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/junaid-hypr/JSONTransform.git
   cd JSONTransform
   ```

2. **Install dependencies** (optional, mostly for the server):
   ```bash
   npm install
   ```

3. **Start a local server**:
   You can use any static file server. Using `http-server` via `npx`:
   ```bash
   npx http-server .
   ```

4. **Open in Browser**:
   Navigate to `http://127.0.0.1:8080/index.html`.

## 📚 About ST.js
This playground is built around the **ST.js** library. For full documentation on the template syntax and capabilities, please refer to the [ST.js Repository](https://github.com/SelectTransform/st.js).

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
