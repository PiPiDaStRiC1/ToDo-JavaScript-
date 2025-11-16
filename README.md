# 🚀 ToDo List App

A web application to help you manage your daily tasks. 🎯

## 🔥 Features

*   **📥 Add Task:** Create a new task in your list
*   **☑️ Complete Task:** Mark a task as completed
*   **📝 Edit Task:** Edit the text of a task
*   **❌ Delete Task:** Remove a task from the list
*   **🔍 Filter Tasks:** Show All, Active, or Completed tasks
*   **🫳 Drag & Drop:** Reorder tasks in the list

## 📸 Screenshots

### Desktop View
![Desktop View](./assets/preview/desktop-dark.png)

### Mobile View
![Mobile View](./assets/preview/mobile-light.png)

## 💻 Tech Stack

*   **Frontend:** HTML, CSS, JavaScript  
*   **Styling:** SCSS/CSS  
*   **Bundler:** Parcel

## 🚀 Run the project

Requirements:
- Node.js (recommended >= 14)
- npm (bundled with Node.js)

1) Install dependencies:
```powershell
cd c:\Users\artem\HTML\toDo\ToDo-JavaScript-
npm install
```

2) (Optional but recommended) Install Parcel as a dev dependency:
```powershell
npm install --save-dev parcel
```

3) Start the dev server:
```powershell
npm run start
```
If `start` script is not present in package.json, run:
```powershell
npx parcel index.html
```

4) Open the app in your browser: http://localhost:1234 (Parcel default)

Build for production:
```powershell
npm run build
# or
npx parcel build index.html
```

## package.json scripts example

Add these scripts to package.json if they are missing:
```json
{
  "scripts": {
    "start": "parcel index.html",
    "build": "parcel build index.html"
  }
}
```

Tips:
- If the dev server fails, try removing the `.parcel-cache` folder and retry.
- Use the `--open` option with Parcel to automatically open the browser.