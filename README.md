Kanban Board - ReactJS

Overview
This project is a Kanban Board built with ReactJS that allows users to manage tasks across different stages:
- To Do
- In Progress
- Peer Review
- Done

It supports drag-and-drop functionality, search filtering, and a floating button to add new tasks.

---
Features
- Drag-and-drop tasks between columns
- Search bar to filter tasks by title
- Floating button to add new tasks (only in the "To Do" column)
- Responsive UI using Material-UI (MUI)
- Clean and modular folder structure

---
Installation and Setup

Prerequisites
Ensure that Node.js and npm are installed. You can verify this by running:
```sh
node -v
npm -v
```
If not installed, download Node.js from [here](https://nodejs.org/).
Clone the Repository
```sh
git clone https://github.com/YOUR-GITHUB-USERNAME/kanban-board.git
cd kanban-board
```

### Install Dependencies
```sh
npm install
```
This will install all required dependencies including React, Material-UI, and react-dnd.

### Start the Application
```sh
npm start
```
The application will open automatically in your default browser at:
```
http://localhost:3000
```

---
## Usage
1. **Add a New Task:** Click the floating button, enter a title and description, and add a task. It will appear in the "To Do" column.
2. **Move a Task:** Drag a task card from one column to another.
3. **Search for a Task:** Use the search bar to filter tasks by title.

---
## Technologies Used
- ReactJS (Frontend Framework)
- React-DnD (Drag-and-Drop Functionality)
- Material-UI (MUI) (UI Components & Styling)
- React Hooks (useState, useEffect)

---
## Folder Structure
```
kanban-board/
├── src/
│   ├── components/
│   │   ├── KanbanBoard.js
│   │   ├── KanbanColumn.js
│   │   ├── TaskCard.js
│   ├── App.js
│   ├── index.js
│   ├── styles.css
├── public/
├── package.json
└── README.md
```

---
## Contribution
Contributions to this project are welcome. Fork the repository and submit a pull request for improvements.

---
## Author
Developed by Samineni Janaki

---
## License
This project is licensed under the MIT License.
