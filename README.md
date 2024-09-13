# [Kanban Board Application](https://kanban-board-frontend-kk.vercel.app)


## Description

A Kanban Board built using React.js. It has the following features:
- Fetches data from [API](https://api.quicksell.co/v1/internal/frontend-assignment )
- Dynamic grouping of data based on the following parameters
  1. **By Status**: Group tickets based on their current status.
  2. **By User**: Arrange tickets according to the assigned user.
  3. **By Priority**: Group tickets based on their priority level.
- Dynamic ordering of tickets based on the following parameters
  1. **Priority**: Arrange tickets in descending order of priority.
  2. **Title**: Sort tickets in ascending order based on their title.
- Responsive design for smaller screen sizes
- Vanilla CSS styling
- Components structured in a reusable and maintainable manner
- Persistance of State


## Technology used

- React.js - Frontend
- Postman - testing API
- Vercel - Hosting Service


## Features

- Group tickets by status, user, or priority.
- Sort tickets by priority or title.
- Visually appealing and responsive design.
- Ability to save the user's view state in local storage.
- Priority levels are defined as Urgent (4), High (3), Medium (2), Low (1), and No priority (0).


## Demo

You can see a live demo of the Kanban board application [here](https://kanban-board-frontend-kk.vercel.app).


## Usage

1. Click the "display" button to fetch and display the tickets from the provided API.
2. Select one of the three grouping options: "By Status," "By User," or "By Priority."
3. Choose the sorting option: "Priority" or "Title."
4. The Kanban board will dynamically adjust to reflect your choices.
5. The application will save your view state, so you can return to your preferred settings even after a page reload.


**Enjoy using the Kanban board application to manage your tasks efficiently!**
