# React ToDo List App 📆
[![Javascript](https://img.shields.io/badge/JavaScript-★★★★★-orange)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React](https://img.shields.io/badge/React-★★★★★-blue)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-★★★★★-yellow)](https://vitejs.dev/)

A simple ToDo List application utilizes several key React concepts for managing state, component composition, and event handling. Built using: **React, utilizing the Vite.js build tool** <img height=25px src="https://skillicons.dev/icons?i=react"> <img height=25px src="https://skillicons.dev/icons?i=vite">. 

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






## Technologies Used 🎯
[![My Skills](https://skillicons.dev/icons?i=react,vite,js)](https://skillicons.dev)

- **React**: A JavaScript library for building user interfaces.
- **Vite.js**: A build tool that provides a fast development environment.
- **JavaScript (ES6+)**: Modern JavaScript features and syntax.
- **CSS**: Styling for the components.



## Screenshots - 
![Todo 1](https://github.com/shanibider/React-ToDo-List/assets/72359805/5a36e113-2e2e-4f08-8289-5b960da5547d)
![Todo 2](https://github.com/shanibider/React-ToDo-List/assets/72359805/2adb59c0-774e-4a9c-94ce-5566c9eac682)
![Todo 3](https://github.com/shanibider/React-ToDo-List/assets/72359805/8e9062aa-ffa9-4f24-99de-b66db8a1e24e)


## Code Snippets ⌨
###### App.js:
![2](https://github.com/shanibider/React-ToDo-List/assets/72359805/b4962f4b-8de8-4654-963a-84ff69a0cafe)

###### TodoItem.js:
![3](https://github.com/shanibider/React-ToDo-List/assets/72359805/a4e3da1f-dea7-4ef3-a73a-9c84381078c6)

###### InputArea.jsx:
![1](https://github.com/shanibider/React-ToDo-List/assets/72359805/58e3d33c-a505-43e7-b581-9e6c08131355)

###### style.css
![4](https://github.com/shanibider/React-ToDo-List/assets/72359805/13aac8e3-da6c-48d1-b8be-643d1a65e077)




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


## 🚀 Running the Projects
To get started with these projects, clone the repository and install the dependencies.
To run any of the projects, navigate to the project directory and start the development server:

```bash
git clone <link-to-project>
npm i
npm run dev
```

> [!TIP]
> Feel free to explore my repositories and see my projects. I'm always open to collaboration and welcome feedback to improve and grow as a developer. Let's code something amazing together! 🚀😊👩‍💻💻


## 🚀 Contact
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.onrender.com/)
<br>For any questions or feedback, please reach out to [shanibider@gmail.com](mailto:shanibider@gmail.com).


---

Happy Coding! 🎉

## License📄

This project is licensed under the MIT License.
