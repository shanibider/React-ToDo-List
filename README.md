# React ToDo List App 📆

<div align="center">
<img height="300px" src="https://github.com/shanibider/React-ToDo-List/assets/72359805/0ca5fdeb-4682-4a08-bf73-deb4ea824646">
</div>

This is a simple ToDo List application, utilizes several key React concepts for managing state, component composition, and event handling. Built using:
### React, utilizing the Vite.js build tool <img height=30px src="https://skillicons.dev/icons?i=react"> <img height=30px src="https://skillicons.dev/icons?i=vite">. 


# React Concepts Used 🥇
### 🎖 State Management with useState Hook

- The app uses the `useState` hook to manage two key pieces of state:
  - `inputText`: to store the value of the input field where users add new tasks.
  - `items`: to maintain the list of tasks.

### 🎖 Component Composition and Tree Management

- The app is composed of several components:
  - `App`: The main component responsible for rendering the entire application.
  - `ToDoItem`: A child component representing individual todo items.
  
- The component tree is managed efficiently, with each component focusing on a specific responsibility.

### 🎖 Event Handling

- `handleChange` function: This function handles the `onChange` event of the input field, updating the `inputText` state with the new value entered by the user.

- `addItem` function: This function adds a new item to the list of tasks (`items` state) when the user clicks the "Add" button. It utilizes the spread operator to create a new array with the updated list of items.

- `deleteItem` function: This function removes an item from the list of tasks when the user clicks the delete button on a specific todo item. It uses the `filter` method to create a new array excluding the item to be deleted.

### 🎖 Spread Operator

- The spread operator (`...`) is used in the `addItem` function to create a new array by spreading the previous items and adding the new item entered by the user. This ensures immutability of state.


## Features 🗓
- Add new tasks to the list.
- Simple and intuitive user interface.

## Getting Started 🖊

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server.
5. Open your browser and go to `http://localhost:5173` to view the app.

## Technologies Used 🎯
[![My Skills](https://skillicons.dev/icons?i=js,react,html,css)](https://skillicons.dev)
- [x] React
- [x] HTML/CSS
- [x] JavaScript


## Folder Structure 📁

```
react-todo-list/
  ├── src/
  │   ├── components/
  │   │   ├── App.js
  │   │   ├── TodoItem.js
  │   │   └── InputArea.jsx
  │   ├── index.html
  │   └── ...
  ├── public/
  │   └── styles.css
  ├── package.json
  └── ...
```

## Screenshots - 
![ToDo-React](https://github.com/shanibider/React-ToDo-List/assets/72359805/49e025cc-a121-4fcd-9fa8-3e728c2a5e5f)
![ToDo-React3](https://github.com/shanibider/React-ToDo-List/assets/72359805/ee622b94-368d-4aaf-9254-aee776d9b897)

## Code Snippets ⌨
###### App.js:
![Managing a Component Tree1](https://github.com/shanibider/React-ToDo-List/assets/72359805/3edaac48-4517-43fb-afc3-41579ab4f473)
![Managing a Component Tree2](https://github.com/shanibider/React-ToDo-List/assets/72359805/9e822021-ff15-4bfb-8fe4-176d2f59348d)

###### TodoItem.js:
![Managing a Component Tree3](https://github.com/shanibider/React-ToDo-List/assets/72359805/f23f29fc-747f-4d3a-aeb1-e49b5beb9382)

###### InputArea.jsx:
![Managing a Component Tree4](https://github.com/shanibider/React-ToDo-List/assets/72359805/5cbd753f-c5d4-4495-896f-5841411f1ebe)

> [!TIP]
> Feel free to explore my repositories and see my projects. I'm always open to collaboration and welcome feedback to improve and grow as a developer. Let's code something amazing together! 🚀😊👩‍💻💻


## 📫 Connect with me 😊
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.github.io/Portfolio/)
[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shanibider@gmail.com)

<footer>
<p style="float:left; width: 20%;">
Copyright © Shani Bider, 2024
</p>
</footer>

## License📄

This project is licensed under the MIT License.
