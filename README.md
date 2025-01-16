# service-di-deep-dive

Simulates a Todo App Tasks to develop dependency injection based on Angular guides, essential practices, injection tokens, semantic and signals

## Project Structure

```
src/app
│
├── tasks
│ ├── new-task # responsible for input task
│   ├── new-task.component.css
│   ├── new-task.component.html
│   └── new-task.component.ts
│ ├── tasks-list # responsible for display and manage N tasks
│   ├── task-item # responsible for display and update 1 task
│     ├── task-item.component.css
│     ├── task-item.component.html
│     └── task-item.component.ts
│   ├── tasks-list.component.css
│   ├── tasks-list.component.html
│   └── tasks-list.component.ts
│ ├── task.model.ts # Model for input data
│ ├── tasks.component.html
│ ├── tasks.component.ts
│ └── tasks.service.ts # Service for tasks logic (add/update "DML")
│
├── app.component.html # Template that orchestrates components
├── app.component.ts # Root component logic
├── loggin.service.ts # Logger service to inject on Angular application
│
├── index.html # Boostrap page
├── main.ts # Boostrap Angular
│
└── styles.css # Global styles
```

## Installation

Use the package manager [npm](https://www.npmjs.com/) and start app

```gitbash
npm install
```

## Usage

```gitbash
npm start
```

1. Open in your browser http://localhost:4200/
2. Insert title and description
3. Press "Add Task" button
4. Filter tasks by "Status" dropdown

## License

[MIT](https://choosealicense.com/licenses/mit/)

<p align="center">
  <img src="https://i.imgur.com/m9Pl9Xd.png" alt="Practice - to-do-tasks - app"/>
</p>
